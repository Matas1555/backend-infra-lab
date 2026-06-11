## Running the app
App runs by command `symfony server:start`

Usefull commands: `--port=****`, `--listen-ip:0.0.0.0`, `--allow-http`

The app runs on port 8000 by default.

Test:curl http://localhost:8000/health
Find listening port:  ss -tulpn | grep 8000
Find process using port:  lsof -i :8000
