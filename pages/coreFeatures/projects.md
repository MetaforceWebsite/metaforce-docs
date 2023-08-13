# Projects

Metaforce Project is a lightweight and powerful code editor for salesforce development.  
Compared to VS Code, `Metaforce Code Editor` has a user friendly interface and provides many handy actions, like code comparison, test execution, etc.

## Package XML Builder

In salesforce, a `package.xml` file defines the components that you’re trying to retrieve or deploy.  
Here is a simple package xml file:

    <?xml version="1.0" encoding="UTF-8"?>
    <Package xmlns="http://soap.sforce.com/2006/04/metadata">
        <types>
            <members>MyCustomObject__c</members>
            <name>CustomObject</name>
        </types>
        <types>
            <members>*</members>
            <name>CustomTab</name>
        </types>
        <types>
            <members>Standard</members>
            <name>Profile</name>
        </types>
        <version>58.0</version>
    </Package>

To build/update a package xml, you can use `Package XML Builder` to quickly choose components and save/export as a package xml file.

## metaforce-manifest.xml

Instead of package.xml, Metaforce Project use its own xml file named `metaforce-manifest.xml`.

-   The file metaforce-manifest.xml is `auto generated` while you create a new project.
-   The file metaforce-manifest.xml file can be `updated via Package XML Builder`.
-   The file metaforce-manifest.xml file can be `retrieved to refresh its all components`.

## Code Editor Actions

### Save On Local (Cmd + S)

### Save To Salesforce (Cmd + Shift + S)

### Refresh From Salesforce (Cmd + Shift + R)

### Show Apex Coverage

### Open In Salesforce (Cmd + Shift + O)

### Show Apex Coverage

### Diff With Target Org

### View References

### View Console Logs (Cmd + Shift + L)

### Format Code (Cmd + Shift + F)

### Editor Font Size

### Editor Themes
