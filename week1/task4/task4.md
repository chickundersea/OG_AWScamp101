嘗試寫一個 shell script 腳本，用來印出 EC2 相關資訊。
提供您的腳本（github repo）。
使用方式及輸出格式如下：
$ sh ./ec2_info.sh i-0123456789abcdef0
=== EC2 Information ===
Instance ID : i-0123456789abcdef0
Instance Type : t3.micro
State : running
Launch Time : 2025-01-01T10:00:00Z
VPC ID : vpc-12345678
Subnet ID : subnet-98765432
Private IP : 10.0.1.25
Public IP : 3.115.22.53