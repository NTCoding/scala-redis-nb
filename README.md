This is a temporary fork that adds reconnection support to the v3.0. The reason for this is that v3.0 uses Akka 2.2.x which is compatible with play framework 2.2.

The latest release of scala-redis-nb is tied to Akka 2.3.0 which is not compatible with the play framework - thus there is no way to have the reconnect feature when using play... unless you use this fork
