#Read Me
#-------------------------------------------------------------------
# This playbook is used to deploy a web application running on Tomcat
# from jenkins
# Deployment is not done concurrently to all servers, but to be done
# one by one
# serial: 1
# gather_facts: true
#-------------------------------------------------------------------

To Run in STG
```
ansible-playbook release.yml -i staging -u <deploy_user>
``
To Run in PROD
```
ansible-playbook release.yml -i production -u <deploy_user>
```

