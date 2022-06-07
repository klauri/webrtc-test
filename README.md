# WebRTC Full Stack Server/Client

## For LAN Access
Requires SSL certificate and key file to access on HTTPS

## Start only for localhost
`python server.py`

## Start server with SSL on HTTPS
`python server.py --cert-file .\keys\domain.crt --key-file .\keys\domain.key`
Browse to https://localhost:8080

### Help
Run `python server.py -h` for argument help