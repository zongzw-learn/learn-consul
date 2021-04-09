```
# curl localhost:8500/v1/health/state/passing | python -m json.tool
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 29835    0 29835    0     0  1691k      0 --:--:-- --:--:-- --:--:-- 1713k
[
    {
        "CheckID": "serfHealth",
        "CreateIndex": 34344,
        "Definition": {},
        "ModifyIndex": 34344,
        "Name": "Serf Health Status",
        "Node": "consul-client-1.novalocal",
        "Notes": "",
        "Output": "Agent alive and reachable",
        "ServiceID": "",
        "ServiceName": "",
        "ServiceTags": [],
        "Status": "passing",
        "Type": ""
    },
    {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 34339,
        "Definition": {},
        "ModifyIndex": 35471,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-client-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  32298      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 34340,
        "Definition": {},
        "ModifyIndex": 35542,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-client-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  32663      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 34341,
        "Definition": {},
        "ModifyIndex": 35457,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-client-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  31553      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 34342,
        "Definition": {},
        "ModifyIndex": 35522,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-client-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  29646      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 34337,
        "Definition": {},
        "ModifyIndex": 35538,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-client-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  17869      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 34338,
        "Definition": {},
        "ModifyIndex": 35518,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-client-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  17968      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "serfHealth",
        "CreateIndex": 34361,
        "Definition": {},
        "ModifyIndex": 34361,
        "Name": "Serf Health Status",
        "Node": "consul-client-2.novalocal",
        "Notes": "",
        "Output": "Agent alive and reachable",
        "ServiceID": "",
        "ServiceName": "",
        "ServiceTags": [],
        "Status": "passing",
        "Type": ""
    },
    {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 34352,
        "Definition": {},
        "ModifyIndex": 35531,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-client-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  29885      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 34346,
        "Definition": {},
        "ModifyIndex": 35551,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-client-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0   3809      0 --:--:-- --:--:-- --:--:--  4333\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 34347,
        "Definition": {},
        "ModifyIndex": 35547,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-client-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  26130      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 34348,
        "Definition": {},
        "ModifyIndex": 35569,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-client-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30232      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 34350,
        "Definition": {},
        "ModifyIndex": 35526,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-client-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  16927      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 34351,
        "Definition": {},
        "ModifyIndex": 35501,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-client-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  19202      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "serfHealth",
        "CreateIndex": 34362,
        "Definition": {},
        "ModifyIndex": 34362,
        "Name": "Serf Health Status",
        "Node": "consul-client-3.novalocal",
        "Notes": "",
        "Output": "Agent alive and reachable",
        "ServiceID": "",
        "ServiceName": "",
        "ServiceTags": [],
        "Status": "passing",
        "Type": ""
    },
    {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 34359,
        "Definition": {},
        "ModifyIndex": 35565,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-client-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  28138      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 34360,
        "Definition": {},
        "ModifyIndex": 35535,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-client-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  33898      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 34354,
        "Definition": {},
        "ModifyIndex": 35567,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-client-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  31668      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 34355,
        "Definition": {},
        "ModifyIndex": 35477,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-client-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  31746      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 34357,
        "Definition": {},
        "ModifyIndex": 35485,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-client-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  21035      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 34358,
        "Definition": {},
        "ModifyIndex": 35523,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-client-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  17894      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "serfHealth",
        "CreateIndex": 34371,
        "Definition": {},
        "ModifyIndex": 34371,
        "Name": "Serf Health Status",
        "Node": "consul-client-4.novalocal",
        "Notes": "",
        "Output": "Agent alive and reachable",
        "ServiceID": "",
        "ServiceName": "",
        "ServiceTags": [],
        "Status": "passing",
        "Type": ""
    },
    {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 34369,
        "Definition": {},
        "ModifyIndex": 35560,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-client-4.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30624      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 34370,
        "Definition": {},
        "ModifyIndex": 35509,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-client-4.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  28824      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 34364,
        "Definition": {},
        "ModifyIndex": 35521,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-client-4.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30588      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 34365,
        "Definition": {},
        "ModifyIndex": 35544,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-client-4.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30552      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 34367,
        "Definition": {},
        "ModifyIndex": 35479,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-client-4.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0   4419      0 --:--:-- --:--:-- --:--:--  5200\nResponse from 10.250.70.17",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 34368,
        "Definition": {},
        "ModifyIndex": 35540,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-client-4.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  16828      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "serfHealth",
        "CreateIndex": 34308,
        "Definition": {},
        "ModifyIndex": 34308,
        "Name": "Serf Health Status",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "Agent alive and reachable",
        "ServiceID": "",
        "ServiceName": "",
        "ServiceTags": [],
        "Status": "passing",
        "Type": ""
    },
    {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 34329,
        "Definition": {},
        "ModifyIndex": 35495,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  31287      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 34330,
        "Definition": {},
        "ModifyIndex": 35497,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30842      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 34331,
        "Definition": {},
        "ModifyIndex": 35527,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  27083      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 34332,
        "Definition": {},
        "ModifyIndex": 35440,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  29246      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 34327,
        "Definition": {},
        "ModifyIndex": 35557,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0    827      0 --:--:-- --:--:-- --:--:--   838\nResponse from 10.250.70.15",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 34328,
        "Definition": {},
        "ModifyIndex": 35533,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-node-1.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  19607      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "serfHealth",
        "CreateIndex": 34305,
        "Definition": {},
        "ModifyIndex": 34305,
        "Name": "Serf Health Status",
        "Node": "consul-node-2.novalocal",
        "Notes": "",
        "Output": "Agent alive and reachable",
        "ServiceID": "",
        "ServiceName": "",
        "ServiceTags": [],
        "Status": "passing",
        "Type": ""
    },
    {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 34320,
        "Definition": {},
        "ModifyIndex": 35488,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-node-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30952      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 34321,
        "Definition": {},
        "ModifyIndex": 35444,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-node-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  33205      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 34322,
        "Definition": {},
        "ModifyIndex": 35461,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-node-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  33942      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 34324,
        "Definition": {},
        "ModifyIndex": 35559,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-node-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  31980      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 34318,
        "Definition": {},
        "ModifyIndex": 35514,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-node-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  17391      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 34319,
        "Definition": {},
        "ModifyIndex": 35520,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-node-2.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0   4842      0 --:--:-- --:--:-- --:--:--  5200\nResponse from 10.250.70.17",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "serfHealth",
        "CreateIndex": 19982,
        "Definition": {},
        "ModifyIndex": 19982,
        "Name": "Serf Health Status",
        "Node": "consul-node-3.novalocal",
        "Notes": "",
        "Output": "Agent alive and reachable",
        "ServiceID": "",
        "ServiceName": "",
        "ServiceTags": [],
        "Status": "passing",
        "Type": ""
    },
    {
        "CheckID": "service:10.250.70.10-80",
        "CreateIndex": 20017,
        "Definition": {},
        "ModifyIndex": 35545,
        "Name": "Service '10.250.70.10-80' check",
        "Node": "consul-node-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30127      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.10",
        "ServiceID": "10.250.70.10-80",
        "ServiceName": "10.250.70.10-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.15-80",
        "CreateIndex": 20018,
        "Definition": {},
        "ModifyIndex": 35496,
        "Name": "Service '10.250.70.15-80' check",
        "Node": "consul-node-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  29646      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.70.15-80",
        "ServiceName": "10.250.70.15-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.17-80",
        "CreateIndex": 20019,
        "Definition": {},
        "ModifyIndex": 35456,
        "Name": "Service '10.250.70.17-80' check",
        "Node": "consul-node-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  32869      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.17",
        "ServiceID": "10.250.70.17-80",
        "ServiceName": "10.250.70.17-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.70.24-80",
        "CreateIndex": 20013,
        "Definition": {},
        "ModifyIndex": 35571,
        "Name": "Service '10.250.70.24-80' check",
        "Node": "consul-node-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  30842      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.70.24-80",
        "ServiceName": "10.250.70.24-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.13-80",
        "CreateIndex": 20015,
        "Definition": {},
        "ModifyIndex": 35504,
        "Name": "Service '10.250.86.13-80' check",
        "Node": "consul-node-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  19534      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.24",
        "ServiceID": "10.250.86.13-80",
        "ServiceName": "10.250.86.13-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    },
    {
        "CheckID": "service:10.250.86.6-80",
        "CreateIndex": 20016,
        "Definition": {},
        "ModifyIndex": 35552,
        "Name": "Service '10.250.86.6-80' check",
        "Node": "consul-node-3.novalocal",
        "Notes": "",
        "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0\r100    26  100    26    0     0  14739      0 --:--:-- --:--:-- --:--:-- 26000\nResponse from 10.250.70.15",
        "ServiceID": "10.250.86.6-80",
        "ServiceName": "10.250.86.6-80",
        "ServiceTags": [
            "web-server"
        ],
        "Status": "passing",
        "Type": "script"
    }
]
```