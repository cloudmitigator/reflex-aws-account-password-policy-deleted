# reflex-aws-account-password-policy-deleted
TODO: Write a brief description of your rule and what it does.

## Usage
To use this rule either add it to your `reflex.yaml` configuration file:  
```
rules:
  - reflex-aws-account-password-policy-deleted:
      email: "example@example.com"
```

or add it directly to your Terraform:  
```
...

module "reflex-aws-account-password-policy-deleted" {
  source           = "github.com/cloudmitigator/reflex-aws-account-password-policy-deleted"
  email            = "example@example.com"
}

...
```

## License
This Reflex rule is made available under the MPL 2.0 license. For more information view the [LICENSE](https://github.com/cloudmitigator/reflex-aws-account-password-policy-deleted/blob/master/LICENSE) 