# Data Operations

## Export records via bulk api 2.0

Compared with dataloader or other tools, Metaforce provides a better experience to start a bulk export job in a super easy way.

Open metaforce and follow steps to export your data now!

1.  Name your export operation and choose the org connection
2.  Choose object & fields, and set soql where clause to filter records.
    ![data-export-info](./images/data-export-info.jpg)

    > [!Tip|style:flat|label:Tips]
    >
    > 1. For soql where clause, it must starts with the "where" keyword. For example, `WHERE CreatedDate > Last_Year ORDER BY LastModifiedDate DESC LIMIT 1000`.
    > 2. To add child-to-parent relationship fields, you can `input the relationship field name` and press `Enter` as below. For example, input "CreatedBy.Name" and press "Enter".  
    >    ![data-export-info](./images/data-export-cross-fields.jpg)

3.  Start the export, view export job result, and download the csv file.
    ![data-export-result](./images/data-export-result.jpg)

## Import records via bulk api 2.0

Compared with dataloader or other tools, Metaforce provides a better experience to start a bulk import job in a super easy way.

### CSV Fields Mapping

-   Click `Auto Match Fields` button to auto map csv header with object fields.
-   `The 'read-only' field can't be mapped`, like formula fields, system fields, etc.
-   `External lookup is supported.` You can choose an external id field on the lookup object to populate the lookup field automatically.

![data-import-mapping](./images/data-mapping.jpg)

### Preview Import Info

Before starting the data import, please review following settings to.

-   If you're doing insert or upsert, please always exclude the "Id" field from your mapping.
-   Make sure mappings between csv header and object field are accurate.

![data-import-info](./images/data-import-info.jpg)

## Data Migration via REST API

This feature helps you to move salesforce records directly from the source org to the target org.

It supports 3 data migration types:

-   `Insert` - insert records as new in the target org.
-   `Update` - Update records based on the record id.
-   `Upsert` - Upsert records based on selected external Id field.
