<h1>CRM+SALES+OPPORTUNITY(TABLEAU)</h1>


<h2>Description</h2>
Using the same data file i used in excel, this project visually analyse some important informations using Tableau. I created a dashboard that visually analyse different informations at a go.
<br />


<h2>Data tools used</h2>

- <b>Tableau and Excel</b> 

<h2>Project walk-through:</h2>
</b>
  After the filtering and sorting of data using excel as clearly explained in the excel project. I imported the file into tableau and then use the data to visually analyse the following informations using a dashboard:
<br />
1) Total close value for all sales agent in every account. To know how well each sales agents are performing under every account </b>
<br />
2) Account with more than or equal to 30 lost opportunity in each region. To know the account that is having the most lost opportunity under every region  </b>
<br />
3) How many won, lost, still engaging and prospecting opportunity under each account  </b>
<br />
4) Most successful agent under each account  </b>
<br />
5) Number of opportunity responded to between 1-5days for every account in each region  </b>
<br />
<br />
I created a chart to analyse each of the problem listed, then created a dashboard from it. Below are all the charts with a clear guide on how all the charts are created: </b>
<br />
1) Total close value for all sales agent in every account. To know how well each sales agents are performing under every account </b>
<br />
<br />
<p align="center">
  Sum(close value) is used as the column and Sales agent as row </b>
  <br />
<img src="https://i.imgur.com/obH1s8Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
An account parameter was created to enable the selection of any account and get the total close value for sales agent of that account  </b>
<br />
<img src="https://i.imgur.com/IEA39jR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="initial">
2) Account with more than or equal to 30 lost opportunity in each region. To know the account that is having the most lost opportunity under every region  </b>
<br />
<p align="center">
  Count(deal_stage) is used as the column and Account as row </b>
  <br />
<img src="https://i.imgur.com/gJWCLkn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  <br />
  A region parameter is created to select each region and get return for the region selected </b>
  <br />
  <img src="https://i.imgur.com/7t0Gti0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
   <br />
   Column "deal_stage" is filtered to only lost because we only want to get result for the lost opportunity  </b>
      <br />
   <img src="https://i.imgur.com/rm79O9N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
   <br />
   Account is filtered into all account with atleast 30 lost opportunity </b>
   <br />
   <img src="https://i.imgur.com/YilnWPa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
     <br />
 <p align="initial">
3) How many won, lost, still engaging and prospecting opportunity under each account  </b>
<br />
<p align="center">
  Bubble chart is used to visualize this information </b>
 <br />
 <img src="https://i.imgur.com/1XjUySn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br />
 <p align="initial">
* For this chart i used the account parameter already created in the first chart to enable the selection of any Account and getting the number of won, lost, still engaging and prospecting opportunity back in return  </b>
  <br />
* I used colour to differentiate each deal_stages as shown in the right bottom corner of the image </b>
   <br />
    <br />
    4) Most successful Agent under each account </b>
    <br />
 <p align="center">
 Sales agent is used as the column and count of deal stage as row </b>
    <br />
    <img src="https://i.imgur.com/VVJPj89.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
        <br />
        <br /> 
        The deal stage is filtered to only won because we are trying to get most successful sales agent </b>
         <br />
<img src="https://i.imgur.com/MF7VWQT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
 <p align="initial">
 * The account parameter created will also be used for this chart to select any account we want to see return of  </b>
 <br />
    <br />
   5) Number of opportunity responded to between 1-5days for every account in each region  </b>
<br />
<br />
For this problem i created an extra column as "duration(days)" in my excel sheet by subtracting the engage_date from the close_date </b>
<br />
<p align="center">
 <img src="https://i.imgur.com/AyR8qS0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Account is used as the column and count(duration(days)) as row </b>
<br />
 <img src="https://i.imgur.com/MKwwIEn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
The duration of days was filtered between 1-5days </b>
<br />
 <img src="https://i.imgur.com/BGD9HdM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
 <p align="initial">
 * The region parameter created will also be used for this chart to select any region we want to see return of  </b>
 <br />
 <br />
<b> Then i created a single dashboard using all of these charts: </b>
 <br />
 <br />
 <p align="center">
 <img src="https://i.imgur.com/sC0QvZO.png" height="80%" width="80%" alt="Disk Sanitization Steps"
   <br />
   <p align="initial">
   * To create the dashboard i used the blank, horizontal containter and the text box </b> 
        <br />
         <br />
       <h2>Note:</h2>
       * The CRM+SALES+OPPORTUNITY raw data file is uploaded above and the excel file for the Project after filtering, sorting and addition of new column is also uploaded above as Tableau Project Excel </b> 
       <br />
    <h1>Tableau Project File</h1>

 ### [TABLEAU PUBLIC](https://public.tableau.com/views/CRMSALESOPPORTUNITY/Dashboard1?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link)

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
