# Getting Started with Rating sample
Step 1: Add the NuGet to the project and add the namespace as shown in the following code sample:

**[XAML]**

```
xmlns:rating="clr-namespace:Syncfusion.Maui.Inputs;assembly=Syncfusion.Maui.Inputs"
```
**[C#]**

```
using Syncfusion.Maui.Inputs;
```
Step 2: Then initialize an empty SfChipGroup as shown in the following code:

**[XAML]**

```
<rating:SfRating x:Name="rating" />
```
**[C#]**
```
SfRating rating;
public MainPage()
{
    InitializeComponent();
    rating = new SfRating();
    this.Content = rating;
}
```

# How to modify space between each rating item

To modify the space between each rating item in a .NET MAUI SfRating control, you can use the ItemSpacing property.

**[XAML]**

```
<editors:SfRating ItemCount="5" ItemSpacing="50" />
```

**[C#]**

```
public MainPage()
{
    InitializeComponent();
    rating = new SfRating();
    this.Content = rating;
    this.ItemSpacing = 50;
    this.ItemCount = 5;
}
```
## How to run this application?

To run this application, you need to first clone the How-to-modify-space-between-each-rating-item repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.
