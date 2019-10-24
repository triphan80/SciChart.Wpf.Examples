

# SciChart.WPF.Examples
## Branch Structure

> **NOTES:** 
>  - [Master branch contains v4, v5 examples](https://github.com/ABTSoftware/SciChart.Wpf.Examples/tree/master). 
>  - For SciChart WPF v6 Examples, please use [branch SciChart_v6_Release](https://github.com/ABTSoftware/SciChart.Wpf.Examples/tree/SciChart_v6_Release)

## What's in this Repo? 

We've taken the SciChart WPF v5 Examples and retrofitted SciChart WPF v6 SDK beta into them to test backward compatibility. 

**This branch should not be used for your usage of SciChart, It is intended for the SciChart team to test breaking changes in SciChart SDK v6 and to demonstrate those changes to our users.** 

## Note: NuGet feed setup

To build, you will need to set the correct NuGet feeds for SciChart WPF v4.x and v5.x. 
NuGet Feed setup instructions are found at the page [Getting Nightly Builds with NuGet](http://support.scichart.com/index.php?/Knowledgebase/Article/View/17232/37/getting-nightly-builds-with-nuget)


> *Add these feeds to Visual Studio -> Tools -> Options -> NuGet Package*
> *Manager -> Package Sources to ensure you can get nightly builds:*
> 
> -   ***Name:** SciChart* 
> -   ***Source:**  [https://www.myget.org/F/abtsoftware/api/v3/index.json](https://www.myget.org/F/abtsoftware/api/v3/index.json)*
> -   ***Name:** SciChart Bleeding-Edge (Beta/Alpha packages)*
> -   ***Source:**  [https://www.myget.org/F/abtsoftware-bleeding-edge/api/v3/index.json](https://www.myget.org/F/abtsoftware-bleeding-edge/api/v3/index.json)*

![How to add NuGet Feeds to Visual Studio](http://www.scichart.com/wp-content/uploads/2015/05/ToolsOptionsNuget.png)
