# tacitknowledge/jmeter

Docker image with Jmeter and jpgc-json plugin

### Installation from [Docker registry hub](https://hub.docker.com/r/tacitknowledge/jmeter/).

You can download the image with the following command:

```bash
docker pull tacitknowledge/jmeter
```

Environment variables
----

This image uses environment variables to allow the configuration of some parameters at run time:

----

* Variable name: `RMI_PORT`
* Default value: 1099

----

* Variable name: `JAVA_MEM`
* Default value: 512m

----

Exposed ports
----

The image exposes `1099` port.
