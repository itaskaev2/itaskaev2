# ~/ilia $ whoami

```bash
$ whoami
ilia --devops --cloud-native --curious

$ cat /etc/profile.d/about.sh
NAME="Ilia Taskaev"
ROLE="DevOps / Cloud Engineer"
LOCATION="Novi Sad, Serbia"
PHILOSOPHY="Everything as Code"

$ aws configure list
      Name                    Value
      ----                    -----
      region                  eu-north-1

$ cat /etc/tech-stack
CLOUD           AWS | Amazon EKS
CONTAINERS      Kubernetes | Docker | Helm
IaC             Terraform | CloudFormation
GITOPS          Flux CD | GitOps
CI/CD           GitHub Actions
SCRIPTING       Bash | Python
OS              Linux

$ kubectl get pods -A
NAMESPACE     NAME                    STATUS
kube-system   coffee-controller       Running
production    infrastructure          Running
gitops        flux-reconciler         Running
personal      side-projects           Pending

$ flux get kustomizations
NAME             READY   MESSAGE
infrastructure   True    Applied revision: main
applications     True    Reconciliation succeeded
life-balance     False   Drift detected: too much work

$ terraform plan
Plan: 3 to add, 0 to change, 0 to destroy.

$ cat ~/interests.txt
Cloud Architecture
AI Agents & Automation
Reverse Engineering
Game Development / Godot
Gaming & Gym

$ git log -1 --oneline
a1b2c3d automate everything, again

$ echo $LIFE_PHILOSOPHY
"Automate the boring stuff. Reverse engineer the fun stuff."

$ uptime
40 years of continuous learning.
```
