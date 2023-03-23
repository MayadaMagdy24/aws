# users-groups-aws
1-	Create aws account and set billing alarm
![Screenshot (604)](https://user-images.githubusercontent.com/93229250/227193777-7ce97857-0c9a-4924-9910-63f66f3c50ef.png)

2-  Create 2 groups one admin and one for development
• in the admin group it has admin permission 
![Screenshot (606)](https://user-images.githubusercontent.com/93229250/227194372-e907f457-b489-4a97-ad5a-53a4b1c7b17d.png)

and in the development only access to s3
![Screenshot (605)](https://user-images.githubusercontent.com/93229250/227194325-e036fc4d-a67d-460b-91ba-a40a91b8db72.png)

create admin-1 user console access and mfa enabled in admin group
![Screenshot (607)](https://user-images.githubusercontent.com/93229250/227194508-c1ff2c73-a252-442e-a3f6-02212c8cb551.png)

• and admin2-prog with cli access only 
![Screenshot (608)](https://user-images.githubusercontent.com/93229250/227194812-3b86d996-85d8-4377-bbeb-625b25617d2b.png)
and list all users and groups using commands not console
![Screenshot (610)](https://user-images.githubusercontent.com/93229250/227195012-27c7af1a-bf6c-46b5-8e15-f69745f19ebe.png)
![Screenshot (611)](https://user-images.githubusercontent.com/93229250/227195061-897e1123-5d50-4911-a698-3af8086117c8.png)

•in the development group create user with name dev-user with programmatic and console access then try to access aws using it (take a screenshot from accessing ec2 and s3 console)
![Screenshot (616)](https://user-images.githubusercontent.com/93229250/227196306-ec6def84-432c-4414-bef5-a4d928754c2d.png)
![Screenshot (617)](https://user-images.githubusercontent.com/93229250/227196337-10525cca-4cd8-4978-a0b9-86d8332108db.png)

•Also access cli using dev-user and try to get all users and groups using it 
![Screenshot (614)](https://user-images.githubusercontent.com/93229250/227195803-c859d53c-1556-40d8-b109-09ee57e5f112.png)
3- Create ec2 and install apache2 on it.
![Screenshot (613)](https://user-images.githubusercontent.com/93229250/227195635-29a4b0dc-979b-438b-807c-4c19687110ec.png)
![Screenshot (615)](https://user-images.githubusercontent.com/93229250/227195670-340054fa-15a5-457c-98de-96dc34258fbe.png)
