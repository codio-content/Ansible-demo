Install dependencies:

`ansible-galaxy install -r requirements.yml`


Play playbook locally:

`ansible-playbook wordpress.yml`

Play roles separately:

`ansible-playbook web.yml -i inventory/localhost.yml `
`ansible-playbook database.yml -i inventory/localhost.yml `