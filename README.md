# XFDesigner
Live XAML designing tool for Xamarin.Forms

For simplicity and separation of platform, the tools and descriptions are maintained based on the Windows and Mac operating systems and the details of setup will be available via platform specific documents.

## What is XFDesigner?
It is a live XAML design renderer on real devices/emulators of Android and iOS phones and tablets. You could instantly see the changes on one or all the setup devices/emulators, simultaneously.

Checkout the sample video on YouTube:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Rk0aBlaLld8/0.jpg)](https://www.youtube.com/watch?v=Rk0aBlaLld8)

## FAQs
### Time required to setup?
You will be able to setup and start using it in under 5 minutes. 

### What IDE/Editor can be used?
As long as you are connected with Server, Watcher and the deployed app, you can use any IDE/Editor to design your XAML from. It has been tested with Visual Studio, Visual Studio for Mac, Visual Studio Code, Rider, Notepad and they all work seamlessly.

### Does it work for Code Behind?
As the name suggests, it works only for the XAML part. Changes in the code behind can only be used in the XAML designing, once you build and re-deploy the project.

### Does it work with ViewModels?
Absolutely, if you have viewmodels created and deployed, then you can use those in the XAML designing and bind to your controls and see them rendered.

### Can I intereact with the devices while designing?
Yes, the changes are live and they work as if it was actually deployed on the device.

### Why changes do not show when used as templates or internal views?
The XAML designs are persisted on your machine and rendered to your device temporarily, hence you can't see the changes when the files are rendered within other containers as views or templates. However, if you build and re-deploy the app, you will see the changes persisted on the device.

### What to do when I am done with XAML designing?
Once you are doing using the live XFDesigner, just restore your App.xaml.cs file to its actual state and remove the dependent nuget package ie., Proinfocus.XFDesigner. Now, you can buid your app and deploy it without any trace of the live designer or its dependencies.


# License
You are free to use it for your personal projects, educational purpose or any other non-commercial projects.
However, if you are using it in commercial projects, you need to buy usage license by paying a nominal fee for lifetime use.


# Contribution
You can show your appreciation for this project by donating via

[![Donate via Paypal](https://www.paypalobjects.com/webstatic/en_US/i/buttons/PP_logo_h_200x51.png)](https://www.paypal.me/rahulhadgal)
