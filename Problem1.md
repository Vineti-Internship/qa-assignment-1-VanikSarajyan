<table>
    <tr>
        <th>Test Scenario</th>
        <th>Test Case</th>
        <th>Test Steps</th>
        <th>Test Data</th>
        <th>Expected Result</th>
        <th>Actual Result</th>
        <th>Status</th>
    </tr>
    <tr>
        <td width="150" rowspan="8">Check the Shipping Calculator</td>
        <td width="150" rowspan="4">Check when Entering Valid Input</td>
        <td width="250" rowspan="8"> 1.Choose country<br> 2.Choose shipping type<br> 3.Choose shipping method <br> 4.Enter parcel parameters</td>
        <td width="180" >Country: USA <br> Type: Online <br> Method: Air <br> Parameters: 10kg</td>
        <td width="150">35000 AMD</td>
        <td>35000 AMD</td>
        <td width="80">pass</td>
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
        <td>Counrty: USA(new) <br> Type: Personal Parcel <br> Method: Ship <br> Parameters: from 0 to 10kg</td>
        <td>25 USD</td>
        <td>25 USD</td>
        <td>pass</td>  
    </tr>
    <tr>
        <td rowspan="4">Check when Entering Invalid Input </td>
        <td>Counrty: USA <br> Type: Online <br> Method: Air <br> Parameters: -3kg</td>
        <td>Inform About Invalid Input</td>
        <td>400 AMD</td>
        <td>fail</td> 
    </tr>
    <tr>
        <td>Counrty: China <br> Type: Online <br> Method: Air <br> Parameters: (6-3)kg</td>
        <td>12000 AMD / Inform About Wrong Character</td>
        <td>400 AMD</td>
        <td>fail</td> 
    </tr>
    <tr>
        <td>Counrty: Russia <br> Type: Online <br> Method: Air <br> Parameters: none</td>
        <td>0 AMD / Inform About Empty Fields</td>
        <td>2000 AMD</td>
        <td>fail</td> 
    </tr>
    <tr>
        <td>Counrty: Great Britain <br> Type: Online <br> Method: Air <br> Parameters: 20000kg</td>
        <td>Inform About Overweight</td>
        <td>80000000 AMD</td>
        <td>fail</td> 
    </tr>
    
</table>
