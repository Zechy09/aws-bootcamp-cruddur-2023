# Week 0 — Billing and Architecture
#Got CLI working by installing AWS CLI 
    updated gitpod.yml
Using the GUI, I created a new user and generated AWS credentials for the new user
Created admin group and apply administrator access
Created security credentials and access key
chose AWS CLI access and downloaded CSV with credentials
Set Env Variables
export AWS_ACCESS_KEY_ID=""
export AWS_SECRET_ACCESS_KEY=""
export AWS_DEFAULT_REGION=us-east-1

Tell gitpod to remember these credentials on relaunch of workspaces:
gp env AWS_ACCESS_KEY_ID=""
gp env AWS_SECRET_ACCESS_KEY=""
gp env AWS_DEFAULT_REGION=us-east-1
gitpod /workspace $ aws sts get-caller-identity
{
    "UserId": "AIDATNXYXXUCH3NNXQJAY",
    "Account": "235671108868",
    "Arn": "arn:aws:iam::235671108868:user/Obinna"
}