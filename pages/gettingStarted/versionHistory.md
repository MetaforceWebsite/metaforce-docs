# Verison history

## Version 2.3

Released on Aug 9, 2023  
**📣 Project Improvements - 3 ways to quickly retrieve latest metadata**

1.  **Single Retrieve** - Open a metadata file and Click "Refresh" button in right action bar.
2.  **Folder Retrieve** - Right click the folder of metadata and Click "Refresh Components In Folder". All components under the folder will be retrieved.
3.  **Manifest Retrieve** to refresh all components in xml file.
    -   Right click "metaforce-manifest.xml" file in project side bar and start to retrieve.
    -   Open "metaforce-manifest.xml" file and Click "Refresh" button in right action bar.

**📣 Data Operation Improvements**

1. Data Import via Bulk api - Auto run assignment rule(s) for "Lead", "Case" records.
2. Data Migration via Rest api - Auto run assignment rule(s) for "Account", "Lead", "Case" records.

**❤️ Bug Fixes**

-   Bulk Data Import - the lookup field couldn't be auto updated via the external id field on the lookup object.

## Version 2.2

Released on Aug 3, 2023

**New Feature & Enhancements**

-   Project
    -   Create Custom Object and Fields from Metaforce directly, faster and easier!
        -   Available object type: Custom Object, Custom Setting, Custom Metadata Type, Platform Event.
    -   Quickly retrieve project metadata from the project header.
    -   Auto reload project sidebar after retrieving metadata without a page reload.
-   Deployment
    -   Quickly switch source org and target org.
