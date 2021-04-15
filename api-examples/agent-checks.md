```
# curl http://10.250.85.12:8500/v1/agent/checks | python -m json.tool
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  6975    0  6975    0     0  1069k      0 --:--:-- --:--:-- --:--:-- 1135k
{
    "service:10.250.70.10-80": {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 0,
        "Definition": {},
        "ModifyIndex": 0,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "Timed out (30s) running check\n\n  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:01 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:02 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:03 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:04 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:05 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:06 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:07 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:08 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:09 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:10 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:11 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:12 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:13 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:14 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:15 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:16 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:17 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:18 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:19 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:20 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:21 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:22 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:23 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:24 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:25 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:26 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:27 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:28 --:--:--     0\r  0     0    0     0    0     0      0      0 --:--:--  0:00:29 --:--:--     0",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "critical",
        "Type": "script"
    },
    "service:10.250.70.15-80": {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 0,
        "Definition": {},
        "ModifyIndex": 0,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  26666      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    "service:10.250.70.17-80": {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 0,
        "Definition": {},
        "ModifyIndex": 0,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  33290      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    "service:10.250.70.24-80": {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 0,
        "Definition": {},
        "ModifyIndex": 0,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  31941      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    "service:10.250.70.5-80": {
        "CheckID": "service:10.250.70.5-80",
        "CreateIndex": 0,
        "Definition": {},
        "ModifyIndex": 0,
        "Name": "Service '10.250.70.5-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (7) Failed connect to 10.250.70.5:80; Connection refused\n",
        "ServiceID": "10.250.70.5-80",
        "ServiceName": "10.250.70.5-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "critical",
        "Type": "script"
    },
    "service:10.250.86.13-80": {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 0,
        "Definition": {},
        "ModifyIndex": 0,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  18426      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    "service:10.250.86.6-80": {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 0,
        "Definition": {},
        "ModifyIndex": 0,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  18624      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    }
}
```