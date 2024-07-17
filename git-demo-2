provider "aws" {
  region ="us-east-1"
}

resource "aws_instance" "test2-ec2" {
    ami="ami-053b0d53c279acc90"
    instance_type = "t2.micro"
    tags = {
      Name="Git-Demo-2"
      Department="Git"
    }
 }
