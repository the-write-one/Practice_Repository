# Getting started

Looking to get acquainted with the Grafana? You’ve come to the right place. Grafana is the open source analytics and monitoring solution for every database. 

The information in this guide assumes you have a working Grafana server up and running. To install Grafana, see the [Installing Grafana](https://grafana.com/docs/installation/) guide.

## Logging in 

Grafana asks you to change your password when you log in for the first time. Choose a strong password at least 8 characters in length, including numbers, symbols, and uppercase and lowercase letters.

To start Grafana for the first time:

1. Open your browser and go to [http://localhost:3000](http://localhost:3000/). 
    The link directs you to the login page. The default http port for Grafana is 3000. Use port 80 to [configure an alternative port](https://grafana.com/docs/installation/configuration/#http-port/). 
3. Type **admin** as the default username.
4. Type **admin** as the default password and click **Log In**. 
5. Follow the prompt and change the **admin** password to a specialized password.
6. Click **Save**.

## Changing your password and user name
You can change the password and user name after the initial login. 
1. Click the **admin** icon located on the bottom left of your **Home Dashboard** screen.
2. Click **Preferences**. Type your new username in the **Username** dialog box.
3. Click the **Change Password** tab to change your password.
4. Type your old password in the dialog box. Type a new password and confirm your new password.
5. Click **Change Password**.

Video 1: Logging in and changing user name and password 

## Adding a data source
A data source is needed before you can create your first dashboard. There are multiple ways to add a data source. The quickest way to add your data source is to:

1. Click the cog icon.
    If the side menu is not visible, click the Grafana icon in the upper left corner.
2. Click the green **Add data source** box. 
    Alternatively, you can add data sources by hovering the mouse over the cog icon until the **Configuration** menu appears and click **Data Sources**.
3. Select a data source from the list.
    In this example we use MySQL as the data source.
![Figure 3: Menus for Adding Data Sources](https://drive.google.com/drive/folders/1wovGePmYMxPViUo0KKVmCR9sQUoJ_6iM)

## Naming the data source
It’s time to name your newly created data source.

1. Type a name for your new data source in the **Name** field. 
    In the this example we’ve named the MySQL data source Hugo.
2. View [Supported data sources](https://grafana.com/docs/features/datasources/#supported-data-sources/)  for more information about how to configure your data source.
3. Click **Save and Test** after the data source is configured.
    If you click **Save and Test** before configuring your data source an error will appear.

Figure 2: Adding and naming the data source 





