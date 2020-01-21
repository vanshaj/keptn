![keptn](./assets/keptn.png)

# Keptn
![GitHub release (latest by date)](https://img.shields.io/github/v/release/keptn/keptn)
![Github Downloads](https://img.shields.io/github/downloads/keptn/keptn/total?logo=github&logoColor=white)
[![Build Status](https://travis-ci.org/keptn/keptn.svg?branch=master)](https://travis-ci.org/keptn/keptn)

Keptn is an event-based control plane for continuous delivery and automated operations for cloud-native applications. 
Please find the documentation on our [website](https://keptn.sh), which provides also information on [Why Keptn?](https://keptn.sh/why-keptn/).

## Usage

Please find the documentation of how to get started with Keptn in the [Quick Start](https://keptn.sh/docs/quickstart/) and the [Installation instructions](https://keptn.sh/docs/0.6.0/installation/setup-keptn/). We recommend using the [latest stable release](https://github.com/keptn/keptn/releases).

Furthermore, you can learn about our current releases, release candidates and pre-releases on the [release section](https://github.com/keptn/keptn/releases).

## Versions compatibilities
We mangage the Keptn core components in versions. The respective images in their versions are stored on [DockerHub](https://hub.docker.com/?namespace=keptn).
The versions of the Keptn core components and the services have to be compatible to each other.
Therefore, this section shows the compatibility between these versions.

**Keptn in [version 0.6.0](https://github.com/keptn/keptn/releases/tag/0.6.0) requires:**

*Keptn core:*
- keptn/api:0.6.0
- keptn/bridge:0.6.0
- keptn/configuration-service:0.6.0
- keptn/distributor:0.6.0
- keptn/eventbroker-go:0.6.0
- keptn/gatekeeper-service:0.6.0
- keptn/helm-service:0.6.0
- keptn/jmeter-service:0.6.0
- keptn/lighthouse-service:0.6.0
- keptn/mongodb-datastore:0.6.0
- keptn/shipyard-service:0.6.0
- keptn/wait-service:0.6.0
- keptn/remediation-service:0.6.0

*for Openshift:*
- keptn/openshift-route-service:0.6.0

<details><summary>Keptn version 0.5.2</summary>
<p>
*Keptn core:*
- keptn/api:0.5.0
- keptn/bridge:0.5.0
- keptn/configuration-service:0.5.0
- keptn/distributor:0.5.0
- keptn/eventbroker-go:0.5.0
- keptn/gatekeeper-service:0.5.0
- keptn/helm-service:0.5.1
- keptn/jmeter-service:0.5.0
- keptn/mongodb-datastore:0.5.0
- keptn/pitometer-service:0.5.0
- keptn/shipyard-service:0.5.0
- keptn/wait-service:0.5.0
- keptn/remediation-service:0.5.0


*Keptn uniform:*
- keptn/dynatrace-service:0.2.0
- keptn/prometheus-service:0.2.0
- keptn/servicenow-service:0.1.4

*for Openshift:*
- keptn/openshift-route-service:0.5.0

</p>
</details>

<details><summary>Keptn version 0.5.1</summary>
<p>
*Keptn core:*
- keptn/api:0.5.0
- keptn/bridge:0.5.0
- keptn/configuration-service:0.5.0
- keptn/distributor:0.5.0
- keptn/eventbroker-go:0.5.0
- keptn/gatekeeper-service:0.5.0
- keptn/helm-service:0.5.1
- keptn/jmeter-service:0.5.0
- keptn/mongodb-datastore:0.5.0
- keptn/pitometer-service:0.5.0
- keptn/shipyard-service:0.5.0
- keptn/wait-service:0.5.0
- keptn/remediation-service:0.5.0


*Keptn uniform:*
- keptn/dynatrace-service:0.3.1
- keptn/prometheus-service:0.2.0
- keptn/servicenow-service:0.1.4

*for Openshift:*
- keptn/openshift-route-service:0.5.0

</p>
</details>
<details><summary>Keptn version 0.5.0</summary>
<p>

Keptn in [version 0.5.0](https://github.com/keptn/keptn/releases/tag/0.5.0) requires:

*Keptn core:*
- keptn/api:0.5.0
- keptn/bridge:0.5.0
- keptn/configuration-service:0.5.0
- keptn/distributor:0.5.0
- keptn/eventbroker-go:0.5.0
- keptn/gatekeeper-service:0.5.0
- keptn/helm-service:0.5.0
- keptn/jmeter-service:0.5.0
- keptn/mongodb-datastore:0.5.0
- keptn/pitometer-service:0.5.0
- keptn/shipyard-service:0.5.0
- keptn/wait-service:0.5.0
- keptn/remediation-service:0.5.0


*Keptn uniform:*
- keptn/dynatrace-service:0.3.1
- keptn/prometheus-service:0.2.0
- keptn/servicenow-service:0.1.4

*for Openshift:*
- keptn/openshift-route-service:0.5.0

</p>
</details>
<details><summary>Keptn version 0.4.0</summary>
<p>

Keptn in [version 0.4.0](https://github.com/keptn/keptn/releases/tag/0.4.0) requires:

*Keptn core:*
- keptn/authenticator:0.2.3
- keptn/bridge:0.1.3
- keptn/control:0.3.0
- keptn/eventbroker-go:0.1.0
- keptn/eventbroker-ext:0.3.0

*Keptn uniform:*
- keptn/gatekeeper-service:0.1.1
- keptn/github-service:0.3.0
- keptn/helm-service:0.1.1
- keptn/jmeter-service:0.1.1
- keptn/pitometer-service:0.2.0
- keptn/servicenow-service:0.1.3

*for Openshift:*
- keptn/openshift-route-service:0.1.1

</p>
</details>

<details><summary>Keptn version 0.3.0</summary>
<p>

Keptn in [version 0.3.0](https://github.com/keptn/keptn/releases/tag/0.3.0) requires:

*Keptn core:*
- keptn/authenticator:0.2.2
- keptn/bridge:0.1.2
- keptn/control:0.2.4
- keptn/eventbroker:0.2.3
- keptn/eventbroker-ext:0.2.3

*Keptn uniform:*
- keptn/gatekeeper-service:0.1.0
- keptn/github-service:0.2.2
- keptn/helm-service:0.1.0
- keptn/jmeter-service:0.1.0
- keptn/pitometer-service:0.1.3
- keptn/servicenow-service:0.1.2

*for Openshift:*
- keptn/openshift-route-service:0.1.0

</p>
</details>

<details><summary>Keptn version 0.2.2</summary>
<p>

Keptn in [version 0.2.2](https://github.com/keptn/keptn/releases/tag/0.2.2) requires:
- keptn/authenticator:0.2.2
- keptn/bridge:0.1.2
- keptn/control:0.2.3
- keptn/eventbroker:0.2.2
- keptn/eventbroker-ext:0.2.2
- keptn/pitometer-service:0.1.2
- keptn/servicenow-service:0.1.1
- keptn/github-service:0.2.1 
- keptn/jenkins-service:0.3.0
  - keptn/jenkins-0.6.0

</p>
</details>

<details><summary>Keptn version 0.2.1</summary>
<p>

Keptn in [version 0.2.1](https://github.com/keptn/keptn/releases/tag/0.2.1) requires:
- keptn/keptn-authenticator:0.2.1
- keptn/keptn-control:0.2.1
- keptn/keptn-event-broker:0.2.1
- keptn/keptn-event-broker-ext:0.2.1
- keptn/pitometer-service:0.1.1 
- keptn/servicenow-service:0.1.0
- keptn/github-service:0.1.1 
- keptn/jenkins-service:0.2.0
  - keptn/jenkins-0.5.0

</p>
</details>

<details><summary>Keptn version 0.2.0</summary>
<p>

Keptn in [version 0.2.0](https://github.com/keptn/keptn/releases/tag/0.2.0) requires:
- keptn/keptn-authenticator:0.2.0
- keptn/keptn-control:0.2.0
- keptn/keptn-event-broker:0.2.0
- keptn/keptn-event-broker-ext:0.2.0
- keptn/pitometer-service:0.1.0
- keptn/servicenow-service:0.1.0
- keptn/github-service:0.1.0
- keptn/jenkins-service:0.1.0
    - keptn/jenkins:0.4.0

</p>
</details>

<details><summary>Keptn version 0.1.3</summary>
<p>

Keptn in [version 0.1.3](https://github.com/keptn/keptn/tree/0.1.3) requires:

- keptn/jenkins:0.2
- dynatraceacm/ansibletower:3.3.1-1-2

</p>
</details>

## Contributions

You are welcome to contribute using Pull Requests to the respective repositories. Before contributing, please read our [Contributing Guidelines](CONTRIBUTING.md) and our [Code of Conduct](CODE_OF_CONDUCT.md).

## License

Keptn is an Open Source Project. Please see [LICENSE](LICENSE) for more information.

## Further information

* The [Keptn`s website](https://keptn.sh) has the documentation of Keptn and its use cases.
* Please join the [Keptn community](https://github.com/keptn/community).
