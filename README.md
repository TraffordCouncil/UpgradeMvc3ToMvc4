UpgradeMvc3ToMvc4
=================

Package for auto upgrade MVC 3 Application to MVC 4 Application.

Once your project has been updated, there is no need to depend on this package,
so you can delete the following line from your packages.config file:

```xml
<package id="UpgradeMvc3ToMvc4" ... />
```

Ensure you also upgrade any related or dependent projects to MVC4.

Visit https://github.com/TraffordCouncil/UpgradeMvc3ToMvc4 for more information

More information about upgrading from MVC3 to MVC4 can be found at 
https://docs.microsoft.com/en-us/aspnet/whitepapers/mvc4-release-notes#_Toc303253806

## Changes in this release ##

- Removed (unnecessary) OAuth package dependency
- Removed need for explicit package dependency versions
(especially helpful if a newer dependency already exists in the project)