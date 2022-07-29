```hcl

provider "aws" {
  region = "us-east-1"
}

module "docker_instance" {
    source = "Kaplanibrahim/docker-instance/aws"
    key_name = "your_keyname"
}
```