---
title: "pgo create namespace"
---
## pgo create namespace

Create a namespace

### Synopsis

Create a namespace. For example:

	pgo create namespace somenamespace

	Note: For Kubernetes versions prior to 1.12, this command will not function properly
    - use $PGOROOT/deploy/add_targted_namespace.sh scriptor or give the user cluster-admin privileges.
    For more details, see the Namespace Creation section under Installing Operator Using Bash in the documentation.

```
pgo create namespace [flags]
```

### Options

```
  -h, --help   help for namespace
```

### Options inherited from parent commands

```
      --apiserver-url string     The URL for the PostgreSQL Operator apiserver that will process the request from the pgo client.
      --debug                    Enable additional output for debugging.
      --disable-tls              Disable TLS authentication to the Postgres Operator.
      --exclude-os-trust         Exclude CA certs from OS default trust store
  -n, --namespace string         The namespace to use for pgo requests.
      --pgo-ca-cert string       The CA Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-cert string   The Client Certificate file path for authenticating to the PostgreSQL Operator apiserver.
      --pgo-client-key string    The Client Key file path for authenticating to the PostgreSQL Operator apiserver.
```

### SEE ALSO

* [pgo create](/pgo-client/reference/pgo_create/)	 - Create a Postgres Operator resource

###### Auto generated by spf13/cobra on 1-Oct-2020