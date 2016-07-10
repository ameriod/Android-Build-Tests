Build Tests
===========

This project shows how to dynamically change various values in the build.gradle and inside the res folders of
an Android application build the build process from outside of the build.gradle file. Also there is the auto
incrementing of the versionCode, versionNumber and each buildType also appends the current git sha at the end of the
buildSuffix.

This is done so that the addition of other flavors of the application can be done easily with a shared set of
vector assets, and different signing configs for each flavor.