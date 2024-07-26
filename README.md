# Self-hosting Ollama models on Fly.io

A simple repo for deploying Ollama on Fly.io.

## Usage

Create a new Fly App with:

```bash
$ fly launch --no-deploy --flycast
```

Then replace the generated `fly.toml` with the one from this repo (replace the app name to yours). 

The `--flycast` arg will make your new Ollama app inaccessible to the internet. To use this app from other Fly apps via your Fly private network (which you get by default), using the address `<your-app>.flycast`

Check out the accompanying video here: https://youtu.be/xkWcGmbhZRQ