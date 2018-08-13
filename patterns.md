## Secrets

|Name|Pattern|
|:---|:---|
|AWS_Credentials|\*\*/{.,\*}aws/credentials|
|SSH rsa / dsa|\*\*/id_{r,d}sa|
|SSH pem / key|\*\*/\*.{pem,key}|

## Mandatory Files

|Name|Pattern|
|:---|:---|
|gitignore|.gitignore|

## Project Dependencies

#### Python:

|Name|Pattern|
|:---|:---|
|wheels|\*\*/wheels/\*\*|
|var|\*\*/var/\*\*|
|sdist|\*\*/sdist/\*\*|
|lib|\*\*/lib\*[0-9]/\*\*|
|eggs|\*\*/{.,\*}eggs/\*\*|

#### Node.js

|Name|Pattern|
|:---|:---|
|node_modules|\*\*/node_modules/\*\*|
|jspm_packages|\*\*/jspm_packages/\*\*|

#### Ruby

|Name|Pattern|
|:---|:---|
|bundle|\*\*/.bundle/\*\*|
|vendor_bundle|\*\*/vendor/bundle/\*\*|

#### VisualStudio

|Name|Pattern|
|:---|:---|
|packages|\*\*/+(P\|p)ackages/!(build)/\*\*|

## Unwanted Files

|Name|Pattern|
|:---|:---|
|VSCode|\*\*/.vscode/\*|
|IntelliJ|\*\*/.idea/\*|
|pry history|\*\*/pry.history|
|bash history|\*\*/bash_history|
