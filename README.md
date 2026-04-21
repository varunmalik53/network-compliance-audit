malik1@DL9V2LYWX5-MBP Network_compliance % tree
.
├── network_compliance.yml
├── non_compliance_report.csv
└── vars
    └── secrets.yml

2 directories, 3 files
malik1@DL9V2LYWX5-MBP Network_compliance % 


ansible-vault edit vars/secrets.yml
# Make sure vault_jira_user is your primary Atlassian email

ansible-vault create vars/secrets.yml
ansible-vault edit vars/secrets.yml

vault_librenms_token: "YOUR_LIBRENMS_TOKEN"
vault_jira_token: "YOUR_ATLASSIAN_API_TOKEN"
vault_jira_user: "malik1@yourcompany.com"
