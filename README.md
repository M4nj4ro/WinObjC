#Welcome to the Windows Bridge for iOS project preview

##What is WinObjC?
WinObjC (also called the Windows Bridge for iOS) is a Microsoft open source project that provides an Objective-C development environment for Visual Studio/Windows. In addition, WinObjC provides support for iOS API compatibility.

The following sections will help you get started and you can view our wiki for more detailed information.

##Where to get it

Download the SDK [here](https://github.com/Microsoft/WinObjC/releases)

##Getting started with WinObjC
To use WinObjC, there are a few requirements. You need:
- Windows 10
- Visual Studio 2015 with Windows developer tools. Visual Studio 2015 Community is available for free [here](https://www.visualstudio.com/en-us/downloads/download-visual-studio-vs.aspx)

The best way to get started with WinObjC is to run one of the samples. We recommend starting with the **WOCCatalog** sample app, which demonstrates an assortment of iOS and XAML UI controls. To run the sample:

1. Extract the SDK zip file to a local directory

2. Navigate to *winobjc/samples/WOCCatalog* in the extracted directory

3. Double-click on *WOCCatalog-WinStore10.sln* to open in VS2015

4. In VS2015 right-click on the WOCCatalog (Universal Windows) project

5. Select **Set as StartUp project**

6. Use **Ctrl-F5** to build and run the app


For guidance about importing your own Xcode project and other SDK details, see the [wiki](https://github.com/Microsoft/WinObjC/wiki)


## What's still under development?
As this project is still under active development, there are a few features that are not yet built out:

1. x86 only today ARM support coming soon
2. Compiler optimizations will not work and will likely crash clang, debug builds only
3. Autolayout
4. Storyboard support
5. MapKit
6. AssetsLibrary
7. AddressBook
8. Ads
9. Objective-C annotations
10. Media Capture and Playback


##Problems?
If you have any questions, we're listening and will do our best to help. Just go to http://stackoverflow.com/ and tag your questions with **WinObjC**. You can also get more information at our [wiki](https://github.com/Microsoft/WinObjC/wiki)

##Directory structure

- bin/ : Various prebuilt tools
- build/ : Projects/solutions to build the SDK
- deps/ : Open source dependencies
	- prebuilt/ : Prebuilt binaries for various architectures
- Frameworks/ : Implementation of iOS-style Frameworks
- include/ : SDK headers (including headers for iOS-style Frameworks)
    - Platform/ : Headers for Windows Objective-C bindings for various OS versions
- msvc/ : Visual Studio integration files
- samples/ : Assorted samples
- tools/ : Source code to tools