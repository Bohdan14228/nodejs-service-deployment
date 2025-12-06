# nodejs-service-deployment
🔗 **Project page:** [https://roadmap.sh/projects/nodejs-service-deployment](https://roadmap.sh/projects/nodejs-service-deployment)

1. Create Instance use Terraform https://github.com/Bohdan14228/iac-aws

2. Add IP in .gitlab-ci.yml
```bash
INSTANCE_IP: "13.38.12.7"
```

3. Add $INSTANCE_IP to Variebles CI/CD Settings

4. Optional: chage user for instance, here:
```bash
- echo "$INSTANCE_IP ansible_user=ubuntu ansible_port=22" >> ./inventory.ini
```
