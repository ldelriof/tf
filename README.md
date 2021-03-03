## deploy dev

create dev secrets file
```
echo 'secret = "dev-secret"' > dev.secret.auto.tfvars
```
run
```
terraform apply
```

## deploy prod

create prod secrets file
```
echo 'secret = "prod-secret"' > prod.secret.tfvars
```
run
```
./deploy_prod.sh
```
