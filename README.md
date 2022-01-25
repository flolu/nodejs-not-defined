## Setup

- `yarn install`

## Usage

- `yarn bazelisk build //...`

## Error

```
ERROR: /home/flo/Documents/nodejs-not-defined/app/BUILD.bazel:27:13: no such package '@nodejs//': The repository '@nodejs' could not be resolved: Repository '@nodejs' is not defined and referenced by '//app:base_image.2'
ERROR: Analysis of target '//app:base_image.2' failed; build aborted: Analysis failed
```
