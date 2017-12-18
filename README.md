# Ext JS Repackaged for Use by Jangaroo (Maven)

License: [Apache 2.0](https://github.com/CoreMedia/jangaroo-tools/wiki/License)

Note: This license applies only to the code that repackages Ext JS, not the framework itself.
Regarding Ext JS, please refer to [Sencha's licensing page](https://www.sencha.com/legal/#Sencha_Ext_JS).

When using the Ext JS "binaries" in Jangaroo's build process, it should be available as a Maven artifact like everything else.
There are several branches in this repository for the different Ext JS versions.
Unfortunately, we may only publish the GPL version of Ext JS to Maven Central, so the branch [ext-js-6.2-gpl](https://github.com/CoreMedia/ext-js/tree/ext-js-6.2-gpl)
is probably the most interesting one.

For commercial versions, please contact your OEM vendor (most likely CoreMedia) or use the POM from the corresponding branch
in this repository to build and privately deploy the desired Ext JS version's Maven artifact.

For examples of how to use the published GPL Ext JS Maven artifact, see [Jangaroo Ext AS Examples](https://github.com/CoreMedia/jangaroo-ext-as-examples).
