# XFDesigner
Live XAML designing tool for Xamarin.Forms

For simplicity and separation of platform, the tools and descriptions are maintained based on the Windows and Mac operating systems and the details of setup will be available via platform specific documents.

## What is XFDesigner?
It is a live XAML design renderer on real devices/emulators of Android and iOS phones and tablets. You could instantly see the changes on one or all the setup devices/emulators, simultaneously.

## FAQs
### Time required to setup?
You will be able to setup and start using it in under 5 minutes.

### Does it work for Code Behind?
As the name suggests, it works only for the XAML part. Changes in the code behind can only be used in the XAML designing, once you build and re-deploy the project.

### Does it work with ViewModels?
Absolutely, if you have viewmodels created and deployed, then you can use those in the XAML designing and bind to your controls and see them rendered.

### Can I intereact with the devices while designing?
Yes, the changes are live and they work as if it was actually deployed on the device.

### Why changes do not show when used as templates or internal views?
The XAML designs are persisted on your machine and rendered to your device temporarily, hence you can't see the changes when the files are rendered within other containers as views or templates. However, if you build and re-deploy the app, you will see the changes persisted on the device.
