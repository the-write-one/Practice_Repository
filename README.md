# Practice_Respository
A sandbox for playing
# Getting started

Looking to get acquainted with Grafana? You’ve come to the right place. The information in this guide assumes you have a working Grafana server up and running. To install Grafana, see the {Installing Grafana](https://grafana.com/docs/installation/) guide.

## Logging in for the first time 

You will be asked to change your password when you log in for the first time. We encourage you to choose a strong password with at least 8 characters in length including, numbers, symbols, uppercase and lowercase letters.

To run Grafana:

1. Open your browser and go to [http://localhost:3000](http://localhost:3000/). The link directs you to the login page. The default http port for Grafana is 3000. Use port 80 to configure an alternative port. 
2. Type **admin** as the default username.
3. Type **admin** as the default password. 
4. Change your password when logging in for the first time.

	After the initial login, you can change your password and username by clicking the **admin** icon located on the bottom left of your screen and choosing **Preferences** or **Change Password**.

Figure 1: 

## Adding a data source
A data source is needed before you can create your first dashboard. There are multiple ways to add a data source. The quickest way to add your data source is to:

1. Click the cog icon.
If the side menu is not visible click the Grafana icon  in the upper left corner.
2. Click the green **Add data source** box. 
Alternatively, you can add data sources by hovering the mouse over the cog icon until the **Configuration** menu appears and click **Data Sources**.
3. Select a data source from the list.
In this example we use MySQL as the data source.
![Figure 3: Menus for Adding Data Sources](https://drive.google.com/drive/folders/1wovGePmYMxPViUo0KKVmCR9sQUoJ_6iM)


Figure 2: Menus for Adding Data Sources

## Naming the data source
It’s time to name your newly created data source.

1. Type a name for your new data source in the **Name** field. 
In the following example we’ve named our MySQL data source Hugo.
2. View [Supported data sources](https://grafana.com/docs/features/datasources/#supported-data-sources/)  for more information about how to configure your data source.
3. Click **Save and Test** after the data source is configured.
If you click **Save and Test** before configuring your data source an error will appear.

Figure 4: 



![A screen shot instructing you place http://localhost:3000/ the browser address bar. Includes the username and password fields. for logging into Grafana]

Figure 2: Admin Preferences
![A screen shot showing 
