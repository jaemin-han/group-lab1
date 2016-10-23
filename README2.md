input text
buttons (radio buttons, dropdown, checkbox, slider'some value', multi-select)


<form action ="" class ="list-maker-form" method = "get">
  <label>input your name
    <input type = 'text' name="myName" />
  </label>

  <button type="submit">asdfasD</button>
</form>

- every form must have a <button type="submit">


when html is ready to this thing (eventlistener) 

wait dome


document.addEventListner('DomContentloaded', function() {
  console.log('this is after the dom')
}

node server.js

how to view html AND NODE server.js

1) buttons
2) radio buttons = <input type = "radio"> - bulletpoints - select one.

3)dropdowm menu
4) <select> == dropdown slider box - <select> options.... pick one and it's selected 



  <form action="http://localhost:3000/showForm" class="list-maker-form" method="post" target='black'>
    <label>Shipping Address:</label><br>
      <textarea placeholder="First Name" cols="30" rows="1"></textarea>
      <textarea placeholder="Last Name" cols="30" rows="1"></textarea><br>
      <textarea placeholder="Address Line" cols="60" rows="1"></textarea><br>
      <textarea placeholder="City" cols="20" rows="1"></textarea>
      <textarea placeholder="State" cols="20" rows="1"></textarea>
      <textarea placeholder="Zip Code" cols="20" rows="1"></textarea><br>
      <textarea placeholder="Email" cols="40" rows="1"></textarea><br>

<br>

<!--     <label>Payment Information:</label><br>
      <textarea placeholder="Card Number" cols="30" rows="1"></textarea><br>
      <select name='expireMM' id='expireMM'>
          <option value=''>Month</option>
          <option value='01'>Janaury</option>
          <option value='02'>February</option>
          <option value='03'>March</option>
          <option value='04'>April</option>
          <option value='05'>May</option>
          <option value='06'>June</option>
          <option value='07'>July</option>
          <option value='08'>August</option>
          <option value='09'>September</option>
          <option value='10'>October</option>
          <option value='11'>November</option>
          <option value='12'>December</option>
      </select>
      <select name='expireYY' id='expireYY'>
          <option value=''>Year</option>
          <option value='10'>2016</option>
          <option value='11'>2017</option>
          <option value='12'>2018</option>
          <option value='11'>2019</option>
          <option value='12'>2020</option>
      </select>
      <input class="inputCard" type="hidden" name="expiry" id="expiry" maxlength="4"/><br>
      <textarea placeholder="Security Code" cols="30" rows="1"></textarea> -->

    <button type="submit">Submit</button>
  </form>
