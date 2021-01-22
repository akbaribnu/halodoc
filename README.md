# DevOps Test Akbar

## Getting Started

* dont forget for change some variables file in **host** file in variable bellow


```
ansible_ssh_private_key_file=your_location_ssh_private_key
ansible_host=your_ip_address_host
ansible_user=user_ssh
```

* if failed to provisioning with this playbook, please try again, because sometimes if your connection not stable effect to success provisioning

* run playbook with this command from root git repository


```ansible-playbook main.yaml -i hosts ```



