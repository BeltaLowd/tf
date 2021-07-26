resource "aws_instance" "server" {
  count = 4 # create four similar EC2 instances

  ami           = "ami-03caf24deed650e2c"
  instance_type = "t2.micro"

  tags = {
    Name = "Rangles ${count.index}"
  }
}
