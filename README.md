# Xamarin Busy Indicator (SfBusyIndicator)

This repository explains you the steps to configure a SfBusyIndicator control in a real-time scenario and also provides a walk-through on some of the customization features available in SfBusyIndicator control.

For know more details about BusyIndicator: https://www.syncfusion.com/xamarin-ui-controls/xamarin-busy-indicator

## Getting Started with Busy Indicator sample

Step 1: Add the NuGet to the project and add the namespace as shown in the following code sample:

**[XAML]**

```
xmlns:busyindicator="clr-namespace:Syncfusion.SfBusyIndicator.XForms;assembly=Syncfusion.SfBusyIndicator.XForms"

```
**[C#]**

```
using Syncfusion.SfBusyIndicator.XForms;

```

Step 2: Add the SfBusyIndicator control with a required optimal name by using the included namespace.

**[XAML]**

```
 <ContentPage.Content>
        <busyindicator:SfBusyIndicator x:Name="busyindicator"/>
 </ContentPage.Content>
```
**[C#]**
```
 public MainPage()
 {
    InitializeComponent();
    SfBusyIndicator busyIndicator = new SfBusyIndicator();
    this.Content = busyIndicator;
 }
```
## How to run this application?

To run this application, you need to first clone the xamarin.forms-busyindicator repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.