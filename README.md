# ansible-demo
https://www.youtube.com/watch?v=YGGK6ElacRQ&amp;t=12s

versions:
```
Vagrant 2.2.6

ansible 2.9.6
  config file = None
  python version = 3.8.1 (default, Dec 27 2019, 18:06:00) [Clang 11.0.0 (clang-1100.0.33.16)]
```

- Start vagrant VM
```
vagrant up
```

- Run ansible scripts
```
ansible-playbook -i ansible_hosts -l test_server plays/test.yml
```
