Lab 1 Command
////////////////////////////////////////////////////////A////////////////////////////////////////
A- Create SSh Key
     Command:ssh-keygen -t ed25519 -C "mohamedtarek1303@gmail.com"

     Result:
     Your public key has been saved in C:\Users\Mohamed Tarek/.ssh/id_ed25519.pub.
SHA256:KDnZZngSPWjL5B/NP4Q1lmU3R+hAr0k3gvxvzynIwd8 mohamedtarek1303@gmail.com
The key's randomart image is:
|           .+ ooo|
|     o   . =.o.o |
|    = o   B oo+  |
|   = B = + + =.. |
|    @ B S o +    |
|     O . o o .   |
|      .   + + +  |
|           + + E.|
|              ..o|
+----[SHA256]-----+

////////////////////////////////////////////////B///////////////////////////////////
1-Create Local Repo
      Command: git init
2-add html file   
      Command:git add .
      Command:git status
      Result:
              On branch master
              No commits yet
              new file: index.html
      Command: git commit -m "initial commit"
3-Add Paragraph with Name  
      Command:git commit -a -m"add FullName"
      Result:
             [master 2456da7] add FullName

 4-Add and Push to Remote Repo           
      Command:git remote add origin git@github.com:mohamedtarek01141/lec-test.git
      Command:git push origin master


      