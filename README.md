# Homelab-AI
Docker compose for OpenWebUI with Ollama bundled in. Will still need to choose an AI model to run in Ollama. You can find model options at: https://ollama.com/search

The docker compose file also include setting for if you choose to run Ollama outside of this container and on bare metal.

## SearXNG
SearXNG is a locally hosted searched engine that we can utilize to enable local AI models to access the internet if they do not have tools already. We use SearXNG's ability to provide json files to enable this. Make sure to install both docker compose files. Separate the two compose files into their own directories.

# Summary
- Create OpenWebUI and SearXNG directories.
- Install each individual docker-compose files into their respective files.
- Copy and paste the MCP server file into OpenWebUI to enable web searches.
