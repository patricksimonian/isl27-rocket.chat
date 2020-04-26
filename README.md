# Rocket.Chat

This is a simple rocket chat deployment that contains two main components:

The HA MongoDB database and the Rocket.Chat Client


## Setup on Openshift

This project was deployed on a fresh openshift cluster found at https://www.openshift.com/learn/courses/playground/. For this reason there are several preliminaries that need to be accomplished prior to getting the app up. The preliminaries are:
- clone this repository into a working directory
  - git clone https://github.com/patricksimonian/isl27-rocket.chat.git
  - cd isl27-rocket.chat
- dev/test/prod openshift namespaces created
  - run `ansible-playbook ansible/setup-projects.yaml`