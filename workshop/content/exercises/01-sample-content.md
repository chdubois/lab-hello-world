This is an example page for exercises to be done for the workshop. You would remove this page, replace it with your own and then adjust the `workshop.yaml` and `modules.yaml` file to list your pages instead.

In this example the pages which make up the core of the workshop content are placed in a sub directory. This is only done as a suggestion. You can place all pages at the same directory level if you wish.

Included below are some tests and examples of page formatting using Markdown.

#### Standard code block

```
echo "standard code block"
```

#### Click text to Hello world

```execute
echo "Hello world in terminal 1"
```

#### Click text to Hello world (with target)

```execute-1
echo "Hello world in terminal 1"
```

```execute-2
echo "Hello world in terminal 2"
```

```execute-all
echo "Hello world in all terminals"
```

#### Click text to copy

```copy
echo "copy text to buffer"
```

#### Click text to copy (and edit)

```copy-and-edit
echo "copy text to buffer"
```

#### Interrupt command

```execute
sleep 3600
```

```execute
<ctrl-c>
```

#### Variable interpolation

workshop_name: {{ workshop_name }}

session_namespace: {{ session_namespace }}

workshop_namespace: {{ workshop_namespace }}

training_portal: {{ training_portal }}

ingress_domain: {{ ingress_domain }}

ingress_protocol: {{ ingress_protocol }}

#### Web site links

[Manage Clusters](https://tanzuemea.tmc.cloud.vmware.com/clusters)
