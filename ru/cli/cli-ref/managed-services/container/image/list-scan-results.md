---

__system: {"dislikeVariants":["Нет ответа на мой вопрос","Рекомендации не помогли","Содержание не соответствует заголовку","Другое"]}
---
# yc container image list-scan-results

[PREVIEW] List scan results of Docker image.

#### Command Usage

Syntax: 

`yc container image list-scan-results --image-id <IMAGE-ID>|--repository-id <REPOSITORY-ID>|--repository-name <REPOSITORY-NAME> [Flags...] [Global Flags...]`

#### Global Flags

| Flag | Description |
|----|----|
|`--image-id`|<b>`string`</b><br/>Image id.|
|`--repository-id`|<b>`string`</b><br/>Repository id.|
|`--repository-name`|<b>`string`</b><br/>Repository name.|
|`--limit`|<b>`int`</b><br/>The maximum number of items to list.|
|`--filter`|<b>`string`</b><br/>Filter by status.|

#### Flags

| Flag | Description |
|----|----|
|`--profile`|<b>`string`</b><br/>Set the custom configuration file.|
|`--debug`|Debug logging.|
|`--debug-grpc`|Debug gRPC logging. Very verbose, used for debugging connection problems.|
|`--no-user-output`|Disable printing user intended output to stderr.|
|`--retry`|<b>`int`</b><br/>Enable gRPC retries. By default, retries are enabled with maximum 5 attempts. Pass 0 to disable retries. Pass any negative value for infinite retries. Even infinite retries are capped with 2 minutes timeout.|
|`--cloud-id`|<b>`string`</b><br/>Set the ID of the cloud to use.|
|`--folder-id`|<b>`string`</b><br/>Set the ID of the folder to use.|
|`--folder-name`|<b>`string`</b><br/>Set the name of the folder to use (will be resolved to id).|
|`--token`|<b>`string`</b><br/>Set the OAuth token to use.|
|`--format`|<b>`string`</b><br/>Set the output format: text (default), yaml, json, json-rest.|
|`-h`,`--help`|Display help for the command.|