[title]: # (Thycotic One Team Cloud Subscriptions)
[tags]: # (Thycotic One, Cloud Manager)
[priority]: # (1000)

# Team Subscriptions

*Subscriptions* are SSC instances.  Products are essentially the exact same thing for Thycotic cloud products other than SSC, such as Privilege Manager Cloud, DevOps Vault, and Account Lifecyle Manager.

> **Note:** The reason there are two names for nearly the same thing is they came from separate legacy development paths. We intend to combine them in a future Cloud Manager release.

## Viewing and Editing Team Subscriptions

> **Note:** The Cloud Manager dashboard provides a much quicker way to view team subscriptions.

1. Log on to your Cloud Manager at `portal.thycotic.com`.

1. Click the **Manage** link and select **Teams**. The Teams page appears.

1. Click the **Subscriptions** button for the desired team. The Subscriptions page appears:

   ![image-20200825114114096](images/image-20200825114114096.png)

1. To view a list of the cloud subscriptions, click the **Details** button. The Subscriptions Details page appears:

   ![image-20200825114246407](images/image-20200825114246407.png)

   We see that the team is listed under Subscription Name, and the subscriptions are for SSC Connection Manager and the SSC platform.

1. To edit the subscriptions, click the **Edit** button. The Subscription popup appears:

   ![image-20200825114412200](images/image-20200825114412200.png)

1. If desired, type the new hostname in the **Name** text box.

   > **Important:** If you change the cloud hostname, any distributed engines you have connected to your cloud instance will continue to contact the old hostname. Any distributed engine functionality, like password changing and discovery, will no longer work. To fix this, uninstall, re-download, and reinstall any distributed engines you have  deployed.

1. If desired, type the new subdomain name in the **Subdomain** text box.

1. Click the **Save** button.

## Editing the Subdomain

See [Viewing and Editing Team Subscriptions](#viewing-and-editing-team-subscriptions).

## Linking to an Instance

## Listing Cloud Subscriptions

See [Viewing and Editing Team Subscriptions](#viewing-and-editing-team-subscriptions).

## Listing Hostnames

See [Viewing and Editing Team Subscriptions](#viewing-and-editing-team-subscriptions).

