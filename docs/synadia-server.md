# synadia-server

Run Synadia Server

**Synopsis**

Run Synadia Server. NATS is started with config file from `-c`. Set URL `-u` and Token `-t` to connect to Control Plane.

```
synadia-server [flags]
```

**Options**

```
  -c, --config string          NATS configuration file
      --disable-file-watcher   Disable File Watcher
  -h, --help                   help for synadia-server
      --opts-file string       YAML or JSON file containing CLI options
  -t, --token string           Control Plane Token
  -u, --url string             Control Plane URL
  -v, --version                version for synadia-server
```

## synadia-server signal

Send signal to synadia-server

**Synopsis**

Valid signals are: stop, quit, ldm, reopen, reload

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
  -c, --config string      NATS configuration file
      --opts-file string   YAML or JSON file containing CLI options
```

## synadia-server validate

Validate NATS Configuration

**Synopsis**

Checks that the NATS Configuration is well-formed and compatible with Control Plane.

```
synadia-server validate [flags]
```

**Options**

```
  -h, --help   help for validate
```

**Options inherited from parent commands**

```
  -c, --config string      NATS configuration file
      --opts-file string   YAML or JSON file containing CLI options
```

