<p>
  <img align="left" src="resource/readme/logo.png">
</p>

# Template7-Introduction

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

Overall introduction of the project Temaplate7.

<br/>
<br/>

The project Template7 is a template of the microservice software product, including dockerize and deployment.

CI flow uses GitHub actions, once the condition is matched, the CI flow will be triggered, it builds the docker image from the source code and then pushes it to the [dockerhub](https://hub.docker.com/).

Use [Helm](https://helm.sh/) as a deployment tool.

## Overall Design

![](./resource/readme/Overall.png)

| Component | Description |
| :---: | :--- |
| [Backend](https://github.com/Template7/backend) | Core backend service. |
| [Cli-Tool](https://github.com/Template7/cli-tool) | Customized CLI tool for the project, such like DB indexes / data initialize. |
| [Common](https://github.com/Template7/common) | Common lib of the project. |
| [Deployment](https://github.com/Template7/deployment) | Project deployment manifest. |
