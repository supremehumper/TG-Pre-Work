<!DOCTYPE html>
<html>
<head>
  <title>Ship To It - Company Packing List</title>
  <link href="https://fonts.googleapis.com/css?family=Lato: 100,300,400,700|Luckiest+Guy|Oxygen:300,400" rel="stylesheet">
  <link href="style.css" type="text/css" rel="stylesheet">
</head>
<body>

  <ul class="navigation">
    <li><img src="https://s3.amazonaws.com/codecademy-content/courses/web-101/unit-9/htmlcss1-img_logo-shiptoit.png" height="20px;"></li>
    <li class="active">Action List</li>
    <li>Profiles</li>
    <li>Settings</li>
  </ul>

  <div class="search">Search the table</div>
  
  <table>
    <thead>
    <tr>
      <th>Company Name</th>
      <th>Number of Items to Ship</th>
      <th>Next Action</th>
    </tr>
    </thead>
    <tbody>
    <tr>
      <td colspan="2">Adam's Greenworks</td>
      <td>14</td>
      <td rowspan="2">Package Items</td>
    </tr>
    <tr>
      <td>Davie's Burgers</td>
      <td>2</td>
      <td>Send Invoice</td>
    </tr>
    <tr>
      <td>Baker's Bike Shop</td>
      <td>3</td>
      <td>Send Invoice</td>
    </tr>
    <tr>
      <td>Miss Sally's Southern</td>
      <td>4</td>
      <td>Ship</td>
    </tr>
    <tr>
      <td>Summit Resort Rentals</td>
      <td>4</td>
      <td>Ship</td>
    </tr>
    <tr>
      <td>Strike Fitness</td>
      <td>1</td>
      <td>Enter Order</td>
    </tr>
    </tbody>
  </table>
  <tfoot>
    <tr>
      <td>Total</td>
    </tr>
    <tr>
      <td>28</td>
    </tr>
  </tfoot>


</body>
</html>