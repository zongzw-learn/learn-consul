```
$ curl 10.250.85.12:8500/v1/health/service/10.250.70.5-80 | python -m json.tool
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 10444    0 10444    0     0   285k      0 --:--:-- --:--:-- --:--:--  291k
[
    {
        "Checks": [
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
                "CheckID": "service:10.250.70.5-80",
                "CreateIndex": 34343,
                "Definition": {},
                "ModifyIndex": 34592,
                "Name": "Service '10.250.70.5-80' check",
                "Node": "consul-client-1.novalocal",
                "Notes": "",
                "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (7) Failed connect to 10.250.70.5:80; Connection refused\n",
                "ServiceID": "10.250.70.5-80",
                "ServiceName": "10.250.70.5-80",
                "ServiceTags": [
                    "web-server"
                ],
                "Status": "critical",
                "Type": "script"
            }
        ],
        "Node": {
            "Address": "10.250.87.4",
            "CreateIndex": 34336,
            "Datacenter": "dc1",
            "ID": "29657eb1-5209-4dd8-ab04-7e19592e3e6d",
            "Meta": {
                "consul-network-segment": ""
            },
            "ModifyIndex": 34336,
            "Node": "consul-client-1.novalocal",
            "TaggedAddresses": {
                "lan": "10.250.87.4",
                "lan_ipv4": "10.250.87.4",
                "wan": "10.250.87.4",
                "wan_ipv4": "10.250.87.4"
            }
        },
        "Service": {
            "Address": "",
            "Connect": {},
            "CreateIndex": 34343,
            "EnableTagOverride": false,
            "ID": "10.250.70.5-80",
            "Meta": null,
            "ModifyIndex": 34343,
            "Port": 80,
            "Proxy": {
                "Expose": {},
                "MeshGateway": {}
            },
            "Service": "10.250.70.5-80",
            "Tags": [
                "web-server"
            ],
            "Weights": {
                "Passing": 1,
                "Warning": 1
            }
        }
    },
    {
        "Checks": [
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
                "CheckID": "service:10.250.70.5-80",
                "CreateIndex": 34349,
                "Definition": {},
                "ModifyIndex": 34593,
                "Name": "Service '10.250.70.5-80' check",
                "Node": "consul-client-2.novalocal",
                "Notes": "",
                "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (7) Failed connect to 10.250.70.5:80; Connection refused\n",
                "ServiceID": "10.250.70.5-80",
                "ServiceName": "10.250.70.5-80",
                "ServiceTags": [
                    "web-server"
                ],
                "Status": "critical",
                "Type": "script"
            }
        ],
        "Node": {
            "Address": "10.250.87.7",
            "CreateIndex": 34345,
            "Datacenter": "dc1",
            "ID": "f46c4076-a490-45f8-e383-aa15f4cc7968",
            "Meta": {
                "consul-network-segment": ""
            },
            "ModifyIndex": 34345,
            "Node": "consul-client-2.novalocal",
            "TaggedAddresses": {
                "lan": "10.250.87.7",
                "lan_ipv4": "10.250.87.7",
                "wan": "10.250.87.7",
                "wan_ipv4": "10.250.87.7"
            }
        },
        "Service": {
            "Address": "",
            "Connect": {},
            "CreateIndex": 34349,
            "EnableTagOverride": false,
            "ID": "10.250.70.5-80",
            "Meta": null,
            "ModifyIndex": 34349,
            "Port": 80,
            "Proxy": {
                "Expose": {},
                "MeshGateway": {}
            },
            "Service": "10.250.70.5-80",
            "Tags": [
                "web-server"
            ],
            "Weights": {
                "Passing": 1,
                "Warning": 1
            }
        }
    },
    {
        "Checks": [
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
                "CheckID": "service:10.250.70.5-80",
                "CreateIndex": 34356,
                "Definition": {},
                "ModifyIndex": 34526,
                "Name": "Service '10.250.70.5-80' check",
                "Node": "consul-client-3.novalocal",
                "Notes": "",
                "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (7) Failed connect to 10.250.70.5:80; Connection refused\n",
                "ServiceID": "10.250.70.5-80",
                "ServiceName": "10.250.70.5-80",
                "ServiceTags": [
                    "web-server"
                ],
                "Status": "critical",
                "Type": "script"
            }
        ],
        "Node": {
            "Address": "10.250.87.6",
            "CreateIndex": 34353,
            "Datacenter": "dc1",
            "ID": "94eaa034-130d-d665-d711-5230bf51eb64",
            "Meta": {
                "consul-network-segment": ""
            },
            "ModifyIndex": 34353,
            "Node": "consul-client-3.novalocal",
            "TaggedAddresses": {
                "lan": "10.250.87.6",
                "lan_ipv4": "10.250.87.6",
                "wan": "10.250.87.6",
                "wan_ipv4": "10.250.87.6"
            }
        },
        "Service": {
            "Address": "",
            "Connect": {},
            "CreateIndex": 34356,
            "EnableTagOverride": false,
            "ID": "10.250.70.5-80",
            "Meta": null,
            "ModifyIndex": 34356,
            "Port": 80,
            "Proxy": {
                "Expose": {},
                "MeshGateway": {}
            },
            "Service": "10.250.70.5-80",
            "Tags": [
                "web-server"
            ],
            "Weights": {
                "Passing": 1,
                "Warning": 1
            }
        }
    },
    {
        "Checks": [
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
                "CheckID": "service:10.250.70.5-80",
                "CreateIndex": 34366,
                "Definition": {},
                "ModifyIndex": 34521,
                "Name": "Service '10.250.70.5-80' check",
                "Node": "consul-client-4.novalocal",
                "Notes": "",
                "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (7) Failed connect to 10.250.70.5:80; Connection refused\n",
                "ServiceID": "10.250.70.5-80",
                "ServiceName": "10.250.70.5-80",
                "ServiceTags": [
                    "web-server"
                ],
                "Status": "critical",
                "Type": "script"
            }
        ],
        "Node": {
            "Address": "10.250.87.5",
            "CreateIndex": 34363,
            "Datacenter": "dc1",
            "ID": "75d32aba-cc1f-7c72-0269-8295019186fe",
            "Meta": {
                "consul-network-segment": ""
            },
            "ModifyIndex": 34363,
            "Node": "consul-client-4.novalocal",
            "TaggedAddresses": {
                "lan": "10.250.87.5",
                "lan_ipv4": "10.250.87.5",
                "wan": "10.250.87.5",
                "wan_ipv4": "10.250.87.5"
            }
        },
        "Service": {
            "Address": "",
            "Connect": {},
            "CreateIndex": 34366,
            "EnableTagOverride": false,
            "ID": "10.250.70.5-80",
            "Meta": null,
            "ModifyIndex": 34366,
            "Port": 80,
            "Proxy": {
                "Expose": {},
                "MeshGateway": {}
            },
            "Service": "10.250.70.5-80",
            "Tags": [
                "web-server"
            ],
            "Weights": {
                "Passing": 1,
                "Warning": 1
            }
        }
    },
    {
        "Checks": [
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
                "CheckID": "service:10.250.70.5-80",
                "CreateIndex": 34325,
                "Definition": {},
                "ModifyIndex": 34325,
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
            }
        ],
        "Node": {
            "Address": "10.250.85.12",
            "CreateIndex": 34308,
            "Datacenter": "dc1",
            "ID": "d5c87caa-7751-6250-47e4-5263889add56",
            "Meta": {
                "consul-network-segment": ""
            },
            "ModifyIndex": 34323,
            "Node": "consul-node-1.novalocal",
            "TaggedAddresses": {
                "lan": "10.250.85.12",
                "lan_ipv4": "10.250.85.12",
                "wan": "10.250.85.12",
                "wan_ipv4": "10.250.85.12"
            }
        },
        "Service": {
            "Address": "",
            "Connect": {},
            "CreateIndex": 34325,
            "EnableTagOverride": false,
            "ID": "10.250.70.5-80",
            "Meta": null,
            "ModifyIndex": 34325,
            "Port": 80,
            "Proxy": {
                "Expose": {},
                "MeshGateway": {}
            },
            "Service": "10.250.70.5-80",
            "Tags": [
                "web-server"
            ],
            "Weights": {
                "Passing": 1,
                "Warning": 1
            }
        }
    },
    {
        "Checks": [
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
                "CheckID": "service:10.250.70.5-80",
                "CreateIndex": 34333,
                "Definition": {},
                "ModifyIndex": 34333,
                "Name": "Service '10.250.70.5-80' check",
                "Node": "consul-node-2.novalocal",
                "Notes": "",
                "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (7) Failed connect to 10.250.70.5:80; Connection refused\n",
                "ServiceID": "10.250.70.5-80",
                "ServiceName": "10.250.70.5-80",
                "ServiceTags": [
                    "web-server"
                ],
                "Status": "critical",
                "Type": "script"
            }
        ],
        "Node": {
            "Address": "10.250.85.26",
            "CreateIndex": 34305,
            "Datacenter": "dc1",
            "ID": "d63c76f0-50da-d416-17d6-958aef73b7a1",
            "Meta": {
                "consul-network-segment": ""
            },
            "ModifyIndex": 34317,
            "Node": "consul-node-2.novalocal",
            "TaggedAddresses": {
                "lan": "10.250.85.26",
                "lan_ipv4": "10.250.85.26",
                "wan": "10.250.85.26",
                "wan_ipv4": "10.250.85.26"
            }
        },
        "Service": {
            "Address": "",
            "Connect": {},
            "CreateIndex": 34326,
            "EnableTagOverride": false,
            "ID": "10.250.70.5-80",
            "Meta": null,
            "ModifyIndex": 34326,
            "Port": 80,
            "Proxy": {
                "Expose": {},
                "MeshGateway": {}
            },
            "Service": "10.250.70.5-80",
            "Tags": [
                "web-server"
            ],
            "Weights": {
                "Passing": 1,
                "Warning": 1
            }
        }
    },
    {
        "Checks": [
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
                "CheckID": "service:10.250.70.5-80",
                "CreateIndex": 20014,
                "Definition": {},
                "ModifyIndex": 34504,
                "Name": "Service '10.250.70.5-80' check",
                "Node": "consul-node-3.novalocal",
                "Notes": "",
                "Output": "  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current\n                                 Dload  Upload   Total   Spent    Left  Speed\n\r  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0curl: (7) Failed connect to 10.250.70.5:80; Connection refused\n",
                "ServiceID": "10.250.70.5-80",
                "ServiceName": "10.250.70.5-80",
                "ServiceTags": [
                    "web-server"
                ],
                "Status": "critical",
                "Type": "script"
            }
        ],
        "Node": {
            "Address": "10.250.85.3",
            "CreateIndex": 19982,
            "Datacenter": "dc1",
            "ID": "b12fc914-8d78-8de9-72bb-8648ef5c6fea",
            "Meta": {
                "consul-network-segment": ""
            },
            "ModifyIndex": 20012,
            "Node": "consul-node-3.novalocal",
            "TaggedAddresses": {
                "lan": "10.250.85.3",
                "lan_ipv4": "10.250.85.3",
                "wan": "10.250.85.3",
                "wan_ipv4": "10.250.85.3"
            }
        },
        "Service": {
            "Address": "",
            "Connect": {},
            "CreateIndex": 20014,
            "EnableTagOverride": false,
            "ID": "10.250.70.5-80",
            "Meta": null,
            "ModifyIndex": 20014,
            "Port": 80,
            "Proxy": {
                "Expose": {},
                "MeshGateway": {}
            },
            "Service": "10.250.70.5-80",
            "Tags": [
                "web-server"
            ],
            "Weights": {
                "Passing": 1,
                "Warning": 1
            }
        }
    }
]
```