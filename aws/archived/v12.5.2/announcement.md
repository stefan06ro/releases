**Giant Swarm release v12.5.2 for AWS is available**. This release fixes an issue when handling cluster deletion. While improbable, if triggered, the issue causes app-operator to crash and stop reconciling app CRs in other clusters. As this is a patch update that doesn't roll nodes, we highly recommended upgrading to it. Further details can be found in the [release notes](https://github.com/giantswarm/releases/tree/master/aws/v12.5.2).