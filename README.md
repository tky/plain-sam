1. Setup

First, copy the samconfig.sample.toml to samconfig.toml and configure settings you want,
and create a s3 bucket the name of which is you configured.

2. Build and deploy

```
$ pipenv install
$ pipenv shell
$ sam build
$ sam deploy
```

That's it. Only these command create the very simple rest api, so you can access the api you created.

3. Local development
sam sync --stack-name {YOUR_STACK_NAME} --watch --profile {YOUR_PROFILE}  --region {YOUR_REGION}
