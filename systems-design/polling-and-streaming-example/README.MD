Note that the commands below involve setting the environment variables in WINDOWS POWERSHELL.
Eg `$env:MY_VAR="8000" ; node index.js`

1. Run the server by running:
   `node .\server.js`

2. Create 2 clients by specifying the mode and username via environment variables:

- `$env:MODE="stream"; $env:NAME="Bob"; node client.js`
- `$env:MODE="stream"; $env:NAME="Alice"; node client.js`

3. Use the clients to send text messages to each other.
