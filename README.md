# azure-iot-redis

In Azure IoT Edge speak, this is a solution that consists of a single module: the RedisEdge module.

The Redis module is a Docker image initialized from [docker-library/redis/5.0-rc/](https://github.com/docker-library/redis/tree/master/5.0-rc). It then needs a bit of NodeJS to support the hooks for the Azure IoT Edge runtime.
