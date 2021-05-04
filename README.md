
Trino
===========

Fast distributed SQL query engine for big data analytics


## Configuration

The following table lists the configurable parameters of the Trino chart and their default values.

| Parameter                | Description             | Default        |
| ------------------------ | ----------------------- | -------------- |
| `image.repository` |  | `"trinodb/trino"` |
| `image.pullPolicy` |  | `"IfNotPresent"` |
| `image.tag` |  | `"latest"` |
| `server.workers` |  | `2` |
| `server.node.environment` |  | `"production"` |
| `server.node.dataDir` |  | `"/data/trino"` |
| `server.node.pluginDir` |  | `"/usr/lib/trino/plugin"` |
| `server.log.trino.level` |  | `"INFO"` |
| `server.config.path` |  | `"/etc/trino"` |
| `server.config.http.port` |  | `8080` |
| `server.config.query.maxMemory` |  | `"4GB"` |
| `server.config.query.maxMemoryPerNode` |  | `"1GB"` |
| `server.config.query.maxTotalMemoryPerNode` |  | `"2GB"` |
| `server.config.memory.heapHeadroomPerNode` |  | `"1GB"` |
| `server.jvm.maxHeapSize` |  | `"8G"` |
| `server.jvm.gcMethod.type` |  | `"UseG1GC"` |
| `server.jvm.gcMethod.g1.heapRegionSize` |  | `"32M"` |
| `additionalNodeProperties` |  | `{}` |
| `additionalJVMConfig` |  | `{}` |
| `additionalConfigProperties` |  | `{}` |
| `additionalLogProperties` |  | `{}` |
| `additionalCatalogs` |  | `{}` |
| `securityContext.runAsUser` |  | `1000` |
| `securityContext.runAsGroup` |  | `1000` |
| `service.type` |  | `"ClusterIP"` |
| `service.port` |  | `8080` |
| `resources` |  | `{}` |
| `nodeSelector` |  | `{}` |
| `tolerations` |  | `[]` |
| `affinity` |  | `{}` |


---
_Documentation generated by [Frigate](https://frigate.readthedocs.io)._

