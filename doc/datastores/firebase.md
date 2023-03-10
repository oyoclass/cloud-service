## Firebase

Firebase is a cloud development platform offered by Google. Firebase is a large and expansive service that can do many things, but one of the modules offered is a realtime database that can be accessed remotely.

This is a step-by-step guide on setting up your own free Firebase realtime database instance.

### Creating an Account

<div class="notebox notebox-info">
    <p class="notebox-title">
        Note
    </p>
    <p>
        If you already have a Google account, then you can skip to the <b>Creating a Project</b> section.
    </p>
    <p>
        You will need a working phone number to recieve a confirmation text to create a Google account.
    </p>
</div>

To use Firebase, you must have a Google account. So the first thing we need to do is create one. Click on the **Get started** button and you will be brought to the Google sign in page:

<img src="../../assets/img/firebase/get-started.png" width="400px">

Then, click on the **Create Account** button:

<img src="../../assets/img/firebase/create-account1.png" width="400px">

In the menu that appears, click **For My Personal Use**:

<img src="../../assets/img/firebase/create-account2.png" width="200px">

Fill out this info, then click **Next**:

<img src="../../assets/img/firebase/create-account3.png" width="300px">

Enter your phone number, then click **Next**:

<img src="../../assets/img/firebase/create-account4.png" width="400px">

After you verify your phone number, you will be asked for your birthdate. After you enter it and agree to Google's terms of service, you now have a fully functioning Google account, and can create a Firebase project!

### Creating a Project

Before we create a database, we need to create a **project** for it to be associated with. Click on **Create a project**:

<img src="../../assets/img/firebase/create-project1.png" width="400px">

Then in the next page, decide on a name and click **Continue**:

<img src="../../assets/img/firebase/create-project2.png" width="400px">

### Creating a Realtime Database

Now that we have a project, we need to add a realtime database to it. In your web browser, on the left side of your screen, find the **Build** section and click on **Realtime Database**:

<img src="../../assets/img/firebase/rtdb.png" width="200px">

On the next page, click on **Create Database**:

<img src="../../assets/img/firebase/create-database1.png" width="300px">

In the window that pops up, we won't need to change anything. Click on **Next**:

<img src="../../assets/img/firebase/create-database2.png" width="400px">

Then click on **Enable**:

<img src="../../assets/img/firebase/create-database3.png" width="400px">

Congratulations! Your database is now set up and ready to use! You will need to download the credentials JSON for your project to connect to it from your programs. You can read about how to get your Firebase realtime database working with Python3 Editor in the [Python3 Editor Docs](https://docs.oyoclass.com/python3editor/)
