# DNSimple

> **note**
> 
> new in version 0.3

Terraform can use DNSimple to provide DNS records for your cluster,
independent of which provider you use to provision your servers.

## DNSimple Username/Token

The easiest way to configure credentials for DNSimple is by setting
environment variables:

Alternatively, you can set up the DNSimple provider credentials in your
.tf file:

``` sourceCode shell
provider "dnsimple" {
  token = "your dnsimple token"
  email = "your e-mail address for the dnsimple account"
}
```
