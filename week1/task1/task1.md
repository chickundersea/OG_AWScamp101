# 【問答題】
##  root user 跟 iam user 的差別？  
root user -> 用來建立 AWS 帳戶時的主帳號，擁有 AWS 帳戶的所有權限
IAM user -> 由 Root User 建立，用於分配個別帳號不同權限

## user, group, role, policy 彼此間的關係為何？policy 的格式為何？  

user：可以是一個人或應用程式，會擁有一組登入用的帳密各別管理
group：多個 user 的集合，用來分類管理權限，例如部門或專案區分

role：代表一個身份或服務，不需要登入，可以指定權限，例如指定S3可以訪問哪些資源

policy：JSON格式定義具體規範誰能做什麼事在什麼資源上