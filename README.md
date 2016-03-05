# samus-arcade.provisioning
Ansible all afternoon

## Testing with Vagrant
Initial setup:
```
vagrant up --provision
```

Connect to box:
```
vagrant ssh
```

Stops and delets machine:
```
vagrant destroy
```

Run an ansible playbook manually against  machine (instead of vagrant provision):
```
run_ansible_on_vagrant.sh <playbook>
```

## Being fancy
![ScreenShot](.fancy-machine.jpg)
