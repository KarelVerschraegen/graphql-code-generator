# @graphql-codegen/typescript-react-query

## 1.3.1

### Patch Changes

- Updated dependencies [dfd25caf]
- Updated dependencies [8da7dff6]
  - @graphql-codegen/visitor-plugin-common@1.21.0
  - @graphql-codegen/plugin-helpers@1.18.7

## 1.3.0

### Minor Changes

- 5c119438: Added an option exposeDocument to expose a document from the hook

### Patch Changes

- d9212aa0: fix(visitor-plugin-common): guard for a runtime type error
- Updated dependencies [d9212aa0]
- Updated dependencies [f0b5ea53]
- Updated dependencies [097bea2f]
  - @graphql-codegen/visitor-plugin-common@1.20.0
  - @graphql-codegen/plugin-helpers@1.18.5

## 1.2.4

### Patch Changes

- 23862e7e: fix(naming-convention): revert and pin change-case-all dependency for workaround #3256
- Updated dependencies [23862e7e]
  - @graphql-codegen/visitor-plugin-common@1.19.1
  - @graphql-codegen/plugin-helpers@1.18.4

## 1.2.3

### Patch Changes

- 29b75b1e: enhance(namingConvention): use change-case-all instead of individual packages for naming convention
- Updated dependencies [e947f8e3]
- Updated dependencies [29b75b1e]
- Updated dependencies [d4942d04]
- Updated dependencies [1f6f3db6]
- Updated dependencies [29b75b1e]
  - @graphql-codegen/visitor-plugin-common@1.19.0
  - @graphql-codegen/plugin-helpers@1.18.3

## 1.2.2

### Patch Changes

- e69869aa: enhance(react-query): Don't generate fetcher without operations (#5601)

## 1.2.1

### Patch Changes

- 70628c87: Add support for useTypeImports when using fetcher: graphql-request

## 1.2.0

### Minor Changes

- ed0ae4c7: Allow fetcher to receive variables lazily so it can use react hooks

### Patch Changes

- Updated dependencies [5749cb8a]
- Updated dependencies [5a12fe58]
  - @graphql-codegen/visitor-plugin-common@1.18.3

## 1.1.0

### Minor Changes

- e6efeadc: Allow to override TError type at the level of the config
- 3c30fbd4: Exposed query keys for each generated qurey hook

### Patch Changes

- Updated dependencies [63be0f40]
- Updated dependencies [190482a1]
- Updated dependencies [4444348d]
- Updated dependencies [142b32b3]
- Updated dependencies [42213fa0]
  - @graphql-codegen/visitor-plugin-common@1.18.1

## 1.0.0

### Major Changes

- b51712c3: - Upgraded react-query to v3
  - Modified generated useQuery hooks to allow passing in of data type to be used with query data selectors
  - Reworked the mutations so that variables are passed in at mutate time and not at instantiation

### Patch Changes

- cda6ded0: Make sure mutation variables are always optional
- d98f5079: Respect typesPrefix for generated types.

  Previously, the prefix was incorrectly applied to runtime hook names.

- Updated dependencies [64293437]
- Updated dependencies [fd5843a7]
- Updated dependencies [d75051f5]
  - @graphql-codegen/visitor-plugin-common@1.17.22

## 0.1.1

### Patch Changes

- 1183d173: Bump all packages to resolve issues with shared dependencies
- Updated dependencies [1183d173]
  - @graphql-codegen/visitor-plugin-common@1.17.20
  - @graphql-codegen/plugin-helpers@1.18.2

## 0.1.0

### Minor Changes

- c3b59e81: NEW PLUGIN!

### Patch Changes

- Updated dependencies [99819bf1]
- Updated dependencies [c3b59e81]
  - @graphql-codegen/visitor-plugin-common@1.17.19
