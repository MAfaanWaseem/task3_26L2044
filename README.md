<!DOCTYPE html>
<html>
<head>
<style> h1{color:red;font-family:arial,sans-serif; text-align:center}
        body{ background-color:silver}
        table{ background-color: lightblue;border:2px solid;margin:80px;width:600px;align:center;}
        td{border:1px solid;}

</style>
</head>
<body>
<h1>Continental Hotel Reservation Form </h1>

<form>
<table>

<tr><td>
<label for="fname">Name:</label></td>
<td>
 <input type="text" id="fname" name="fname" placeholder="Enter your name"><br></td>
</tr>

<tr><td>
<label for="fname">E-mail:</label></td>
<td>
 <input type="text" id="fname" name="fname" value="info@continental.pk"><br>
</td></tr>

<tr><td>
<label for="phone">Mobile Number:</label></td>
<td>
 <input type="tel" id="phone" name="phone" placeholder ="Enter your cell number"><br>
</td></tr>


<tr><td>
<label for="time">Arrival Time:</label></td>
<td>
 <input type="time" id="time" name="time" placeholder ="Enter your arrival time"><br>
</td></tr>

<tr><td>
<label for="depart">Departure:</label></td>
<td>
 <input type="text" id="depart" name="depart">
<input type="time" id="depart" name="depart" ><br>
</td></tr>

<tr><td>
<label for="room">Room-Type:</label></td>
<td>
 <input type="radio" id="room" name="room" value="Single">
  <label for="room">Single</label>
<input type="radio" id="room" name="room" value="Double">
  <label for="room">Double</label><br>
<input type="radio" id="room" name="room" value="Presidential Suite">
  <label for="room">Presidential Suite</label><br></td>
</tr>

<tr>
<td>
<label for="pref">Preferences:</label></td>
<td>
  <input type="checkbox" id="pref" name="pref" value="Non-Smoking" >
  <label for="pref">Non-Smoking</label><br>
 <input type="checkbox" id="pref" name="pref" value="Internet" >
  <label for="pref">Internet</label><br>
 <input type="checkbox" id="pref" name="pref" value="Firm Mattress">
  <label for="pref">Firm Mattress</label><br>
</td>
</tr>


<tr>
   <td class="label-cell"><label>Mode of Payment</label></td>
    <td>
    <input type="checkbox" id="cash" name="payment" value="Cash">
    <label for="cash">Cash</label>
    <input type="checkbox" id="check" name="payment" value="Check">
    <label for="check">Check</label><br>
     <input type="checkbox" id="card" name="payment" value="Credit Card">
     <label for="card">Credit Card</label>
     <select name="select_card">
       <option>Select Card</option>
       </select>
 </td>
  </tr>
<tr>
<td colspan="2" style="text-align:center;">
<button type="submit">Send Data</button>
</td>
</tr>





</table>
</form>

</body>
</html>
