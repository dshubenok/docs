---
sourcePath: ru/_cli-ref/cli-ref/managed-services/serverless/mdbproxy/update/clickhouse.md
---
# yc serverless mdbproxy update clickhouse

Update the specified proxy

#### Command Usage

Syntax: 

`yc serverless mdbproxy update clickhouse <PROXY-NAME>|<PROXY-ID> [Flags...] [Global Flags...]`

#### Global Flags

| Flag | Description |
|----|----|
|`--new-name`|<b>`string`</b><br/> New proxy name.|
|`--description`|<b>`string`</b><br/> Proxy description.|
|`--labels`|<b>`key=value[,key=value...]`</b><br/> A list of label KEY=VALUE pairs.|
|`--id`|<b>`string`</b><br/> Proxy id.|
|`--name`|<b>`string`</b><br/> Proxy name.|
|`--new-database`|<b>`string`</b><br/> Clickhouse database.|
|`--new-password`|<b>`string`</b><br/> Clickhouse password.|
|`--new-user`|<b>`string`</b><br/> Clickhouse user.|
|`--async`| Display information about the operation in progress, without waiting for the operation to complete.|

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
