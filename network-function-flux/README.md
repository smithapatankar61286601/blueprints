# network-function-flux

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] network-function-flux`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree network-function-flux`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init network-function-flux
kpt live apply network-function-flux --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
