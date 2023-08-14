# Data Operations

> For cross-object field reference, you can directly input the reference field name and press `Enter`. The field name will be directly added as a field under the 'Choose fields' dropdown list.

## Bulk Export via Bulk API

Export salesforce records as CSV file via Bulk API via 3 steps below:

1. Choose a salesforce org connection
2. Choose an object & fields, set where conditions to filter your records.
3. Review your export info and Start it.

![data-export-info](./images/data-export-info.jpg)

## Bulk Import via Bulk API

Import your csv data into salesforce via Bulk API.

### CSV Fields Mapping

-   Click `Auto Match Fields` button to auto map csv header with object fields.
-   `The 'read-only' field can't be mapped`, like formula fields, system fields, etc.
-   `External lookup is supported.` You can choose an external id field on the lookup object to populate the lookup field automatically.

![data-import-mapping](./images/data-mapping.jpg)

### Preview Import Info

In the last step of Import, you can preview all import info in one place.

-   Before the import, you can review the `target org`, the `target object`, the `CSV field mapping`, `number of csv rows`.
-   After the import, you can view bulk `import job status`, `number of success/fail records`, `download results`.

![data-import-info](./images/data-import-info.jpg)

## Data Migration via REST API

This feature helps you to move salesforce records directly from the source org to the target org.

It supports 3 data migration types:

-   `Insert` - insert all records as new in the target org.
-   `Update` - Update all records based on the record id.
-   `Upsert` - Upsert all records based on selected external field.
