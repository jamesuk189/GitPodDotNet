# GitPodDotNet
A repository containing the confgiuration for gitpod.io to run .NET web apps with the port exposed

## Key files
| File | Description |
|------|----|
| .gitpod.yml | Contains definition of workspace image to work |
| .vscode/launch.json | Add `urls: http://0.0.0.0:5001` to `env` so Kestrel serves requests from GitPod exposed port |
