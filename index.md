---

copyright:
  years: 2015, 2017, 2018
lastupdated: "2018-01-09"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}
{:javascript: .ph data-hd-programlang='javascript'}
{:java: .ph data-hd-programlang='java'}
{:python: .ph data-hd-programlang='python'}
{:swift: .ph data-hd-programlang='swift'}

# Building Mobile apps on {{site.data.keyword.cloud_notm}}
{: #about}

You can manage your Mobile apps and the services that are integrated with the mobile app through the concept of a Mobile Developer Console *Project*. You can create a Project using the [Mobile Developer Console](https://console.bluemix.net/developer/mobile). The Mobile developer console brings in most commonly used services, starters, and capabilities for building mobile apps into one continuous experience that is optimized for the developer.

The {{site.data.keyword.cloud_notm}} mobile developer console enables a developer to create a project from a variety of starter kits, create and connect key {{site.data.keyword.cloud_notm}} services to your project, and quickly download working code with SDKs. The SDKs are fully integrated with capability credentials or dependencies that enable you to have it running in minutes. When your application is running and you have set up and configured capabilities, you can return to your project to monitor and manage engagement with your application users. You can also configure and manage your services through the {{site.data.keyword.dev_console}}.

The downloaded starter app code can become a starting point for your new mobile app. If you are integrating {{site.data.keyword.cloud_notm}} services into an existing mobile app, the downloaded code serves as a reference code to help you integrate with {{site.data.keyword.cloud_notm}} services.


## Projects
{: #projects}

The {{site.data.keyword.cloud_notm}} Mobile developer console combines the data, and services for the mobile app in a complete *project*. By creating a project, all of the required parts of your app and the added services are maintained on the {{site.data.keyword.cloud_notm}} server. You can download your app starter code and the required **credentials** and initialization code for the services that are configured into your project. You can view all of your projects by selecting **Projects**.  

You can view additional information about a single project by selecting it on the **Projects** page. This displays the **Project Overview** page, which includes the services that are associated with the project. Services are separate capabilities that extend your app by adding a function. Because they are added individually, you can add the services that you need, like Push services, authentication, analytics, or other services. When you add a service to your project on the **Project Overview** page and follow the instructions to configure it, it is automatically associated with your app.


### Project Overview page
{: #project_overview}

Once you have logged on, you can view and work with a single Mobile project by selecting the project on the **Projects** page, which opens the Project Overview page.
{: shortdesc}

The **Project Overview** page displays an entry for each service that is configured for the selected project. For each service entry bound to your projetc, you will see its name, a link for further documentation, and an *actions* button with three vertically-aligned dots. The *actions* button options are to remove service from project, open dashboard for service, and delete service. Please note that removing a service instance only removes the association to this project and does not delete the service instance.

The Project Overview page also allows you to add new services to your project. The available services are dependent on the type of project and the services that are available in that region, so not all services will be available to associate with all projects.

For convenience, the credentials for the services associated with your project are shown on the **Project Overview** page under the **Credentials** section.

Select **Download Code** to generate and download the code for your project. For more information about downloading the code, see [Get code](https://console.bluemix.net/docs/cloudnative/get_code.html).

Also, note that you can deploy your project to {{site.data.keyword.cloud_notm}} by clicking on the *Create Toolchain* button.


## Starter kits
{: #starters}

You can choose from a variety of starter kits that are available that demonstrate a popular mobile app pattern.

Starter kits are optimized to be production ready starter code that focuses on demonstrating a key pattern implementation using a particular mobile platform (e.g. Android, iOS or Cordova). In some cases, starters offer a simple user experience to highlight the integration of the service, data or interactions with the user. Each starter can be configured to be enabled with Authentication, Data, and possibly other capabilities, if you decide to configure them for your project. In other words, high-value services can be added to projects you create from starter kits.


## Services
The Project generate scaffolding code from the starter kit for the services listed under the **Services** page. If you choose to associate any of the services listed on that page with your application, you can then download code that includes scaffolding code for accessing those services from the application.

{: tip}
{: shortdesc}
