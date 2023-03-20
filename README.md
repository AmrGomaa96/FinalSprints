# Project OverView
#### The Purpose of the project is to deploy python-app with database on a AWS cluster using Terraform to create the environment and ansible for configuration
#



## 1) Building the Environment using Terraform
### Apply the code using :
```
terraform plan 
terraform init
terraform apply
```

#

## 2) using ansible for configuration 

```
ansible-playbook playbook.yaml -i inventory.txt

```


#



## 3) Using Jenkins to build&push images
### Add the following script in the jenkins file to jenkins manually to build the docker file then push it to ecr and  apply the kubernetes files


## 4) Using the load balancer dns to access the web-app
<img src=https://user-images.githubusercontent.com/116598689/226450798-8e6c0d5c-5f6c-489d-8053-458c62c77578.jpg>


