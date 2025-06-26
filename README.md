# Ansible role quiz

## Presentation
This ansible role allows to deploy a web app made with node js. It contains a quiz about Ansible.

The app is available on port 3000.

## What does this role do?
- Install Git and node JS.
- Clone the repository https://github.com/franklin-tutorials/quiz-ansible.git
- Install NPM dependencies
- Compile and run app


## How to use this role?
- Create a playbook in yaml. For example : deploy-quiz.yaml
- Specify the targets : 
  ```
  hosts: rocky
  ```
- Call the role : 
  ```
  roles:
   - ansible-role-quiz
  ```
