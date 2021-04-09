## Usage tips

You need to add `-hcl 'disable_remote_exec=false'` to `consul agent` starting command for enabling remote execution. 

Or you will have the following error:

https://stackoverflow.com/questions/53151941/consul-exec-doesnt-do-anything/53154649#53154649

```
# consul exec -verbose  uptime
Created remote execution session: 853057f3-3313-8be7-4ba6-97ea34ae63c5
Uploaded remote execution spec
Fired remote execution event: 9acf1acc-c4eb-91e6-f75d-8ad3b97b911b
0 / 0 node(s) completed / acknowledged

```

## Command And Output Example

```
# consul exec -verbose  uptime
Created remote execution session: c3e02bfc-9040-b2f5-dede-c8a7032cd479
Uploaded remote execution spec
Fired remote execution event: 71959d6b-6a28-5244-dd70-674b942e5e08
==> consul-node-3.novalocal: acknowledged
    consul-node-3.novalocal:  02:59:14 up 2 days, 13:16,  2 users,  load average: 0.00, 0.01, 0.05
    consul-node-3.novalocal:
==> consul-node-3.novalocal: finished with exit code 0
==> consul-node-2.novalocal: acknowledged
==> consul-client-1.novalocal: acknowledged
==> consul-client-3.novalocal: acknowledged
==> consul-client-4.novalocal: acknowledged
    consul-node-2.novalocal:  02:59:14 up 2 days, 13:16,  0 users,  load average: 0.00, 0.01, 0.05
    consul-node-2.novalocal:
    consul-client-1.novalocal:  02:59:14 up 2 days, 30 min,  0 users,  load average: 0.01, 0.06, 0.05
    consul-client-1.novalocal:
    consul-client-3.novalocal:  02:59:14 up 2 days, 30 min,  0 users,  load average: 0.01, 0.04, 0.05
    consul-client-3.novalocal:
    consul-client-4.novalocal:  02:59:14 up 2 days, 30 min,  0 users,  load average: 0.00, 0.03, 0.05
    consul-client-4.novalocal:
==> consul-node-2.novalocal: finished with exit code 0
==> consul-client-1.novalocal: finished with exit code 0
==> consul-client-3.novalocal: finished with exit code 0
==> consul-client-4.novalocal: finished with exit code 0
==> consul-node-1.novalocal: acknowledged
    consul-node-1.novalocal:  02:59:14 up 2 days, 13:16,  0 users,  load average: 0.19, 0.09, 0.06
    consul-node-1.novalocal:
==> consul-node-1.novalocal: finished with exit code 0
==> consul-client-2.novalocal: acknowledged
    consul-client-2.novalocal:  02:59:14 up 2 days, 30 min,  0 users,  load average: 0.03, 0.05, 0.05
    consul-client-2.novalocal:
==> consul-client-2.novalocal: finished with exit code 0
7 / 7 node(s) completed / acknowledged

```