# Desk.com Canvas: Example Canvas Metrics
This is an example Desk.com Canvas application that displays the Resolution Time metrics for a case. It serves as a demonstration of how Canvas can be used to display case metrics to the agent in real time. 

## I. Deploy the Application
First, install this application by deploying the source code to your Heroku account. To deploy your application, simply click this button:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https%3A%2F%2Fgithub.com%2Fdesklabs%2Fcanvas-report%2Ftree%2Fmaster)

## II. Create the Integration URL
Now that you have the application on Heroku, go ahead and create the integration URL.

1. In the **Name** field, add a title for the this application. In this example, we’ll use 'Canvas Report'.

2. The **Description** field, though optional, is a way to give a general description of the integration URL.

3. Select 'Canvas iFrame' from the **Open Location** dropdown.

4. Toggle the **Enabled** button to 'Yes' and select the [Permission level](https://support.desk.com/customer/portal/articles/1146981?b_id=7112&t=568640).

5. Click the **Update** button.

## III. Add it to your Case Layout
Now display the canvas application on your Case Layout.

1. **Go to Cases >> Next Gen Case Layouts**

2. Find the **Create an Article from your Draft** canvas application in the **Integrations** section on the right side of the screen.

3. **Drag** and **Drop** the application in your case layout.

4. Scroll over the left side of the 'Canvas Report' bar and click on the gear to open the **Edit** window. Adjust the pixel **Height** to **220** and **Position**, the order in which it appears in Case Details on the dashboard. Click **Save**.

## IV. Dashboard Confirmation
After you have added the canvas application to your layout and selected users, open a ticket and you should see the Time Tracker under **Case Details**.


