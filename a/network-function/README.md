# a/network-function

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] a/network-function`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree a/network-function`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init a/network-function
kpt live apply a/network-function --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
