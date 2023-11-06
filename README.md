# build-fe

### Inputs

| Name  | Required | Details | Default value |
| :---: | :------: | :-----: | :-----------: |
| aws-access-key | yes | | |
| aws-secret-access-key | yes | | |
| aws-region | yes | | |
| aws-s3-name | yes | | |
| aws-cloudfront-name | yes | | |
| slack-channel | no | Send to enable Slack messages | `''` |
| slack-token | no | Send to enable Slack messages | `''` |
| build-command | no | [`yarn`, `npm`] | `yarn` |
| build-envs | no | Send only if environment variables need to be set for build step | |
| build-path | no | Send only if the build location is not in the default folder | `build` |
| node-version | no | Specify NodeJS version used for build step | 16.x |
| skip-build | no | Enable for deploy only | false |
