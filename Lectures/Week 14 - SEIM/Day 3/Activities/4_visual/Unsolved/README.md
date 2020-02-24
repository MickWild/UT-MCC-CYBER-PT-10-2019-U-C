## Student Activity: Visualizing Data from Firewall Attack Logs

### Instructions

Welcome to the Final Activity!  You may select a teammate to work with you on this exercise.

Your team has prepared a **statistical report** for The Customer's digital forensics case. You started by investigating *firewall attack log* event data that was collected for several years.  Now, you are asked to summarize the report details for the company's highest management team.  You will create two *charts* and *map* to visualize your digital forensics results.

In this activity, you will use the `fortinet_logs_new.csv` file and create visual elements that will be added to a dashboard.

* Work with your teammate to **duplicate this dashboard** for the displaying information about the top attacker. Please ask your TA for assistance if you need help.

   ![Images/visual-18.png](Images/visual-18.png)


* First, upload the `fortinet_logs_new.csv` file into Splunk.

#### Create a visual using the following elements: 

**Time chart**

* Create a **timechart** for the top `source IP` for the **DOS attacks by month**.

    * Hint: Here is the start of the `timechart` command:
    
      ` | timechart count as ....`

* **Add the timechart** to a Dashboard called `Fortinet Research Dashboard`.

* Change the titles to:

   * Title: `Oracle.9i.TNS.OneByte.Dos`

   * Title: `Cluster Map`

**Attack Count**   

* Generate the `count` (420) using the `stats` command.

* **Add the count** to the dashboard.

**Map**

* Next, generate a `map` for only the top source IP. 

   * Hint: Use the `iplocation` and `geostats` commands

* **Add the map** to the dashboard.

**Area Chart**

* Generate an area chart that displays the **targets** of the attack for the source IP address.

* **Add the area chart** to the dashboard. 

   * Hint: This should use a `timechart` using the destination IP and then `sort` descending by destination IP.

**User Interface**   

* Change the **color** of the `count` to red.

* Change the **background** for the dashboard.

* **Arrange the panels** as shown in the example.

* Where are the attacks originating? 


### Activity Complete!