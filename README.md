# ansible-role-template
Basic template for developing Ansible Roles

'''
ansible-playbook \
  --limit ubuntu5 \
  --inventory ansible-umich-perfsonar-core/inventory/ \
  --become \
  --become-method su \
  --become-user root \
  --ask-become-pass \
  ubuntu5.yml
'''

'''
ansible-playbook \
  --limit ubuntu5 \
  --inventory ansible-umich-perfsonar-core/inventory/ \
  --become \
  --become-method su \
  --become-user root \
  --ask-become-pass \
  --tags unibuild \
  ubuntu5.yml
'''
