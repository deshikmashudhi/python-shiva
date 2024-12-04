# HEADING 1
- this is a bullet point 
- orange
- banana
- apple
- custurd

## HEADING 2
 1. orange
 2. banana
 3. apple
 4. custurd #this is in numberic format
 - [join devops](https://www.joindevops.com/)
 - ![sample](https://t4.ftcdn.net/jpg/03/96/98/33/360_F_396983381_AcuGFHQbNn7D9eercXFpOecN7d7B5F66.jpg)
 
### HEADING 3
#to write a command: `sh hello world.sh`

#### HEADING 4
``` yaml ansible
- name: Grant user Joe read access to a file
  acl:
    path: /etc/foo.conf
    entity: joe
    etype: user
    permissions: r
    state: present

- name: Removes the ACL for Joe on a specific file
  acl:
    path: /etc/foo.conf
    entity: joe
    etype: user
    state: absent 

```

##### HEADING 5

###### HEADING 6
