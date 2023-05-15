# **The Code Talker**

The purpose of this project is to create a user-friendly and dynamic platform for users where they can send own ideas and experiences about Technical Knowledge.


## **Technology Stack**

We have Used,

1. Frontend: HTML, CSS, Bootstrap, JavaScript
2. Backend: Flask(Python)
3. Database: MySQL

## Project Structure

```bash
The Code Talkers
├── README.md: documentation file
├── config.json: create json file before run this code
└── main.py
```

## Run this project :

First, clone the repository to your local machine:

```bash
  git clone https://github.com/abhiumesh/The_Code_Talkers
```
Go to the project directory

```bash
  cd The_Code_Talkers
```

## 👉 Some Changes Required
Create config.json file :
```
{
  "params":
  {
    "local_server":"True",
    "local_uri": "mysql://root:@localhost/<DataBase Name>",
    "prod_uri":"mysql://root:@localhost/<DataBase Name>",
    "fb_url":"<FaceBook profile link>",
    "tw_url":"<Twitter link>",
    "gh_url": "<Github link>",
    "blog_name": "<Blog Name>",
    "tag_line": "<Tag Line>",
    "gmail-user":"<Email-id>",
    "gmail-password":"<Enter Gmail Password after Two Step Varification>",
    "no_of_posts": 3,
    "login_image":"login.jpg",
    "admin_user":"<Admin_Name>",
    "admin_password": "<admin_Password>",
    "upload_location":"<Update_location>"

  }
}
```

# Documentation

You should see :)

[Flask Official Documentation](https://flask.palletsprojects.com/en/2.3.x/) 👈

[Jinja Official Documentation](https://jinja.palletsprojects.com/en/3.1.x/) 👈

[Python Cheatsheet](https://www.w3schools.com/python/) 👈
