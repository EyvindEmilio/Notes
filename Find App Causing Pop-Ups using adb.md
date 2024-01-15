## Find Apps Causing Pop-Ups using adb

- When the pop-up appears, run this command to get the current package running

`adb shell dumpsys window windows | grep -i "mCurrentFocus"`

- Then you can close the package with

`adb shell am force-stop`


*After find the app try to revoke the permissions or delete the app*
