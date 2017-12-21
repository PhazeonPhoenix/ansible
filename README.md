# PES7 ansible playbook

first run

```
ansible-galaxy install -r requirements.yml

```

then

```
ansible-playbook site.yml -i hosts.yml [-u user] [-K]
```

-u specifies the remote user ansible will connect with. -K will ask for
privilege escalation password (sudo)
