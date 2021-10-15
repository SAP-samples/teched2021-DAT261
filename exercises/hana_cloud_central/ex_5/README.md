# Exercise 5 - Start, Stop, Upgrade Instances, and Other Actions

In this section we will discuss about how to Start and Stop the databases from the SAP HANA Cloud Central Overview page. On clicking the More(...) button under the Actions column for any type of instance, we see a Stop option to stop the particular instance


1. Click on "..." button.

<br>![](/exercises/ex_5/images/1.png)

2. Click on Stop. A pop up shows up, confirming if you want to continue with stopping the instance. If yes, click on Stop button.

<br>![](/exercises/ex_5/images/2.png)

3. On the Overview page, you can see that the status for instance you just stopped has changed to 'Stopping'. Click on the hyperlink status to see more details on the status.

<br>![](/exercises/ex_5/images/3.png)

<br>![](/exercises/ex_5/images/4.png)


4. Now let us Start an instance that has been already Stopped. Click on More(...) button under the Actions column

<br>![](/exercises/ex_5/images/5.png)

5. Click on Start. We can see that the instance has moved to status Starting. And on clicking the Starting hyperlink we see details on the date and time when the instance was initiated and updated.

<br>![](/exercises/ex_5/images/9.png)

<br>![](/exercises/ex_5/images/10.png)

<br>![](/exercises/ex_5/images/11.png)

6. We also have another option that allows us to Upgrade the SAP HANA instance. We can find this option under the Actions list. Click on Upgrade button under Actions column if there is any upgrade available.

<br>![](/exercises/ex_5/images/6.png)

7. A pop up appears saying that a new revision for the instance is available and if we want to continue with the Update process. If you would like an update now, click on Update button else click on Cancel to quit from the pop up. Click on Cancel for now.

<br>![](/exercises/ex_5/images/7.png)

8. Let us now have a look at an SAP HANA instance that already has a Data lake instance associated with it. When you see the Actions list for such an SAP HANA instance, you can notice that Add Data lake option is not available. When there is no data lake associated, you can see Add Data Lake option in the Action list.

<br>![](/exercises/ex_5/images/8.png)

9. Now let us talk about the other Actions available for each of the instance. Click on More (...) button under the Actions column for an SAP HANA instance. Click on Open in SAP HANA Cockpit option in the Actions list. We can directly open the SAP HANA Cockpit to administer the SAP HANA instance from the SAP HANA Cloud Central page.

<br>![](/exercises/ex_5/images/12.png)

10. SAP HANA Cockpit is opened in an adjacent new tab. Here enter the valid Username and Password for the instance. Click on Ok. Once the credentials are validated, we are at the SAP HANA Cockpit Database Overview page, where in we can perform various monitoring and administrating operations on our HANA instance.

<br>![](/exercises/ex_5/images/13_a.png)

<br>![](/exercises/ex_5/images/13_b.png)

11. We can also open the SAP HANA Database Explorer to create SQL scripts, run them and also administer the SAP HANA instance directly from the Cloud Central page. Click on Open in SAP HANA Database Explorer option in the Actions list for an SAP HANA instance. SAP HANA Database Explorer is opened in an adjacent new tab. 

<br>![](/exercises/ex_5/images/14_a.png)

<br>![](/exercises/ex_5/images/14_b.png)

12. Get back to the Cloud Central Overview page and choose the Actions list for an SAP HANA instance again. Now click on Open SQL Console option. SAP HANA Database Explorer opens up in a new tab, but this time with an SQL Console already opened.

<br>![](/exercises/ex_5/images/15_a.png)

<br>![](/exercises/ex_5/images/15_b.png)

13. Let us now explore the actions for a Data lake instance. Click on More(...) button under the Actions column corresponding to a Data Lake instance. First is the Manage File Container. Click on it. You can edit the configuarations and click on save.

<br>![](/exercises/ex_5/images/16.png)

<br>![](/exercises/ex_5/images/17.png)

<br>![](/exercises/ex_5/images/18.png)

16. Copy SQL Endpoint functionality - On clicking this, the SQL endpoint is copied to the clipboard. Click on Copy SQL Endpoint.

<br>![](/exercises/ex_5/images/19.png)

14. We get a success message saying that the SQL endpoint is copied to the clipboard.

<br>![](/exercises/ex_5/images/20.png)

15. Next is the Copy Instance ID option - This will help us copy the instance id to the clipboard. This function is similar to the previous copy option we discussed. On clicking Copy Instance ID option, we get a success message.

<br>![](/exercises/ex_5/images/21.png)

<br>![](/exercises/ex_5/images/22.png)

16. Click on Copy Configuration. A popup open with options to copy configuration to clipboard or download it as a JSON file.

<br>![](/exercises/ex_5/images/23.png)

<br>![](/exercises/ex_5/images/24.png)

17. Copy Files Rest API Endpoint- copies it to the clipboard.

<br>![](/exercises/ex_5/images/25.png)

<br>![](/exercises/ex_5/images/26.png)

18. Other Copy options help in directly copying the Landscape Id, Port ID, Coordinator Endpoint and Worker. You can find these options in the Actions list for a Data Lake instance. All the IDs are directly copied to the clipboard.

<br>![](/exercises/ex_5/images/27.png)


Continue to - [Exercise 6 - Delete Instances ](../ex_6/README.md)