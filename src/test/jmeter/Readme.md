# This shows how to run in Maven

## Steps

### Install the plugin in your Maven repository or Nexus/Artifactory

```
mvn install:install-file -Dfile=/data/ubik/ulp/ulp-packages/video-streaming/ulp_video-streaming-plugin-6.3.2/lib/ext/ubik-jmeter-videostreaming-plugin-6.3.2.jar -DgroupId=com.ubikingenierie.ubikloadpack.streaming -DartifactId=ubik-jmeter-streaming-plugin -Dversion=6.3.2 -Dpackaging=jar

```

### Copy to src/test/jmeter

- saveservice.properties
- user.properties
- ulp_video_streaming_demo.jmx
- streams.csv
- ubik-streaming-plugin.license


### Run 

```
mvn clean verify
```