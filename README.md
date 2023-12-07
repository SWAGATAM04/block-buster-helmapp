[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/block-buster-helmapp)](https://artifacthub.io/packages/search?repo=block-buster-helmapp)


# block-buster-helm-app

1. This repo contains an helm artefact which will be linked to a repo in ArtifactHub. 
2. This is used for FluxCD Demo.
3. Chart Name - `block-buster-helm-app`
4. URL - `https://swagatam04.github.io/block-buster-helmapp`
5. Container Image - `swagatam04/block-buster-dev:7.6.0`

### Sample values.yaml
```yaml
replicaCount: 1

service:
  type: NodePort
  nodePort: 30006

namespace:
  name: 5-demo
  
labels:
  app:
    name: block-buster
    version: 7.6.0
    env: dev
```
