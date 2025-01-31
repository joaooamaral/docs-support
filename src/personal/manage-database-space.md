---
summary: Personal environments can store up to 2GB on the database. This includes system and application data. Learn what you can do to take the most of it.
---

# Manage the database space of your personal environment

Personal environments have a database limit of 2GB. The database stores the following : 

* **System data**: The metadata used by the OutSystems Platform. This includes, for example, the applications definition, data model, module configurations, logs, and application versions. The system data usually increases as you develop and deploy your applications.

* **Application data**: The data your applications generate and manipulate. The application data usually increases as your users access your applications.

## Check how much database space you have

Go to your personal environment at `https://<yourpersonal>.outsystemscloud.com` and navigate to the **Environments** tab.

![](images/manage-database-space_0.png)

In this example only 13% of the available database storage space is being used.

To check how much space is being used for system data and application data,click the **View details** link.

![](images/manage-database-space_1.png)

Note that these metrics are updated every hour, so they might not represent the actual space you are using at the moment.

To clear database space in your Personal Environment, see [Best practices for a tidy and clean environment](https://success.outsystems.com/Documentation/Best_Practices/Lifecycle/Best_practices_for_a_tidy_and_clean_environment).
