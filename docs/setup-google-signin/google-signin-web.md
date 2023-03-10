---
sidebar_position: 1
sidebar_label: Setup Android Google Sign In
---
# Setup Google Signin Web App

Hallo Doctor Web app, already implemented google singin with firebase you don't have to do much work to make working,
you only need to add your domain in firebase authentication setting 

- goto your firebase project <https://console.firebase.google.com/>
- goto Authentication -> Setings -> Authorized domain
- add localhost, because we have not deployed our app to hosting, later you need to add your domain in this setting

![googlesingweb](assets/google%20signin%20domain.png)


that's it, you can now test sign in with google

