# Ubuntu Initial Enrolment
# Instructions
After you installed an Ubuntu machine, launch this playbook with the following command to download required software and apply useful configurations:
```console
ansible-galaxy install -r requirements.yml --ignore-errors \
&& ansible-playbook ubuntu_enrolment.yaml
```


