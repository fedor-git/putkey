# putkey
Shell script to put ssh key in remote server
# Setup in header
- set your ssh key name
- run: *putkey -a server_ip -p 22*
### Options
[-a ssh bind_address] // your server ip
[-p ssh port] // default 22
# Clone and install
```
cd /tmp && \
git clone https://github.com/fedorHub/putkey && \
cp /tmp/putkey/putkey /usr/local/bin/putkey && \
chmod +x /usr/local/bin/putkey && \
rm -rf /tmp/putkey/
```