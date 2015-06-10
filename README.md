Infrastructure
==============

Install dependencies

```
ansible-galaxy install -r requirements.yml --ignore-errors
```

Run with 

```
ansible-playbook -i ec2.py site.yml
```
