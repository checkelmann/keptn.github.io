---
date: "2021-03-25T15:47:41+01:00"
title: "keptn get event evaluation.finished"
slug: keptn_get_event_evaluation.finished
---
## keptn get event evaluation.finished

Returns the latest Keptn sh.keptn.event.evaluation.finished event from a specific Keptn context

### Synopsis

Returns the latest Keptn sh.keptn.event.evaluation.finished event from a specific Keptn context.

```
keptn get event evaluation.finished [flags]
```

### Examples

```
keptn get event evaluation.finished --keptn-context=1234-5678-90ab-cdef
```

### Options

```
      --keptn-context string   The ID of a Keptn context from which to retrieve an evaluation.finished event
```

### Options inherited from parent commands

```
  -h, --help               help
      --mock               Disables communication to a Keptn endpoint
  -n, --namespace string   Specify the namespace where Keptn should be installed, used and uninstalled in (default "keptn")
  -q, --quiet              Suppresses debug and info messages
  -v, --verbose            Enables verbose logging to print debug messages
  -y, --yes                Assume yes for all user prompts
```

### SEE ALSO

* [keptn get event](../keptn_get_event/)	 - Returns the latest Keptn event specified by event type

###### Auto generated by spf13/cobra on 25-Mar-2021
