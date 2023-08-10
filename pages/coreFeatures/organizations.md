# Organizations

> 💡 Within Metaforce, all your salesforce organizations can be connected and managed via OAuth 2.0 protocol. You can easily switch logins between different salesforce organizations just by one click! No need to use password and MFA code any more!

### Connect salesforce organzation

Metaforce connects salesforce organizations via [OAuth 2.0](https://oauth.net/2/) protocol. All salesforce orgs with following salesforce login urls are supported:

-   **https://login.salesforce.com**, includes Production, Developer Edition, Trailhead Playground, etc.
-   **https://test.salesforce.com**, only for sandbox

> 🛠️ Go to “Organizations” → “New Organization” → “Choose an organization type”
>
> ℹ️  If your organization can only be logged in from a custom domain, please choose the corresponding type, then change to the custom domain on standard login page.

## View Orgs

### Grid View

-   All organizations are grouped by organization name.
-   Drag & Drop to sort groups.

### List View

-   All organizations are list as cards
-   Drag & Drop org photo to sort org cards

# Org Actions

![Untitled](Organizations%204350afbe73f040d2b25531020b983cee/Untitled%207.png)

### Open In Browser

Login your salesforce organization in browser by one click. No password needed any more!

### Copy Login Link

Get a login link and paste the link in the browser, then your salesforce org can be accessed as you without password login.

_Notes: please only share this link with someone you trust since it’s logged as your account!_

### Copy AccessToken

AccessToken can be used in all salesforce apis, like rest/metadata/tooling. When you build salesforce integration, you can easily copy access token here and test your apis.

_Notes: please only share AccessToken with someone you trust since it’s logged as your account!_

### Reset Password

Instead of sending new password email, you can set a new password for a particular user directly by following the password policy of your company.

-   You can also generate a random password directly, which is a mixture of letters, numbers and some special characters like @,#,$,\*, etc.

### Secret Notes

As you can login salesforce org from Metaforce by just one click , you might forget salesforce passwords since they might not be used for a long time!

You can put password/security token as secret notes in Metaforce and never lost those key information.

Of course, you can also set a new password directly if you forget the password.

![Untitled](Organizations%204350afbe73f040d2b25531020b983cee/Untitled%208.png)

![Untitled](Organizations%204350afbe73f040d2b25531020b983cee/Untitled%209.png)

### Re-Authorize

The org connection can be disconnected somehow, like sandbox refresh, user deactivation, etc. You can re-authorize the org and it will be connected again.

### Secret Notes

Put your important/secret stuff here so that you can find them someday in future, like your password, or security toke

### Revoke Connection

Your org connections are stored securely on your local computer. But you can revoke your org connection in Metaforce if you have to.

---

**Did we miss something?**
No worries! **[Submit A Case](https://metaforce.ltd/)** to us or send us a note at [**metaforce.salesforce@gmail.com**](mailto:metaforce.salesforce@gmail.com)!✌️
