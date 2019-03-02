# MoreHomes
* Allows players to have multiple beds
* You can set the delay of teleportation
* Manage max amount of homes by creating permissions

## Instalation
Download the latest plugin release from [here](https://github.com/RestoreMonarchy/MoreHomes/releases/)  
**Libraries:** 0Harmony, uDB and LiteDB  
*Special thanks to [Void](https://steamcommunity.com/profiles/76561194107500974) for uDB!*

## Commands
**/home** - Teleports you to your first bed  
**/home [name]** - Teleports you to the selected be  
**/homes** - Prints all your beds to the chat  
**/renamehome [oldName] [newName]** - Renames your bed

## Default Configuration
```xml
<?xml version="1.0" encoding="utf-8"?>
<MoreHomesConfiguration xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <TeleportationDelay>5</TeleportationDelay>
  <DefaultHomes>2</DefaultHomes>
  <Permissions>
    <Permission>
      <MaxHomes>3</MaxHomes>
      <SPermission>home.vip</SPermission>
    </Permission>
    <Permission>
      <MaxHomes>5</MaxHomes>
      <SPermission>home.lord</SPermission>
    </Permission>
  </Permissions>
</MoreHomesConfiguration>
```

## Default Translation
```xml
<?xml version="1.0" encoding="utf-8"?>
<Translations xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <Translation Id="home_max_warn" Value="You can't have more beds!" />
  <Translation Id="command_homes" Value="Your beds:" />
  <Translation Id="command_home_not_found" Value="Can't find any bed called {0}." />
  <Translation Id="command_home_delay" Value="You will be teleported to your bed in {0} seconds!" />
  <Translation Id="command_rename_not_found" Value="Couldn't rename bed {0}, because it doesn't exits." />
  <Translation Id="command_rename_format" Value="Format: /renamehome [oldName] [newName]" />
  <Translation Id="command_rename_success" Value="Successfully renamed {0} to {1}!" />
</Translations>
```
## Support
If you need any help installing or setting up the plugin, be sure to join my Discord https://discord.gg/dCHkuxS
