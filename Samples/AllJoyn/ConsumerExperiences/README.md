---
page_type: sample
languages:
- csharp
products:
- windows
- windows-uwp
urlFragment: AllJoynConsumerExperiences
extendedZipContent:
- path: SharedContent
  target: SharedContent
- path: LICENSE
  target: LICENSE
- path: Samples/AllJoyn/Common
  target: Common
- path: Samples/AllJoyn/shared
  target: shared
description: "Creates an AllJoyn Windows Universal app using Code Generation with Introspection XML and Windows.Devices.AllJoyn."
---

<!---
  category: DevicesSensorsAndPower
  samplefwlink: http://go.microsoft.com/fwlink/p/?LinkId=534021
--->

# AllJoyn consumer experiences sample

Shows how to create an AllJoyn Windows Universal app using Code Generation with Introspection XML and Windows.Devices.AllJoyn.

> **Note:** This sample is part of a large collection of UWP feature samples. 
> You can download this sample as a standalone ZIP file
> [from docs.microsoft.com](https://docs.microsoft.com/samples/microsoft/windows-universal-samples/alljoynconsumerexperiences/),
> or you can download the entire collection as a single
> [ZIP file](https://github.com/Microsoft/Windows-universal-samples/archive/master.zip), but be 
> sure to unzip everything to access shared dependencies. For more info on working with the ZIP file, 
> the samples collection, and GitHub, see [Get the UWP samples from GitHub](https://aka.ms/ovu2uq). 
> For more samples, see the [Samples portal](https://aka.ms/winsamples) on the Windows Dev Center. 

Specifically, this sample covers:

**Scenario 1**
-   Creating and launching a Secure AllJoyn Consumer.
-   Implementing method call, property and signal from generated code.

**Scenario 2**
-   Discovering and connecting to an Onboardee's SoftAP.
-   Implementing method calls to get an Onboardee's network scan, configuring an Onboardee with WiFi credentials etc.

**Note** The Universal Windows samples require Visual Studio to build and Windows 10 to execute.
 
To obtain information about Windows 10 development, go to the [Windows Dev Center](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio and the tools for developing Windows apps, go to [Visual Studio](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Samples

* [AllJoyn Producer Experiences](http://go.microsoft.com/fwlink/p/?LinkId=534025)
* [AllJoyn Consumer Experiences](http://go.microsoft.com/fwlink/p/?LinkID=534021)
* [AllJoyn Consumer Experiences](/archived/AllJoyn/ConsumerExperiences/) for JavaScript (archived)

The AllSeen Alliance has samples in [Windows SDK](https://allseenalliance.org/developers/download)

### Reference

[MSDN Reference](https://msdn.microsoft.com/library/windows/apps/windows.devices.alljoyn.aspx)  
[AllJoyn Reference](https://allseenalliance.org/developers/develop/api-reference)  
[Troubleshooting AllJoyn blog](http://channel9.msdn.com/Blogs/Internet-of-Things-Blog/Troubleshooting-AllJoyn-with-Windows-10-Insider-Preview-Builds)  

## System requirements

* Windows 10

## Build the sample

1. Start Microsoft Visual Studio and select **File** \> **Open** \> **Project/Solution**.
2. Go to the directory to which you unzipped the sample. Then go to the subdirectory containing the sample in the C# language. Double-click the Visual Studio Solution (.sln) file. 
3. Set the active solution configuration and platform to the desired values under **Build** \> **Configuration Manager**.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**. 

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 