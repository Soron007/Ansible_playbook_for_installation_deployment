Managing servers manually is time-consuming and prone to errors. To make things more efficient, I automated my daily infrastructure tasks using Ansible playbooks—saving time and ensuring consistency across my AWS EC2 instances!

🔹 What I Automated with Ansible:
✅ Installed Packages – Automatically installed Apache and Nginx across multiple servers
✅ Configured Apache – Copied the updated apache2.conf file and ensured it had the right permissions
✅ Restarted Services – Automatically restarted Apache after configuration changes
✅ Created Directories & Files – Set up a custom directory (/opt/mydir) and generated required files inside it
✅ Ensured Idempotency – If a task was already completed, Ansible skipped it, avoiding unnecessary changes
✅ Handled Errors Gracefully – Debugged Apache restart failures by checking logs and fixing configuration issues
✅ Handled Security – prevented inventory.ini, vars.yaml and apache2.conf files from getting committed to the git repo

Using Ansible playbooks, I eliminated repetitive tasks, improved server provisioning, and ensured smooth deployments across multiple environments! 🚀

Please check my repo for this project: https://lnkd.in/g7NJQXiq


💡 What’s Next?
🔹 Integrating this with CI/CD pipelines for fully automated deployments
🔹 Using Ansible Vault to securely manage credentials 🔐
🔹 Expanding automation to handle load balancers & database configurations

This experience reinforced how automation is a game-changer in DevOps and cloud management! 🌍
