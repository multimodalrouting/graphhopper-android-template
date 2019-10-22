# GraphHopper library template

a minimal scratch project, that loads the latest graphhopper-tools
into a fresh android project and imports a present map.

## maps

currently a static map is being configured and needs to be manually build
and uploaded to `/mnt/sdcoard/0/Download/graphhopper/maps`

## GraphHopper libs

Clone the latest [graphhopper library project](https://github.com/graphhopper/graphhopper)
and build it with `mvn install`

The local 1.0-SNAPSHOT version of graphhopper-tools will be used by the gradle build.