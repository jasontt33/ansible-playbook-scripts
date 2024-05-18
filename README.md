# Project Ansible [![Build Status](https://travis-ci.org/adithyakhamithkar/ansible-playbooks.svg?branch=master)](https://travis-ci.org/adithyakhamithkar/ansible-playbooks) [![HitCount](http://hits.dwyl.io/adithyakhamithkar/ansible-playbooks.svg)](http://hits.dwyl.io/adithyakhamithkar/ansible-playbooks)

## Index
+ AWS
    - assign-eip
    - create-ec2-key
    - [create-iam-admin-group](https://github.com/adithyakhamithkar/ansible/blob/master/AWS/roles/create-iam-admin-group)
    - [create-iam-group](https://github.com/adithyakhamithkar/ansible/blob/master/AWS/roles/create-iam-group)
    - [create-iam-policy](https://github.com/adithyakhamithkar/ansible/blob/master/AWS/roles/create-iam-policy)
    - [create-iam-read-only-group](https://github.com/adithyakhamithkar/ansible/blob/master/AWS/roles/create-iam-read-only-group)
    - create-iam-role
    - [create-iam-user](https://github.com/adithyakhamithkar/ansible/blob/master/AWS/roles/create-iam-user)
    - create-sg-db
    - create-sg-web
    - create-vpc
    - launch-ec2
    - start-ec2
    - stop-ec2
+ MySql
    - mysql-create-db
    - mysql-create-user
    - mysql-dump
    - mysql-import
    - transfer-db
+ Hacking
    - [john-the-ripper](https://github.com/adithyakhamithkar/ansible/blob/master/Hacking/roles/john-the-ripper)
+ List of Roles
    - [agar](https://github.com/adithyakhamithkar/ansible/blob/master/roles/agar)
    - [ansible](https://github.com/adithyakhamithkar/ansible/blob/master/roles/ansible)
    - beef
    - bitcoin (WIP)
    - bittorrentsync
    - build-docker-image
    - cachethq (Not working)
    - [cassandra](https://github.com/adithyakhamithkar/ansible/blob/master/roles/cassandra)
    - common
    - create-user
    - datadog-agent
    - deployment-nginx
    - deployment-phpmyadmin
    - docker
    - docker-clean
    + [elasticsearch](https://github.com/adithyakhamithkar/ansible-playbooks/blob/master/roles/elasticsearch/README.md)
        - elasticsearch-data
        - elasticsearch-master
    - epoch
    - fail2ban
    - filebeat
    - galera
    - gitlab
    - glassfish
    - gradle
    - grafana-server
    - hadoop
    - hostname
    - ipa-client
    - ipa-server
    - jdk
    - jenkins
        - jenkins-configure
    - [kafka](https://github.com/adithyakhamithkar/ansible/blob/master/roles/kafka)
        - [kafka-manager](https://github.com/adithyakhamithkar/ansible/tree/master/roles/kafka-manager)
    - kibana
    - kubernetes
    - ldap-server
    - lets-encrypt
    - logstash
    - [mesos](https://github.com/adithyakhamithkar/ansible/blob/master/roles/mesos)
        - mesos-master
        - mesos-slave
    - mongodb
    - motd
    - mysql
    - newrelic
        - new-relic-java-agent (WIP)
        - new-relic-php-agent
        - new-relic-server-agent
    - nexus
    - nginx (Configured to support http 2.0)
        - nginx-jenkins
        - nginx-load-balancer
        - nginx-sensu-master
    - nodejs
    - [ntp](https://github.com/adithyakhamithkar/ansible/tree/master/roles/ntp)
    - odoo
    + [ossec](https://github.com/adithyakhamithkar/ansible/blob/master/roles/ossec-server)
        - ossec-server
        - ossec-agent
    - packer  
    - [phabricator](https://github.com/adithyakhamithkar/ansible/blob/master/roles/phabricator)
    - php
    - php7
    - [postfix](https://github.com/adithyakhamithkar/ansible/tree/master/roles/postfix)
    - psad
    - rabbit-mq
    - rancher
    - redis
    - roles-template
    - rootkit-scanners
        - chkrootkit
        - rkhunter
    - [s3fs](https://github.com/adithyakhamithkar/ansible/blob/master/roles/s3fs)
    - [saltstack](https://github.com/adithyakhamithkar/ansible/tree/master/roles/salt-master)
        - salt-master
        - salt-minion
    - scala
    - sensu
        - sensu-client
        - sensu-client-checks
        - sensu-master
    - solr
    - ssh-banner
    - ssh-keys
    - teamcity
    - tiger
    - tomcat
    - varnish
    - youtrack
    - [zookeeper](https://github.com/adithyakhamithkar/ansible/blob/master/roles/zookeeper)
