## Contents

[Lifecycle](./10-lifecycle.md)
- [What is a job?](./10-lifecycle.md#what-is-a-job)
- [What is an event?](./10-lifecycle.md#what-is-an-event)
- [What is a watch?](./10-lifecycle.md#what-is-a-watch)
- [How do events trigger jobs?](./10-lifecycle.md#how-do-events-trigger-jobs)
- [How can jobs be ordered?](./10-lifecycle.md#how-can-jobs-be-ordered)

[Design: the Why of ContainerPilot](./20-design.md)
- [Why active service discovery?](./20-design.md#why-active-service-discovery)
- [Why are behaviors specified by application developer?](./20-design.md#why-are-behaviors-specified-by-application-developer)
- [Why are jobs not the same as services?](./20-design.md#why-are-jobs-not-the-same-as-services)
- [Why don't watches have behaviors?](./20-design.md#why-dont-watches-have-behaviors)
- [Why isn't there a "post-start" event?](./20-design.md#why-isnt-there-a-post-start-event)
- [Why should you not use ContainerPilot?](./20-design.md#why-should-you-not-use-containerpilot)

[Configuration](./30-configuration.md)
- [Installation](./30-configuration.md#installation)
- [Configuration syntax](./30-configuration.md#configuration-syntax)
- [Environment variable parsing and template rendering](./30-configuration.md#environment-variable-parsing-and-template-rendering)
- [Consul configuration](./30-configuration.md#consul-configuration)
  - [Client configuration](./30-configuration.md#client-configuration)
  - [Consul agent configuration](./30-configuration.md#consul-agent-configuration)
- [Job configuration](./30-configuration.md#job-configuration)
  - [Service discovery](./30-configuration.md#service-discovery)
  - [Health checks](./30-configuration.md#health-checks)
  - [Restart behavior](./30-configuration.md#restart-behavior)
  - [Pre-stop/post-stop behaviors](./30-configuration.md#pre-stop-post-stop-behaviors)
- [Watch configuration](./30-configuration.md#watch-configuration)
- [Telemetry configuration](./30-configuration.md#telemetry-configuration)
  - [Sensor configuration](./30-configuration.md#sensor-configuration)
- [Control plane](./30-configuration.md#control-plane)
  - [ContainerPilot subcommands](./30-configuration.md#containerpilot-subcommands)
- [Logging](./30-configuration.md#logging)

[Support](./40-support.md)
- [Where to file issues](./40-support.md#where-to-file-issues)
- [Contributing](./40-support.md#contributing)
- [Backwards compatibility](./40-support.md#backwards-compatibility)

## Where it's used

- [Applications on autopilot: a guide to how to build self-operating applications with ContainerPilot](https://www.joyent.com/blog/applications-on-autopilot)
- [MySQL (Percona Server) with auto scaling and fail-over](https://www.joyent.com/blog/dbaas-simplicity-no-lock-in)
- [Autopilot Pattern WordPress](https://www.joyent.com/blog/wordpress-on-autopilot)
- [ELK stack](https://www.joyent.com/blog/docker-log-drivers)
- [Node.js + Nginx + Couchbase](https://www.joyent.com/blog/docker-nodejs-nginx-nosql-autopilot)
- [CloudFlare DNS and CDN with dynamic origins](https://github.com/autopilotpattern/cloudflare)
- [Consul, running as an HA raft](https://github.com/autopilotpattern/consul)
- [Couchbase](https://github.com/autopilotpattern/couchbase)
- [Mesos on Joyent Triton](https://www.joyent.com/blog/mesos-by-the-pound)
- [Nginx with dynamic upstreams](https://www.joyent.com/blog/dynamic-nginx-upstreams-with-containerbuddy)