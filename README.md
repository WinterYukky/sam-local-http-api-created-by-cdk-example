# CDK SAM Local example

This is example of SAM Local emulate the HTTP API that created by CDK.

## Open project

This project has `.devcontainer` so you can open in Remote Container of VSCode.

## Local emulate HTTP API

Synth template.

```bash
cdk synth --no-staging > template.yml
```

Start emulate.

```bash
sam local start-api
```

Access the http://localhost:3000/hello .  
You can get the result like this JSON body.

```json
{ "message": "Hello from Lambda!" }
```
