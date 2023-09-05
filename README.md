# MyPharmacy
Pharmacy management system for ecommerce drug stores. 

# Dictionary object

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="application/xhtml+xml; charset=ISO-8859-1" />
</head>
<body>
  <table class="outerTable">
    <tr>
      <td><h2>Table: ZYUU3_D_DRUG</h2>
  <h3>Description: Drugs table</h3></td>
    </tr>
    <tr>
      <td><!--This is where our main table begins  -->
<table class="innerTable">
<tr>
  <th>Row</th>
  <th>Field name</th>
  <th>Position</th>
  <th>Key</th>
  <th>Data element</th>
  <th>Domain</th>
  <th>Datatype</th>
  <th>Length</th>
  <th>Lowercase</th>
  <th>Domain text</th>
</tr>
<tr class="cell">
  <td> 1</td>
  <td>MANDT</td>
  <td>1</td>
  <td>X</td>
  <td>MANDT</td>
  <td>MANDT</td>
  <td>CLNT</td>
  <td>3</td>
  <td>&nbsp;</td>
  <td>Client</td>
</tr>
<tr class="cell">
  <td> 2</td>
  <td>DRUG_ID</td>
  <td>2</td>
  <td>X</td>
  <td>ZYUU3_DRUG_ID</td>
  <td>ZYUU3_DRUG_ID</td>
  <td>NUMC</td>
  <td>6</td>
  <td>&nbsp;</td>
  <td>Drug ID</td>
</tr>
<tr class="cell">
  <td> 3</td>
  <td>CATEGORY</td>
  <td>3</td>
  <td>&nbsp;</td>
  <td>ZYUU3_CATEGORY_NAME</td>
  <td>ZYUU3_CATEGORY_NAME</td>
  <td>CHAR</td>
  <td>100</td>
  <td>&nbsp;</td>
  <td>Category name</td>
</tr>
<tr class="cell">
  <td> 4</td>
  <td>DRUG_NAME</td>
  <td>4</td>
  <td>&nbsp;</td>
  <td>ZYUU3_DRUG_NAME</td>
  <td>ZYUU3_DRUG_NAME</td>
  <td>CHAR</td>
  <td>100</td>
  <td>&nbsp;</td>
  <td>Drug name</td>
</tr>
<tr class="cell">
  <td> 5</td>
  <td>MANUFACTURED_DATE</td>
  <td>5</td>
  <td>&nbsp;</td>
  <td>ZYUU3_MANUFACTURED_DATE</td>
  <td>DATUM</td>
  <td>DATS</td>
  <td>8</td>
  <td>&nbsp;</td>
  <td>Manufactured date</td>
</tr>
<tr class="cell">
  <td> 6</td>
  <td>EXPIRE_DATE</td>
  <td>6</td>
  <td>&nbsp;</td>
  <td>ZYUU3_EXPIRE_DATE</td>
  <td>DATUM</td>
  <td>DATS</td>
  <td>8</td>
  <td>&nbsp;</td>
  <td>Expire date</td>
</tr>
<tr class="cell">
  <td> 7</td>
  <td>MANUFACTURER</td>
  <td>7</td>
  <td>&nbsp;</td>
  <td>ZYUU3_MANUFACTURER_NAME</td>
  <td>ZYUU3_MANUFACTURER_NAME</td>
  <td>CHAR</td>
  <td>100</td>
  <td>&nbsp;</td>
  <td>Manufacturer Name</td>
</tr>
      </table>
     </td>
   </tr>
<br/>
   <tr>
<td class="footer">Extracted by Mass Download version 1.5.5 - E.G.Mellodew. 1998-2023. Sap Release 756</td>
   </tr>
</table>
</body>
</html>


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="application/xhtml+xml; charset=ISO-8859-1" />
</head>
<body>
  <table class="outerTable">
    <tr>
      <td><h2>Table: ZYUU3_D_CUSTOMER</h2>
  <h3>Description: Customer table</h3></td>
    </tr>
    <tr>
      <td><!--This is where our main table begins  -->
<table class="innerTable">
<tr>
  <th>Row</th>
  <th>Field name</th>
  <th>Position</th>
  <th>Key</th>
  <th>Data element</th>
  <th>Domain</th>
  <th>Datatype</th>
  <th>Length</th>
  <th>Lowercase</th>
  <th>Domain text</th>
</tr>
<tr class="cell">
  <td> 1</td>
  <td>ADDRESS</td>
  <td>9</td>
  <td>&nbsp;</td>
  <td>ZYUU3_CUSTOMER_ADDRESS</td>
  <td>TEXT140</td>
  <td>CHAR</td>
  <td>140</td>
  <td>X</td>
  <td>Customer Address</td>
</tr>
<tr class="cell">
  <td> 2</td>
  <td>BIRT_DATE</td>
  <td>10</td>
  <td>&nbsp;</td>
  <td>DATUM</td>
  <td>DATUM</td>
  <td>DATS</td>
  <td>8</td>
  <td>&nbsp;</td>
  <td>Date</td>
</tr>
<tr class="cell">
  <td> 3</td>
  <td>CITY</td>
  <td>8</td>
  <td>&nbsp;</td>
  <td>ZYUU3_CUSTOMER_CITY</td>
  <td>TEXT40</td>
  <td>CHAR</td>
  <td>40</td>
  <td>X</td>
  <td>Customer City</td>
</tr>
<tr class="cell">
  <td> 4</td>
  <td>COUNTRY</td>
  <td>7</td>
  <td>&nbsp;</td>
  <td>ZYUU3_CUSTOMER_COUNTRY</td>
  <td>LAND1</td>
  <td>CHAR</td>
  <td>3</td>
  <td>&nbsp;</td>
  <td>Customer Country</td>
</tr>
<tr class="cell">
  <td> 5</td>
  <td>EMAIL</td>
  <td>5</td>
  <td>&nbsp;</td>
  <td>ZYUU3_CUSTOMER_EMAIL</td>
  <td>TEXT40</td>
  <td>CHAR</td>
  <td>40</td>
  <td>X</td>
  <td>Customer email</td>
</tr>
<tr class="cell">
  <td> 6</td>
  <td>FIRST_NAME</td>
  <td>3</td>
  <td>&nbsp;</td>
  <td>ZYUU3_FIRST_NAME</td>
  <td>ZYUU3_PERSON_NAME</td>
  <td>CHAR</td>
  <td>30</td>
  <td>X</td>
  <td>First Name</td>
</tr>
<tr class="cell">
  <td> 7</td>
  <td>GENDER</td>
  <td>6</td>
  <td>&nbsp;</td>
  <td>ZYUU3_CUSTOMER_GENDER</td>
  <td>ZYUU3_CUSTOMER_GENDER</td>
  <td>CHAR</td>
  <td>1</td>
  <td>&nbsp;</td>
  <td>Customer Gender</td>
</tr>
<tr class="cell">
  <td> 8</td>
  <td>ID</td>
  <td>2</td>
  <td>X</td>
  <td>ZYUU3_CUSTOMER_ID</td>
  <td>ZYUU3_CUSTOMER_ID</td>
  <td>NUMC</td>
  <td>6</td>
  <td>&nbsp;</td>
  <td>Customer ID</td>
</tr>
<tr class="cell">
  <td> 9</td>
  <td>LAST_NAME</td>
  <td>4</td>
  <td>&nbsp;</td>
  <td>ZYUU3_LAST_NAME</td>
  <td>ZYUU3_PERSON_NAME</td>
  <td>CHAR</td>
  <td>30</td>
  <td>X</td>
  <td>Last Name</td>
</tr>
<tr class="cell">
  <td>10</td>
  <td>MANDT</td>
  <td>1</td>
  <td>X</td>
  <td>MANDT</td>
  <td>MANDT</td>
  <td>CLNT</td>
  <td>3</td>
  <td>&nbsp;</td>
  <td>Client</td>
</tr>
      </table>
     </td>
   </tr>
<br/>
  <table class="outerTable">
    <tr>
      <td><h2>Fixed Domain Values </h2>
    </tr>
    <tr>
      <td><!--This is where our main table begins  -->
<table class="innerTable">
<tr>
  <th>Domain Name</th>
  <th>Value Low</th>
  <th>Value High</th>
  <th>Text</th>
</tr>
<tr class="cell">
  <td>ZYUU3_CUSTOMER_GENDER</td>
  <td>M</td>
  <td>&nbsp;</td>
  <td>Male</td>
</tr>
<tr class="cell">
  <td>ZYUU3_CUSTOMER_GENDER</td>
  <td>F</td>
  <td>&nbsp;</td>
  <td>Female</td>
</tr>
      </table>
     </td>
   </tr>
   <tr>
<td class="footer">Extracted by Mass Download version 1.5.5 - E.G.Mellodew. 1998-2023. Sap Release 756</td>
   </tr>
</table>
</body>
</html>


<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="application/xhtml+xml; charset=ISO-8859-1" />

</head>
<body>
  <table class="outerTable">
    <tr>
      <td><h2>Table: ZYUU3_D_ORDER</h2>
  <h3>Description: Order Table</h3></td>
    </tr>
    <tr>
      <td><!--This is where our main table begins  -->
<table class="innerTable">
<tr>
  <th>Row</th>
  <th>Field name</th>
  <th>Position</th>
  <th>Key</th>
  <th>Data element</th>
  <th>Domain</th>
  <th>Datatype</th>
  <th>Length</th>
  <th>Lowercase</th>
  <th>Domain text</th>
</tr>
<tr class="cell">
  <td> 1</td>
  <td>CUSTOMER_ID</td>
  <td>7</td>
  <td>&nbsp;</td>
  <td>ZYUU3_CUSTOMER_ID</td>
  <td>ZYUU3_CUSTOMER_ID</td>
  <td>NUMC</td>
  <td>6</td>
  <td>&nbsp;</td>
  <td>Customer ID</td>
</tr>
<tr class="cell">
  <td> 2</td>
  <td>ID</td>
  <td>2</td>
  <td>X</td>
  <td>ZYUU3_ORDER_ID</td>
  <td>ZYUU3_ORDER_ID</td>
  <td>NUMC</td>
  <td>6</td>
  <td>&nbsp;</td>
  <td>Order ID</td>
</tr>
<tr class="cell">
  <td> 3</td>
  <td>MANDT</td>
  <td>1</td>
  <td>X</td>
  <td>MANDT</td>
  <td>MANDT</td>
  <td>CLNT</td>
  <td>3</td>
  <td>&nbsp;</td>
  <td>Client</td>
</tr>
<tr class="cell">
  <td> 4</td>
  <td>ORDER_DATE</td>
  <td>3</td>
  <td>&nbsp;</td>
  <td>DATUM</td>
  <td>DATUM</td>
  <td>DATS</td>
  <td>8</td>
  <td>&nbsp;</td>
  <td>Date</td>
</tr>
<tr class="cell">
  <td> 5</td>
  <td>PAYMENT_AMOUNT</td>
  <td>5</td>
  <td>&nbsp;</td>
  <td>ZYUU3_PAYMENT_AMOUNT</td>
  <td>CURR</td>
  <td>DEC</td>
  <td>17</td>
  <td>&nbsp;</td>
  <td>Payment Amount</td>
</tr>
<tr class="cell">
  <td> 6</td>
  <td>PAYMENT_MODE</td>
  <td>4</td>
  <td>&nbsp;</td>
  <td>ZYUU3_PAYMENT_MODE</td>
  <td>ZYUU3_PAYMENT_MODE</td>
  <td>CHAR</td>
  <td>100</td>
  <td>&nbsp;</td>
  <td>Payment Mode</td>
</tr>
<tr class="cell">
  <td> 7</td>
  <td>PAYMENT_STATUS</td>
  <td>6</td>
  <td>&nbsp;</td>
  <td>ZYUU3_PAYMENT_STATUS</td>
  <td>ZYUU3_PAYMENT_STATUS</td>
  <td>CHAR</td>
  <td>100</td>
  <td>&nbsp;</td>
  <td>Payment Status</td>
</tr>
      </table>
     </td>
   </tr>
<br/>
  <table class="outerTable">
    <tr>
      <td><h2>Fixed Domain Values </h2>
    </tr>
    <tr>
      <td><!--This is where our main table begins  -->
<table class="innerTable">
<tr>
  <th>Domain Name</th>
  <th>Value Low</th>
  <th>Value High</th>
  <th>Text</th>
</tr>
<tr class="cell">
  <td>ZYUU3_PAYMENT_STATUS</td>
  <td>PENDING</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
</tr>
<tr class="cell">
  <td>ZYUU3_PAYMENT_STATUS</td>
  <td>COMPLETE</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
</tr>
<tr class="cell">
  <td>ZYUU3_PAYMENT_STATUS</td>
  <td>FAILED</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
</tr>
      </table>
     </td>
   </tr>
   <tr>
<td class="footer">Extracted by Mass Download version 1.5.5 - E.G.Mellodew. 1998-2023. Sap Release 756</td>
   </tr>
</table>
</body>
</html>

