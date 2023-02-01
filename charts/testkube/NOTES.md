# Testkube Helm Chart versions
```sh
apiVersion: v2
name: testkube
version: 1.9.3
dependencies:
- name: testkube-operator
  version: 1.9.0
- name: mongodb
  version: 12.1.31
- name: nats
  version: 0.19.1
- name: testkube-api
  version: 1.9.1
- name: testkube-dashboard
  version: 1.8.14
- name: global
  version: 0.1.0
  
apiVersion: v2
name: testkube
version: 1.9.2
dependencies:
- name: testkube-operator
  version: 1.9.0
- name: mongodb
  version: 12.1.31
- name: nats
  version: 0.19.1
- name: testkube-api
  version: 1.9.0
- name: testkube-dashboard
  version: 1.8.14
- name: global
  version: 0.1.0
```