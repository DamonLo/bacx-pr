---
title: "View doc builds for your changes| MicrosoftDocs"
ms.date: 08/01/2018
ms.service: 
ms.topic: "conceptual"
author: "KumarVivek"
ms.author: "kvivek"
manager: "annbe"
---

# View doc builds for your content

Once your content is pushed to GitHub, our publishing system creates a doc build so that you can see your changes in the review site on docs.microsoft.com.


<!-- Is the following still correct? ops.microsoft.com ? Should they instead review content on the review site? 
Here's info on how to review content on the review site. We could put it here: 
https://microsoft.sharepoint-df.com/teams/Dynamics365CustomerEngagementEditingResources/_layouts/15/WopiFrame.aspx?sourcedoc={0ea74ded-c03c-452d-a0de-6c89d54f7107}&action=edit&wd=Dynamics_365_CE_Content-Review_site_%28staging%29-3OGLTtbgI4Ylazc0bz7NekdJ-48vsv13el4QebF20CpQirSTR

-->

You can manually see your build status and get your review links in **ops.microsoft.com**.

1. Browse to <https://ops.microsoft.com>.
2. Select **Sign in with GitHub**.
3. Provide your GitHub credentials to sign in.
4. In the OPS Portal, type the repo name where you made the change in the upper left corner. You can find the repo names here: [our repos](get-started.md#our-repos).
    
    For example, if the repo URL is https://github.com/MicrosoftDocs/flow-docs-pr, then your repo name is **flow-docs-pr** 

    ![](media/search-repo.png)

5. Select the repo name from the list below that exactly matches the name you typed, and then select the **Build history** tab to view all the doc builds.
6. Click on any of the builds from the list to expand it, and then look for the review link URL under the **Changes** > **Published URL**.

    ![](media/build-url.png)

