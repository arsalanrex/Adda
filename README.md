# Adda
A whatsapp-like chat application created using firebase as the backend. 

Steps to use the repo:

1. Clone the repo and save it locally.
2. Open it with android studio or install the .apk file.
3. If opened in android studio simulate it else instal the apk on your mobile.
4. Register with an unique username.
5. login with the username.

For more info check out the documentation.

---------------------------------------------------------------------------------------------------------------------------------

To create your own firebase server:

1. Create a firebase account. 
2. Create a project "Adda".
3. In the project give the package name: "com.arsalan.adda".
4. Give a nickname.
5. Do NOT give the SHA certificate. 

Set up the Authentication:
1. Go to Sign-in method and turn on Email/Password.

Set up the Database:
1. Create a realtime database.
2. Set the rules as:
{
  "rules": {
    ".read": true,
    ".write": true
  }
}

---------------------------------------------------------------------------------------------------------------------------------

Enjoy!!!

For queries mail me: arsalan.rex@gmail.com

