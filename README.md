# ansible-vpn

### To launch the server on AWS:
ansible-playbook -i hosts --ask-vault-pass newansible.yml

the shutdown script required me to specify an AWS profile other then the default like this:
AWS_PROFILE=yehudafull ansible-playbook -i hosts shutdown.yml
