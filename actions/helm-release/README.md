## Description

Release helm chart

## Inputs

| parameter | description | required | default |
| --- | --- | --- | --- |
| chart-path | set custom chart path | `false` | ./ |
| release-path | set RELEASE or SNAPSHOTS dir | `true` | snapshots |
| git-token | the git token used to operate on the git repository. If not specified it's loaded from the git credentials file | `true` |  |
| repo-url | the git token used to operate on the git repository. If not specified it's loaded from the git credentials file | `true` | cvacoop/alfresco_helm_charts |
| git-user | If you want to override the name of the author/committer of the tag | `false` | Actions Bot |
| git-email | If you want to override the email of the author/committer of the tag | `false` | no-reply@no-reply.users.github.com |


## Runs

This action is a `composite` action.


