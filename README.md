# ansible-config
Personal Ansible Collection

## Requirements

- boto3
- ansible
- python

I personally used the following setup:

```
$ ansible --version
ansible 2.3.0.0
  config file = /etc/ansible/ansible.cfg
  configured module search path = Default w/o overrides
  python version = 2.7.5 (default, Nov  6 2016, 00:28:07) [GCC 4.8.5 20150623 (Red Hat 4.8.5-11)]
$ python -c "import boto;print boto.__version__"
2.46.1
$ python -c "import boto3;print boto3.__version__"
1.4.4
```



