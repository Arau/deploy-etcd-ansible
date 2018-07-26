# Install etcd3 through Ansible

## Playbook

Install and run etcd3

## Inventory example

```
cat <<END > hosts.example
[nodes]
centos-1 IP=172.28.128.17
centos-2 IP=172.28.128.18
centos-3 IP=172.28.128.19
END
```

## Run

```
$ansible-playbook -i hosts.example site.yml
```

