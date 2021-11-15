# Nokia 2.2 TWRP Trees (Newest as of writing)

What has been fixed?

Branding

Incorrect Values

Roomservice errors

Nokia 2.2 TWRP Tree

Credits: Lopestom for the oukitel wp5 twrp tree i based this off

https://github.com/lopestom

***UNTESTED AS OF SPEAKING WILL BE TESTING WHEN IT BUILDS THIS WILL BE UIPDATED WHEN I HAVE TESTED IT***

**UPDATE: IT BUILDS**

**WHAT ISNT WORKING:
MTP**

This trees android version?

Android 9

What build?

1680 00WW

How to build?

First sync minimal omni manifests

```repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-9.0```

now sync

```repo sync```

Second clone this twrp tree

```git clone https://github.com/SmallPP420/FixedTree.git device/nokia/Wasp```

Now build

```export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch omni_Wasp-userdebug; mka recoveryimage```
