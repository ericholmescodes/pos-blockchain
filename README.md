npm run dev

HTTP_PORT=3002 P2P_PORT=5002 PEERS=wc://localhost:5001 npm run dev

HTTP_PORT=3003 P2P_PORT=5003 PEERS=wc://localhost:5002 npm run dev

For first leader:
use bootstrap method with value in from field as BOOTSTRAP
create a global variable BOOTSTRAPED = false
check if BOOTSTRAP is done