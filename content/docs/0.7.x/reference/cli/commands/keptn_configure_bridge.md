---
date: "2020-09-02T17:04:24+02:00"
title: "keptn configure bridge"
slug: keptn_configure_bridge
---
## keptn configure bridge

Configures the credentials for the Keptn Bridge

### Synopsis

Configures the credentials for the Keptn Bridge.

```
keptn configure bridge --user=<user> --password=<password> [flags]
```

### Examples

```
keptn configure bridge --user=<user> --password=<password>
```

### Options

```
  -h, --help              help for bridge
  -o, --output            Print the current credentials
  -p, --password string   The password to login to the bridge
  -u, --user string       The user name to login to the bridge
```

### Options inherited from parent commands

```
      --mock                 Disables communication to a Keptn endpoint
  -q, --quiet                Suppresses debug and info messages
      --suppress-websocket   Disables WebSocket communication to suppress info messages from services running inside Keptn
  -v, --verbose              Enables verbose logging to print debug messages
```

### SEE ALSO

* [keptn configure](../keptn_configure/)	 - Configures one of the specified parts of Keptn

###### Auto generated by spf13/cobra on 2-Sep-2020
