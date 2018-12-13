# Proinfocus XFDesigner on Windows
Getting started with Live XAML designing tool for Xamarin.Forms

### Getting started
*Steps for Server and Watcher:*
1. Make sure you have .Net Core 2.0 or above SDK installed on your machine
2. Download the **ServerWatcher.zip** and extract it to C:\ServerWatcher (or any location and follow along with that particular path)
3. From command-line/terminal from your location ie., C:\ServerWatcher, run **dotnet BUILD**
4. Once successfully done, you can run the server by running **SERVE** command.
5. To start watching for file changes, go to the directory where you want the files to be watched.
6. Run the watcher command by typing **C:\ServerWatcher\WATCH**, it will start watching for files in that folder and its sub-folders.

> **Note:**
> Steps 1 to 3 is just one time for setup of the dependencies for the Server and Watcher tools.
> Subsequently, you will be using only step 4 thru 6 everytime you need to use the XFDesigner in your Xamarin.Forms


*Steps to integrate Proinfocus XFDesigner into Xamarin.Forms:*
1. Create or open your Xamarin.Forms project.
2. Make sure the Xamarin.Forms nuget is at least version **3.4**
3. Download the **Proinfocus.XFDesigner** nuget from the private nuget location: http://nugets.proinfocus.com
4. Once done, build the project and add make necessary changes in your **App.xaml.cs** file as given in the example App.xaml.cs file in the repo.
5. Build and run the project with or without debugging, and start making changes.
6. The changes in the XAML file will be instantly rendered on the device or emulator, if everything is rightly setup.

