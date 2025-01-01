# 🥵 About code-server in "termux"
## 👉 Runing vs-code on termux and web browser

* 🤯 You know ? You can download the **vs-code** on termux 🔥 **And all so you can run the** **vs-code** **on termux virtual inverment** **web-browser** 🗣️ , It's really cool and I show you how to download and use it
  
* 🗣️ By downloading the **vs-code**, first update the repository by using this commend 👉 👉 👉 **apt update -y** and **apt upgrade -y**, then open the termux linux virtual enviment if you don't know what is it 👉 👉 👉 check, my this **https://github.com/SANTASDVL-ODDMAR-CODER/Termux-repository** here I explane and show you how to downlaod it 🥰

* Let's start download 🗣️
  
```
apt update -y
apt upgrade -y
apt install tur-repo
apt install code-oss
apt update -y
apt upgrade -y
```

* 🤏 Those commend for downlaod the **vs-code** or another name **code-oss**
  
* ✋💀 After downlaoding the **code-oss**, run the commend 👉 👉 👉 👉 **code-oss** for run the vs-code
  
* 🫨 Or run the **code-oss** on menu, like this 🗣️
  
![Screenshot_2024-12-30_23-02-20](https://github.com/user-attachments/assets/877a7415-8e9f-487d-8701-9063b0618c32)

* 👀 This from **menu**, and another photo from **terminal**
  
![Screenshot_2024-12-30_22-44-18](https://github.com/user-attachments/assets/8ce5e95f-a844-41fe-aed0-b5c673246712)

# 🎃 Run vs-code on web-browser 
## 👉 About the code-server  
* This is possible by using the **code-server** package
* This allowed or give the access to run the **vs-code** in web-browser
* Here is the download process  

```
apt update -y
apt upgrade -y
apt install code-server
```

* After installing the code-server, open terminal and type the **code-server**, Like this 👉
  
![Screenshot_2024-12-30_23-20-16](https://github.com/user-attachments/assets/5358d80e-ce5b-46db-8278-fb22ff318753)

* 🥰 If you see those thinks, open the web-browser and enter the **127.0.0.1:8080**, **127.0.0.1** is the localhost and **8080** was the port
* 😬 After open the port you will see 👉 were it need the password
  
* ![Screenshot_2024-12-30_23-32-39](https://github.com/user-attachments/assets/46d716e9-0d0c-4ef2-82c0-10572b44b939)
* 🫨 Another time open the terminal and past this commend

```
nano /data/data/com.termux/files/home/.config/code-server/config.yaml
```

* 👉 And configer or change the password
  
![Screenshot_2024-12-30_23-39-00](https://github.com/user-attachments/assets/27aef712-0848-4369-ac45-fab4d961a1ce)

* After changing the password open the **code-server** and enter the password that you just given
* Here another commend about autherizetion with **code-server**
* Here is the commend 👉 👉 👉 👉
  
```
code-server --auth none
```

* This commend help you login with out the autherizetion or the password 🥰
* I hope this tutorial you like it, Good bye 👋
