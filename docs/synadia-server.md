# synadia-server

Run Synadia Server

**Synopsis**

Run Synadia Server. NATS is started with config file from `-c`. Set URL `-u` and Token `-t` to connect to Control Plane.

```
synadia-server [flags]
```

**Options**

```
  -c, --config string           NATS configuration file
  -h, --help                    help for synadia-server
      --synadia-config string   YAML or JSON config file containing CLI arguments.
  -t, --token string            Control Plane Token
  -u, --url string              Control Plane URL
  -v, --version                 version for synadia-server
```

## synadia-server signal

Send signal to synadia-server process (stop, quit, ldm, reopen, reload)

```
synadia-server signal [flags]
```

**Options**

```
  -h, --help         help for signal
  -P, --pid string   PID or PID File
```

**Options inherited from parent commands**

```
  -c, --config string           NATS configuration file
      --synadia-config string   YAML or JSON config file containing CLI arguments.
```

## synadia-server validate

Validate Configuration

```
synadia-server validate [flags]
```

**Options**

```
  -h, --help   help for validate
```

**Options inherited from parent commands**

```
  -c, --config string           NATS configuration file
      --synadia-config string   YAML or JSON config file containing CLI arguments.
```

