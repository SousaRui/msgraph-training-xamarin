# Completed module: Add Azure AD authentication

The version of the project in this directory reflects completing the tutorial up through [Add Azure AD authentication](https://docs.microsoft.com/graph/tutorials/xamarin?tutorial-step=3). If you use this version of the project, you need to complete the rest of the tutorial starting at [Get calendar data](https://docs.microsoft.com/graph/tutorials/xamarin?tutorial-step=4).

> **Note:** It is assumed that you have already registered an application in the Azure portal as specified in [Register the app in the portal](https://docs.microsoft.com/graph/tutorials/xamarin?tutorial-step=2). You need to configure this version of the sample as follows:
>
> 1. Rename the `./GraphTutorial/GraphTutorial/Models/OAuthSettings.cs.example` file to `OAuthSettings.cs`.
> 1. Edit the `OAuthSettings.cs` file and make the following changes.
>     1. Replace `YOUR_APP_ID_HERE` with the **Application Id** you got from the Azure portal.
> 1. In the **GraphTutorial.iOS** project, open the `Info.plist` file.
>    1. On the **Advanced** tab, locate the **URL Types** section. In the **URL Schemes** value, replace `YOUR_APP_ID_HERE` with the **Application Id** you got from the Azure portal.
> 1. In the **GraphTutorial.Android** project, open the `Properties/AndroidManifest.xml` file.
>     1. Replace `YOUR_APP_ID_HERE` with the **Application Id** you got from the Azure portal.
