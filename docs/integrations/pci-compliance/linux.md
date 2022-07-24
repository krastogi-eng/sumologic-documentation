---
id: linux
title: PCI Compliance App for Linux
sidebar_label: Linux
---

This guide helps you set up Sumo Logic Collectors, install the PCI Compliance for application, and create dashboards from samples so you can begin monitoring your usage and determine if you are meeting Compliance benchmarks.


### Collect Logs for PCI Compliance for Linux
!1.gif "image_tooltip")

The PCI Compliance for Linux App works with your existing Linux logs to identify any compliance issues.

To collect Linux logs, you will need:

* An [Installed Collector](https://help.sumologic.com/03Send-Data/Installed-Collectors). Choose the one right for your host environment.
* A Linux [Source](https://help.sumologic.com/03Send-Data/Sources/01Sources-for-Installed-Collectors), depending on your environment.
    * [Local File Source](https://help.sumologic.com/03Send-Data/Sources/01Sources-for-Installed-Collectors/Local-File-Source)
    * [Remote File Source](https://help.sumologic.com/03Send-Data/Sources/01Sources-for-Installed-Collectors/Remote-File-Source)
    * [Syslog Source](https://help.sumologic.com/03Send-Data/Sources/01Sources-for-Installed-Collectors/Syslog-Source)


## Install the PCI Compliance for Linux App and view the Dashboards

### Install the Sumo Logic App
!2.gif "image_tooltip")

Now that you have set up collection, install the Sumo Logic App for PCI Compliance for Linux to use the preconfigured searches and [Dashboards](https://help.sumologic.com/07Sumo-Logic-Apps/16PCI_Compliance/PCI_Compliance_for_Linux/03PCI-Compliance-for-Linux-Dashboards#Dashboards) that provide insight into your data.

**To install the app:**

Locate and install the app you need from the **App Catalog**. If you want to see a preview of the dashboards included with the app before installing, click **Preview Dashboards**.

1. From the **App Catalog**, search for and select the app**.**
2. Select the version of the service you're using and click **Add to Library**.

!3.png "image_tooltip")
Version selection is applicable only to a few apps currently. For more information, see the [Install the Apps from the Library.](https://help.sumologic.com/01Start-Here/Library/Apps-in-Sumo-Logic/Install-Apps-from-the-Library)



1. To install the app, complete the following fields.
    1. **App Name.** You can retain the existing name, or enter a name of your choice for the app. 
    2. **Data Source.** Select either of these options for the data source. 
        * Choose **Source Category**, and select a source category from the list. 
        * Choose **Enter a Custom Data Filter**, and enter a custom source category beginning with an underscore. Example: (_sourceCategory=MyCategory). 
    3. **Advanced**. Select the **Location in Library** (the default is the Personal folder in the library), or click **New Folder** to add a new folder.
2. Click **Add to Library**.

Once an app is installed, it will appear in your **Personal** folder, or other folder that you specified. From here, you can share it with your organization.

Panels will start to fill automatically. It's important to note that each panel slowly fills with data matching the time range query and received since the panel was created. Results won't immediately be available, but with a bit of time, you'll see full graphs and maps.


### Dashboards
!4.gif "image_tooltip")



#### PCI Compliance for Linux - Account, User, System Monitoring
!5.gif "image_tooltip")


**Dashboard description:** This dashboard meets PCI Requirements 02, 07, 08 and 10 by monitoring user accounts and services. It presents information about user accounts created and deleted, stopped services, running services active services over time, unique services running, and running services, and more.

**Use case:** Use this dashboard to monitor administrative actions (create, delete users) performed by end users, ensure proper services are running on all systems, detect attempts to change the system time, and verify that critical systems are up and running.You can also monitor excessive failed login attempts to detect attempts to break into the system.

!6.png "image_tooltip")


#### PCI Compliance for Linux - Login Activity
!7.gif "image_tooltip")


**Dashboard description: **This dashboard meets PCI Requirements 02 and 10 by tracking login activity. It provides information about failed and successful user logins, and failed and successful super-user logins.

**Use case:** Use this dashboard to monitor access to the cardholder data environment. You can monitor failed and successful user logins.

!8.png "image_tooltip")


#### PCI Compliance for Linux - Privileged Activity
!9.gif "image_tooltip")


**Dashboard description: **This dashboard meets PCI Requirement 10. It provides information about total sudo attempts, failed sudo attempts, the top 10 users and hosts that have issued sudo attempts, recent sudo attempts, and sudo attempts over time.

**Use case:** Use this dashboard to monitor successful and failed access attempts to systems, especially with administrative privileges. It also helps monitor actions performed by users with administrative privileges.


!10.png "image_tooltip")