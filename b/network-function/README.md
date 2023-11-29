# b/network-function

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] b/network-function`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree b/network-function`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init b/network-function
kpt live apply b/network-function --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
