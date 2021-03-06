# Proinfocus XFDesigner on Mac
Getting started with Live XAML designing tool for Xamarin.Forms

### Getting started
*Steps for Server and Watcher:*
1. Make sure you have .Net Core 2.0 or above SDK installed on your machine
2. Download the **ServerWatcher.zip** and extract it to ~Desktop/ServerWatcher (or any location and follow along with that particular path)
3. From command-line/terminal from your location ie., ~/Desktop/ServerWatcher, run **./BUILD.command**
4. Once successfully done, you can run the server by running **./SERVE.command** command.
5. To start watching for file changes, go to the directory where you want the files to be watched.
6. Run the watcher command by typing **~/Desktop/ServerWatcher/WATCH.command**, it will start watching for files in that folder and its sub-folders.

> **Note:**
> Steps 1 to 3 is just one time for setup of the dependencies for the Server and Watcher tools.
> Subsequently, you will be using only step 4 thru 6 everytime you need to use the XFDesigner in your Xamarin.Forms


*Steps to integrate Proinfocus XFDesigner into Xamarin.Forms:*
1. Create or open your Xamarin.Forms project in Visual Studio for Mac or Rider.
2. Make sure the Xamarin.Forms nuget is at least version **3.0**
3. Download the **Proinfocus.XFDesigner** nuget from the private nuget location: http://nuget.proinfocus.com/nuget
4. Once done, build the project and add make necessary changes in your **App.xaml.cs** file as given in the example below.
5. Build and run the project with or without debugging, and start making changes.
6. The changes in the XAML file will be instantly rendered on the device or emulator, if everything is rightly setup.

### Sample App.xaml.cs file
```C#
public App()
{
    InitializeComponent();

    var fallBackPage = new MainPage(); //If using Shell, it would be new AppShell();

    // If you want to design, uncomment the following 3 lines and make sure, the url is working.

    //string url = "http://127.0.0.1:12345/xaml";
    //var designer = new XFConnection(this, url, fallBackPage);
    //designer.Start();

    // if you want to use the app without designer, uncomment following line
    
    // MainPage = fallBackPage;
}
```
