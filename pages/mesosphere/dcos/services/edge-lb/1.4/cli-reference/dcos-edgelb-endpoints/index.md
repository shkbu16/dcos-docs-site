---
layout: layout.pug
navigationTitle:  dcos edgelb endpoints
title: dcos edgelb endpoints
menuWeight: 15
excerpt: List all endpoints for a pool
enterprise: true
---

# Description
The `dcos edgelb endpoints` command returns a list of all endpoints for a pool. The internal IP address and ports for a pool can be found with this command.

# Usage

```bash
dcos edgelb endpoints <pool-name> [options]
```

# Options

| Name, shorthand | Description |
|-----------------|-------------|
| `--help, -h`   | Display usage information. |
| `--verbose, -v`   | Enable additional logging of requests and responses. |
| `--name="<name>"`   | Specify the name of the service instance to query. |
| `--json` | Show unparsed JSON response. |

# Parent command

| Command | Description |
|---------|-------------|
| [dcos edgelb](../../cli-reference/) |  Manage Edge-LB. |

# Examples

See the [Edge-LB Usage](../../usage/).