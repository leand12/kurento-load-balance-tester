# kurento-load-balance-tester
Automatic launcher of multiple JS Kurento Clients in Docker containers to test load balance for KMS


## Usage
- Make sure to be connected to the UA's VPN.
- Run `docker-compose up --scale test=3` to run 3 selenium test sessions on a JS client in Firefox.
- Navigate to `http://localhost:4444/` to check the selenium test sessions and interact with them.

LiveView (VNC) Password: `secret`
