provider "aws" {
  region = "us-east-1"
}

resource "aws_instance" "terraform_ec2" {
  ami           = "ami-0fc5d935ebf8bc3bc" # Ubuntu 22.04 (example)
  instance_type = "t2.micro"

  tags = {
    Name = "terraform-ec2"
    resource "aws_instance" "example" {
  ami           = "ami-0fc5d935ebf8bc3bc"   # Ubuntu 22.04
  instance_type = "t2.micro"

  tags = {
    Name = "terraform-ec2"
  }
}

  }
}
