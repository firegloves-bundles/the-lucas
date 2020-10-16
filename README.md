```
apiVersion: entando.org/v1
kind: EntandoDeBundle
metadata:
  name: the-lucas
  labels:
    plugin: 'true'
    widget: 'true'
spec:
  details:
    name: thelucas-bundle
    description: This is the theLucas bundle
    dist-tags:
      latest: no-widgets
    versions:
      - v0.0.1
      - v0.0.2
  tags:
    - version: v0.0.1
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
    - version: v0.0.2
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
```