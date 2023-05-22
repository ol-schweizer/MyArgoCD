# Manual for using the plugin kubeplugin

The plugin kubeplugin shows metrics of pods (CPU and Memory usage) in k8s cluster.

The syntax:

kubectl kubeplugin {{parameter 1}} {{parameter 2}}
where   {{parameter 1}} - namespace
        {{parameter 2}} - resource type


Example:
kubectl kubeplugin kube-system pod