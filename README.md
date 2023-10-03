# CI-CD
Mikes Electronic -> public website [Software Development Team] <- Product Management Team [Gives feature to develop]
SDT -> git -> build & intregrate -> compile -> package -> OPS Team -> test environment -> testing -> public website 

📘 **OLD SCHOOL PROBLEMS** 📘

Integration is painful and effort consuming 
Fixing issues at the end of integrations 
Intermediate merge issues can hold up team 
Long Feedback cycle for functinal defects 
Long iterations 

➡️**Continous Integration** - BUILD PIPELINE 

Different components  [customer profile, product catalog, order tracking]-> Git master -> compile -> package -> automated unit tests -> automated UI tests
(Build and integrate team is dissolved)

1 EPIC -> different PR'S -> master branch -> Build -> Jar -> Docker image 
100 Files present - 10 Files modified - 100 Files jar created 

➡️**Continous Delivery** - you can deploy the image 

Package +instructions -> operations team -> read instructions -> prepare environment -> test environment -> testing    🔲 OLD SCHOOL 
Package -> operations team -> automated script -> test environment -> testing QA -> public website                     🔲 UPDATE VERSION 

➡️**Continous Deployment** - automated to production - risks involved 

🛄**DevOps - Development and Operations**

Developer -> master -> compile -> package -> automate unit tests -> automated UI tests -> Ops Team -> script automated -> test environment -> automated tests -> public website 



 
