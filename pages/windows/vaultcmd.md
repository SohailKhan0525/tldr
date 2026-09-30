# vaultcmd

> Creates, displays, and deletes stored credentials in Windows Credential Manager.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/vaultcmd>.

- List all credential vaults:

`vaultcmd /list`

- List the schemas for all credential vaults:

`vaultcmd /listschema`

- List all credentials stored in the Windows Credentials vault:

`vaultcmd /listcreds:"Windows Credentials" /all`

- List all credentials stored in the Web Credentials vault:

`vaultcmd /listcreds:"Web Credentials" /all`

- List the properties of a credential vault:

`vaultcmd /listproperties:"{{vault_name_or_guid}}"`

- Display help for a specific command:

`vaultcmd /listcreds /?`
