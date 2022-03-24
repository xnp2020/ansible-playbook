- 该role将创建基于sentinel的1个master2个replics的redis集群，默认master信息为：192.168.11.11 6379，如需变更，请在执行playbook的时候输入。默认密码为'1qw2!QW@'
- 须提前修改redis_hosts为部署的服务器信息，服务器数量应为奇数
- 执行方式：ansible-playbook -i redis_hosts redis_cluster.yml

