## ADK05
MCP example

based on https://google.github.io/adk-docs/tools/mcp-tools/
## Set up virtual environment

```
rm -rf .venv
virtualenv -p python3.12 .venv
. .venv/bin/activate
pip install --upgrade pip

pip install -r requirements.txt
```

## Usage

Update .env file with your API key

Then run the server with:

```bash
python my_adk_mcp_server.py
```

Then run the app with:

```bash
adk run mcp_client_agent
```

You can also run the app with:

```bash
adk web
```

# Close with deactivation of venv

```
deactivate
```
