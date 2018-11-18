
| Test Scenario | Test Case | Test Steps | Test Data | Expected Result | Actual Result | Status |
|--------------|-----------|-----------------------|---------------|---------------------|------------------|---------|
| Check Shipping Calculator | Check when entering valid input|  1.Choose country<br> 2.Choose shipping type<br> 3.Choose shipping method <br> 4.Enter parcel parameters| Country: USA <br> Type: Online <br> Method: Air <br> Parameters: 10kg | 35000 AMD | 35000 AMD | pass |
||||Counrty: China <br> Type: Online <br> Method: Air <br> Parameters: 3kg <br> | 48000 AMD | 48000 AMD | pass | 



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
        <td width="100" rowspan="4">Check the Shipping Calculator</td>
        <td width="100" rowspan="4">Check when Entering Valid Input</td>
        <td width="250" rowspan="4"> 1.Choose country<br> 2.Choose shipping type<br> 3.Choose shipping method <br> 4.Enter parcel parameters</td>
        <td width="200" >Country: USA <br> Type: Online <br> Method: Air <br> Parameters: 10kg</td>
        <td>35000 AMD</td>
        <td>35000 AMD</td>
        <td>pass</td>
    </tr>
        <td>Counrty: China <br> Type: Online <br> Method: Air <br> Parameters: 3kg</td>
        <td>12000 AMD</td>
        <td>12000 AMD</td>
        <td>pass</td>
    <tr>
    </tr>
        <td>Counrty: Russia <br> Type: Online <br> Method: Air <br> Parameters: 5kg</td>
        <td>10000 AMD</td>
        <td>10000 AMD</td>
        <td>pass</td>
    <tr>
    </tr>
</table>
