---
sidebar_position: 1
sidebar_label: Setup Doctor Category
---

# Setup Doctor Category & Admin Account

after you successfully deploy your Firebase Cloud Functions to Firebase, in the previous tutorial, and try to run your client app, you will see that the doctor category is still empty, well because we still haven't imported the doctor category into our Firestore Database,
we will also setup `admin email & password` that you will use when you want to log in on the `Hallo Doctor Web Admin Dashboard`

- To setup doctor category & admin credentials, open `Command Prompt` in folder `/Halo_Doctor_Cloud_Function_Firebase/functions`
- inside `/functions` folder run
  
```npm
npm run setup-firebase
```

- you will get prompted to `Do you want to setup Admin Email & Password` type **Y** and then enter

![plop1](./assets/plop1.png)

- and then `Do you want to add default Category in database, you can change it later in Admin Dashboard` type **Y** enter

![plop1](./assets/plop2.png)

:::info

later if you wanto change the admin dashboard password, you can just repeate the proccess, but in this step you will need to choose no, but now just choose yes

:::

- You'll get prompted to enter the path to you service account key file, To generate it, go to your `Firebase Dashboard`, `Project settings` tab and then to `Service accounts` option

![Flutter Doctor](./assets/service1.PNG)

- after downloading it you can directly enter the path in the command line earlier, or more easily put your service account file in the `/functions` folder, and you just have to type the service account file name in command line

![Flutter Doctor](./assets/cmd1.PNG)

- after that you have to enter your database url, you can get it on the same page when you download your service account

![Flutter Doctor](./assets/service3.PNG)

![Flutter Doctor](./assets/cmd2.PNG)

- Next you have to enter your `email address` and `password` that will be used to login to your web admin dashboard

:::caution

make sure the password is six characters or more, and make sure you remember the `email & password`

:::

if everything goes well, the doctor category should have been added and the admin credentials to login to the web admin should have been setup

Next we will setup the Web admin dashboard
