---
author: buck1ey
---



# Review links

There are multiple ways to find review links to content in branches you are working in. This is useful if you are editing content in GitHub and want to see how it will look when live on docs.

Each time you commit a change, the build system ("OPS") generates a build, and provides review links. You can find these in build status emails that you receive when you commit a change. 

You can also navigate between branches on the review site to find your content.

## OPS build email

 When a build completes (or fails), the OPS system sends a status email message. The subject line for these messages will be similar to **[Succeeded With Warning] Open Publishing Build Service - Publish**. The text in the brackets can be "Succeeded", "Succeeded With Warning", or "Failed". These messages contain review links for pages that were successfully built.

 > [!div class="mx-imgBorder"]
 > ![Review links in build status email](media/review-email.png "Review links in build status email")

Click **View** to navigate to a review build of a particular page. 

If you aren't receiving build status emails, check your GitHub notification settings.

 1. Navigate to <https://github.com/settings/notifications>. You may need to log in to GitHub.

 2. Under **Email notification perferences**, verify the email address in **Default notification email**, and make sure **Include your own updates** is checked.

Also check your Outlook rules to make sure the messages aren't being blocked.

## Navigating the review site

Most of the time, you can use your browser to navigate to your review content.

 1. Navigate to a live topic in your docset (if possible, find the topic you'd like to review). For example [https://docs.microsoft.com/en-us/business-applications-release-notes/October18/index](https://docs.microsoft.com/en-us/business-applications-release-notes/October18/index).

 2. Prepend **review** to the topic URL. For example [https://**review**.docs.microsoft.com/en-us/business-applications-release-notes/October18/index](https://review.docs.microsoft.com/en-us/business-applications-release-notes/October18/index).

 3. Use the branch dropdown to select your branch.

 >[!div class="mx-imgBorder"]
 >![Branch dropdown](media/branch-dropdown.gif "Branch dropdown")

 > [!NOTE]
 > You can also edit the URL. Set the **branch=** parameter to your branch name.

 4.  If necessary, use the TOC to navigate to your topic.

