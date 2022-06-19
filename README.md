## Create VM in GCP using Terraform

Following are the files that are needed:
```
main.tf
vars.tf
provider.tf
```

## Apply your details inside vars.tf file:

Following are the details that you need to mention:
```
1. project_id
2. region
3. zone
4. vm_name
5. machine_type
6. image
```

## Commands to apply the script:

1. To Initialize 

```
$ terraform init
```
2. To check the plan for the terraform

```
$ terraform plan
```
3. To Apply the terraform script

```
$ terraform apply
```

Now check your GCP Console, VM is successfully created.