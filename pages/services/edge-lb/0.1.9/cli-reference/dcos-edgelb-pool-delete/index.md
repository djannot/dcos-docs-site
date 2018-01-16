---
layout: layout.pug
navigationTitle:  dcos edgelb pool delete
title: dcos edgelb pool delete
menuWeight: 60
excerpt:

enterprise: false
---

# Description
Delete and uninstall an Edge-LB pool.

# Usage

```bash
dcos edgelb [<flags>] pool delete <name>
```

# Positional arguments

| Name, shorthand | Description |
|---------|-------------|
| `<name>`   | Pool name. |


# Options

| Name, shorthand | Description |
|---------|-------------|
| `--help, h`   | Print usage. |
| `--verbose`   | Enable additional logging of requests and responses. |
| `--force-insecure`   | Allow unverified TLS certificates when querying service. |
| `--custom-auth-token=DCOS_AUTH_TOKEN`   | Specify a custom auth token to use when querying a service. |
| `--custom-dcos-url=DCOS_URI/DCOS_URL`   | Specify a custom cluster URL to use when querying a service. |
| `--custom-cert-path=DCOS_CA_PATH/DCOS_CERT_PATH`   | Specify a custom TLS CA certificate file to use when querying a service. |
| `--name="<name>"`   | Name of the service instance to query. |

# Parent command

| Command | Description |
|---------|-------------|
| [dcos edgelb](/service-docs/edge-lb/0.1.9/cli-reference)  |  Manage Edge-LB. |

# Examples

See the [Edge-LB Usage](/service-docs/edge-lb/0.1.9/usage).