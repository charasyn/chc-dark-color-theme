# Instructions for publishing:
To generate PAT: (probably will need to do this)
1. Go to https://dev.azure.com
1. Select the publishing account
1. Go to the "person with a gear" icon in the top-right -> Personal Access Tokens
1. Create token
1. !!! Select Organization -> All Accessible Organizations !!!
1. Scopes: Select "Custom defined" and hit "Show more scopes"
1. Under Marketplace, check Acquire and Manage
1. Generate
1. ```vsce login <publisher name>```

To publish:
1. vsce publish
