Auto upgrade MVC 3 Application to MVC 4 Application
===================================================

Assuming no NuGet errors occured, your project should now be upgraded to MVC4.

If you have re-applied this package to an existing MVC4 project then be aware
of any breaking changes that may have been made, most notably your RegisterBundles.cs.
Check all changes made in your source control!

Ensure you also upgrade any related or dependent projects to MVC4.

-------------------------------------------------------------------------------

Once your project has been updated, there is no need to depend on this package,
so you can delete the following line from your packages.config file:

<package id="UpgradeMvc3ToMvc4" ... />

-------------------------------------------------------------------------------

Visit https://github.com/TraffordCouncil/UpgradeMvc3ToMvc4 for more information