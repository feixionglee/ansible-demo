# ansible-demo
https://www.youtube.com/watch?v=YGGK6ElacRQ&amp;t=12s

- Start vagrant VM
```
vagrant up
```

- Run ansible scripts
```
ansible-playbook -i ansible_hosts -l test_server plays/test.yml
```
