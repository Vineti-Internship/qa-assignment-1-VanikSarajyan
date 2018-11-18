<table>
    <tr>
        <th>Test Scenarion</th>
        <th>Test Case</th>
        <th>Test Steps</th>
        <th>Test Data</th>
        <th>Expected Result</th>
        <th>Actual Result</th>
        <th>Status</th>
    </tr>
    <tr>
        <td width="120" rowspan="5">Check the Shipping Calculator</td>
        <td width="150" rowspan="4">Check when Entering Valid Input</td>
        <td width="250" rowspan="5"> 1.Choose country<br> 2.Choose shipping type<br> 3.Choose shipping method <br> 4.Enter parcel parameters</td>
        <td width="150" >Country: USA <br> Type: Online <br> Method: Air <br> Parameters: 10kg</td>
        <td>35000 AMD</td>
        <td>35000 AMD</td>
        <td>pass</td>
    </tr>
    <tr>
        <td>Counrty: China <br> Type: Online <br> Method: Air <br> Parameters: 3kg</td>
        <td>12000 AMD</td>
        <td>12000 AMD</td>
        <td>pass</td>
    </tr>
    <tr>
        <td>Counrty: Russia <br> Type: Online <br> Method: Air <br> Parameters: 5kg</td>
        <td>10000 AMD</td>
        <td>10000 AMD</td>
        <td>pass</td>  
    </tr>
    <tr>
        <td>Counrty: USA(new) <br> Type: Personal Parcel <br> Method: Ship <br> Parameters: 0-10kg</td>
        <td>25 USD</td>
        <td>25 USD</td>
        <td>pass</td>  
    </tr>
    <tr>
        <td>Check when Entering Invalid Input </td>
        <td>Counrty: USA <br> Type: Online <br> Method: Air <br> Parameters: -3kg</td>
        <td>0 AMD</td>
        <td>400 AMD</td>
        <td>fail</td> 
    </tr>
</table>
