# Contributing

We welcome and encourage contributions from the community.
Keep in mind that this spec describes the current production API so changes
must reflect actual behavior of the API.

### Tooling

The tooling chosen supports either authoring, validation, testing, or
publishing. Respective Make targest

- [Spectral](https://stoplight.io/open-source/spectral/): JSON/YAML linter with
  support for OpenAPI v3, custom rules, built-in functions, and custom functions
- [OpenAPI CLI](https://github.com/Redocly/openapi-cli): OpenAPI CLI toolbox
  with rich validation and bundling features.

In addition, the following tools are leveraged to facilitate authoring the spec.

#### Visual Studio Code Extensions

These are useful extensions when choosing to author OpenAPI spec using Visual
Studio Code.

- [Spectral](https://marketplace.visualstudio.com/items?itemName=stoplight.spectral):
  View linting violations inline
- [OpenAPI Preview](https://marketplace.visualstudio.com/items?itemName=zoellner.openapi-preview):
  Preview the API spec in SwaggerUI within the editor
