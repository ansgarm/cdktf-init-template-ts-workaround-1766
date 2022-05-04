# Remote template for CDK for Terraform TypeScript projects

Workaround for [#1766](https://github.com/hashicorp/terraform-cdk/issues/1766) until a new version of the cdktf-cli is released.

## Usage 

Instead of
```
cdktf init --template typescript
```
use
```
cdktf init --template https://github.com/ansgarm/cdktf-init-template-ts-workaround-1766/archive/refs/heads/main.zip
```

Read more about remote templates in the [CDK for Terraform docs](https://www.terraform.io/cdktf/create-and-deploy/remote-templates).