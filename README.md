# Java_project_mysql

### ๐ ํ๋ก์ ํธ ์ฃผ์  
######  ๋ฐ์ดํฐ๋ฒ ์ด์ค ๊ด๋ฆฌ์์คํ์ธ MySQL์ ์ ๊ทผํ์ฌ ๋ฐ์ดํฐ๋ฒ ์ด์ค๋ฅผ ์ถ๊ฐ, ์ญ์ , ์กฐํํ  ์ ์๋ ์๋ฐ ํ๋ก๊ทธ๋จ 

### โ  ์ฝ๋ ๊ฐ์ 

1. GUI๊ตฌ์ฑ ์ฝ๋ (StudentGUI.java) - ํ๋ ์ ์์ฑ

![image](https://user-images.githubusercontent.com/86222503/151692943-069663de-0fca-473e-984b-faed55f251a3.png)


![image](https://user-images.githubusercontent.com/86222503/151692945-a4cb4c13-adda-49ce-80d6-75f114e364b3.png)




- ๋ค์๊ณผ ๊ฐ์ด setTitle()์ ํตํด ํ๋ก๊ทธ๋จ ์ ๋ชฉ์ โIT์ ๋ณด๊ณตํ๊ณผ JAVA ๊ฐ์ฒด์งํฅํ๋ก๊ทธ๋๋ฐ ํ์ ๊ด๋ฆฌ ํ๋ก๊ทธ๋จโ์ผ๋ก ์ง์ ํ๊ณ  SetBounds()๋ฅผ ํตํด ๊ฐ๋ก,์ธ๋ก ์์น ๋ฐ ํฌ๊ธฐ์กฐ์ ์ ํ๋ค.
- SetDefaultCloseOperation() ๋ฉ์๋๋ฅผ ์ด์ฉํด ์๋์ฐ ์ฐฝ ์ข๋ฃ์ ํ๋ก์ธ์ค๊น์ง ๊น๋ํ๊ฒ ์ข๋ฃํ  ์ ์๋๋ก ์ค๊ณํ์๋ค.

2. GUI๊ตฌ์ฑ ์ฝ๋ (StudentGUI.java) - ์๋ ฅ ํจ๋ ์์ฑ

![image](https://user-images.githubusercontent.com/86222503/151692979-80e918c1-e905-484a-915c-ee2c506e5036.png)


















-  ์๋จ ๋ฐ์ดํฐ๋ฒ ์ด์ค ์ ๋ณด ์๋ ฅ ํจ๋๊ณผ ํ๋จ์ DB์ ๋ณด ์๋ ฅ ํจ๋์ JPanel์ ํตํด ๋ง๋ค์ด ์ถ๊ฐํ์๋ค.

3. GUI๊ตฌ์ฑ ์ฝ๋ (StudentGUI.java) - ํ๋จ ๊ธฐ๋ฅ ๋ฒํผ ํจ๋ ์์ฑ
 
![image](https://user-images.githubusercontent.com/86222503/151693030-1dbcb929-0cd0-415b-967a-648acca47ace.png)







- ํ๋จ์ DB์ ๋ํ ๋ฐ์ดํฐ ์ถ๊ฐ, ์์ , ์ญ์ , ์กฐํ๋ฅผ ํ  ์ ์๋ ๋ฒํผ ํจ๋์ JButton์ ์ฌ์ฉํ์ฌ ๊ตฌํํ์๋ค.  


4. GUI๊ตฌ์ฑ ์ฝ๋ (StudentGUI.java) - ์ ๋ณด์ถ๋ ฅ ํจ๋ ์์ฑ

![image](https://user-images.githubusercontent.com/86222503/151693044-c8203f23-c3f0-4345-81d2-379b25c8bd05.png)




- ์ค์์์ญ์ table์ ์์ฑํ์ฌ vector๋ฅผ ์ฌ์ฉํ์ฌ ์ปฌ๋ผ๋ช์ ์ค์ ํ์๋ค.
- isCellEditable ์ด๋ผ๋ ๋ถ๋ถ์ ํ์ด๋ธ์ ์ง์  ์์ ํ ์ ์๊ฒ ๋ง์๋ ๋ถ๋ถ์ด๋ค.

---------------------------------------------------------------------------------------

- StudentDB.java

1. DB์ Eclipse ์ฐ๊ฒฐ โ getConnection() ๋ฉ์๋

![image](https://user-images.githubusercontent.com/86222503/151693050-21497ae3-e60e-4d6b-96e9-9b0919374faf.png)


- ์ดํด๋ฆฝ์ค์์ ๋ฏธ๋ฆฌ ๊ตฌ์ถํ MySQl์ DB์ ์ ๊ทผํ ์ ์๋๋ก getConnection() ๋ฉ์๋๋ฅผ ์ ์ํ์๋ค.




 
            String driver = DB ์ฐ๊ฒฐํ  ๋ ์ฌ์ฉํ  ๋๋ผ์ด๋ฒ ์ ๋ณด
            String url = ์ ์ํ  DB ์๋ฒ
            String user = MySQL ์์ด๋
            String password = MySQL ๋น๋ฐ๋ฒํธ


2. Eclipse๋ฅผ ํตํด MySQL๋ก๊ทธ์ธ Login() ๋ฉ์๋ / StudentDB.java






![image](https://user-images.githubusercontent.com/86222503/151693071-9b03be51-2d7e-4ebe-951b-2f7a34f6d103.png)







- login() ๋ฉ์๋
DB๋ด์ ํ์ด๋ธ์ ํตํด ์์ฑํ ๋ฐ์ดํฐ์ ์ ๋ณด (์ด๋ฆ ๋ฐ ๋น๋ฐ๋ฒํธ )๋ฅผ ํตํด Login ํ  ์ ์๋ ๋ฉ์๋๋ฅผ ์ ์ํ์๋ค.

3. Eclipse๋ฅผ ํตํด MySQL์ ๋ฐ์ดํฐ ์ฝ์ insert() ๋ฉ์๋ /StudentDB.java



![image](https://user-images.githubusercontent.com/86222503/151693084-c3e41b7f-3c73-41de-bf4e-e62780920ffd.png)









- insert()๋ฉ์๋
Login์ ํ๋ฉด MySQL์ ์์ฑํ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ์ ๊ทผ์ ํ  ์ ์๋ค.
insert()๋ฉ์๋๋ฅผ ํตํด MySQL์ ์์ฑํ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ๋ฐ์ดํฐ๋ฅผ ์ถ๊ฐํ  ์ ์๋ค.








4. Eclipse๋ฅผ ํตํด MySQL์ ๋ฐ์ดํฐ ์ฝ์ delete() ๋ฉ์๋ /StudentDB.java


![image](https://user-images.githubusercontent.com/86222503/151693088-d7a8c567-e60e-4375-adab-1e9122e43ce5.png)
















- delete()๋ฉ์๋
Login์ ํ๋ฉด MySQL์ ์์ฑํ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ์ ๊ทผ์ ํ  ์ ์๋ค.
delete()๋ฉ์๋๋ฅผ ํตํด MySQL์ ์กด์ฌํ๋ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ๋ฐ์ดํฐ๋ฅผ ์ญ์ ํ  ์ ์๋ค.


5. Eclipse๋ฅผ ํตํด MySQL์ ๋ฐ์ดํฐ ์์  correct(() ๋ฉ์๋ /StudentDB.java


![image](https://user-images.githubusercontent.com/86222503/151693091-7c232ab7-3aaf-4ad8-a730-15a0a9131b69.png)










- correct() ๋ฉ์๋
Login์ ํ๋ฉด MySQL์ ์์ฑํ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ์ ๊ทผ์ ํ  ์ ์๋ค.
correct()๋ฉ์๋๋ฅผ ํตํด MySQL์ ์กด์ฌํ๋ ๋ฐ์ดํฐ๋ฒ ์ด์ค์ ๋ฐ์ดํฐ๋ฅผ ์์ ํ  ์ ์๋ค.



### โ ํ๋ก๊ทธ๋จ ์ค๋ช 
![image](https://user-images.githubusercontent.com/86222503/151693179-2fd25585-c888-47ef-afba-8031a72b73f1.png)

![image](https://user-images.githubusercontent.com/86222503/151693183-7a36300b-7e65-4ec2-b737-38bfc37c3e93.png)

![image](https://user-images.githubusercontent.com/86222503/151693185-25e393b1-4b4f-4d4c-831c-93f4b3cdeb58.png)

![image](https://user-images.githubusercontent.com/86222503/151693186-0f201c89-5f61-41ba-ae15-2eb458892286.png)


![image](https://user-images.githubusercontent.com/86222503/151693190-04346e97-3cc8-484d-aa3b-46cdcf8fad8c.png)

![image](https://user-images.githubusercontent.com/86222503/151693195-99630367-312a-490f-8721-f5ebfd1c88ce.png)

![image](https://user-images.githubusercontent.com/86222503/151693196-f7dcabf7-e204-4936-92d9-5f87b5bdcb49.png)


![image](https://user-images.githubusercontent.com/86222503/151693199-63b7eccd-ed8c-4ce2-8547-ae37269f4a9f.png)



### โ ํ๋ก์ ํธ ์ต์ข๊ฒฐ๊ณผ๋ฌผ 
![image](https://user-images.githubusercontent.com/86222503/151693126-3b520546-04de-4962-8910-df28884df389.png)


