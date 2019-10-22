# GraphHopper library template

a minimal scratch project, that loads the latest grapphopper-tools
into a fresh android project and imports a present map.

## maps

currently a static map is being configured and needs to be manually build
and uploaded to `/mnt/sdcoard/0/Downloads/graphhopper/maps`

## GraphHopper libs

Clone the latest [https://github.com/graphhopper/graphhopper](graphhopper library project)
and build it with `mvn install`

The local 1.0-SNAPSHOT version of graphhopper-tools will be used by the gradle build.