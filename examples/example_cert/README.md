# Azure Key Vault Cert

Creates a cert and insert it in an existing Azure Keyvault.

## Usage
To run this example, simply execute:

```hcl
terraform init
terraform plan
export ARM_CLIENT_ID=" "
export ARM_CLIENT_SECRET=" "
export ARM_SUBSCRIPTION_ID=" "
export ARM_TENANT_ID=" "
terraform apply
```

Once you are done, just run 
```hcl
terraform destroy
```

## Outputs
| Name | Type | Description | 
| -- | -- | -- | 
| secret_ids | string | Returns the AKV secret IDs of the created certificates. | 
