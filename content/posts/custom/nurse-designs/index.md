---
title: Nurse Designs
date: 2020-04-02T11:38:31-08:00
cover: InfusingCourage.png
categories:
  - custom
tags:
---

Nurse Designs!
<!--more-->

## Infusing Courage T-Shirt 
Shown Above!  Unisex soft cotton T-shirt in Pink, Black, or Jade.  


## Infusing Love T-Shirt
Unisex soft cotton T-shirt in Pink, Black, or Jade.
![Unisex soft cotton T-shirt with Full Chest Image: "Infusing Love" and picture of IV Bag with a heart](InfusingLove.png "Unisex soft cotton T-shirt with Full Chest Image: 'Infusing Love' and picture of IV Bag with a heart")

## Infusing Strength T-Shirt
Unisex soft cotton T-shirt in Pink, Black, or Jade.  
![Unisex soft cotton T-shirt with Full Chest Image: "Infusing Strength" and picture of IV Bag with a heart](InfusingStrength.png "Unisex soft cotton T-shirt with Full Chest Image: 'Infusing Strength' and picture of IV Bag with a heart")

<h2 id="order_now"> Order Now!</h2>
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
  <input type="hidden" name="cmd" value="_s-xclick" />
  <input type="hidden" id="hosted_button_id" name="hosted_button_id" value="HX29CRW3KYGQQ" />
  <table class="not-prose">
      <tr>
      <td>
        <input type="hidden" name="on4" value="Variety"/>
        <strong>Variety</strong>
      </td>
    </tr>
    <tr>
      <td>
        <select id="os4" name="os4" class="input input-bordered" style="appearance:auto; -webkit-appearance: auto" onChange="updateItemName()">
           <option value="Infusing Courage">
            Infusing Courage Adult T-Shirt $25.00 CAD
          </option>
          <option value="Infusing Love">
            Infusing Love Adult T-Shirt $25.00 CAD
          </option>
          <option value="Infusing Strength">
            Infusing Strength Adult T-Shirt $25.00 CAD
          </option>
        </select>
      </td>
    </tr>
    <tr>
      <td style="padding-top:10px">
        <input type="hidden" name="on1" value="Size"/>
        <strong>Size</strong> (see <a target="_blank" style="color:#22c;" href="/sizing-chart/">Sizing Chart</a>)
      </td>
    </tr>
    <tr>
      <td>
        <select id="os1" name="os1" class="input input-bordered" style="appearance:auto; -webkit-appearance: auto" onChange="updateItemName()">
          <option value="XS">
            XS
          </option>
          <option value="Small" selected>
            Small
          </option>
          <option value="Medium">
            Medium
          </option>
          <option value="Large">
            Large
          </option>
          <option value="XL">
            XL
          </option>
          <option value="2XL">
            2XL
          </option>
          <option value="3XL">
            3XL
          </option>
        </select>
      </td>
    </tr>
    <tr>
      <td style="padding-top:10px">
        <input type="hidden" name="on2" value="Color"/>
        <strong>Color</strong>
      </td>
    </tr>
    <tr>
      <td>
        <select id="os2" name="os2" class="input input-bordered" style="appearance:auto; -webkit-appearance: auto" onChange="updateItemName()">
          <option value="Black" selected>
            Black
          </option>
          <option value="Pink" >
            Pink
          </option>
          <option value="Jade" >
            Jade
          </option>
        </select>
      </td>
    </tr>
    <tr>
      <td style="padding-top:10px">
        <input type="hidden" name="on3" value="Customizations and Notes"/>
      <strong>Customizations and Notes</strong>
      </td>
    </tr>
    <tr>
      <td>
        <input type="text" name="os3" style="border-width:1px" maxLength="500" class="input input-bordered"/>
      </td>
    </tr>
    <tr>
      <td style="padding-top:10px">
        <input type="checkbox" name="local-pickup" onClick="toggleLocalPickup()"/> I'll pickup this order myself (no shipping applied)
        <input type="hidden" id="no_shipping" name="no_shipping" value=2 />
      </td>
    </tr>

  </table>
  <input type="hidden" id ="item_name" name="item_name" value="Infusing">
  <input type="hidden" name="on0" value="Style"/>
  <input type="hidden" name="os0" value="Women's T-shirt">
  <input type="hidden" name="currency_code" value="CAD" />
  <input style="margin-top:10px" type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_buynowCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Buy Now" onClick="updateItemName()"/>
</form>
  <div>Shipping Costs Calculated at Checkout</div>
  <script>
    //let designName = document.getElementById("title");
    //let designNameField = document.getElementById("os4");
    //designNameField.setAttribute('value',designName.innerText)
    function updateItemName() {
      let design = document.getElementById("title");
      let designName = document.getElementById("os4");
      let shirtStyle = document.getElementById("os0");
      let shirtSize = document.getElementById("os1");
      let shirtColor = document.getElementById("os2");
      let itemName = document.getElementById("item_name");
      console.log(
        designName.options[designName.selectedIndex].value + " " + 
        shirtSize.options[shirtSize.selectedIndex].value + " " + 
        shirtColor.options[shirtColor.selectedIndex].value 
      )
      itemName.setAttribute('value', 
        designName.options[designName.selectedIndex].value + " " + 
        shirtSize.options[shirtSize.selectedIndex].value + " " + 
        shirtColor.options[shirtColor.selectedIndex].value
      )
    }
    function toggleLocalPickup() {
      const shippingButtonID="HX29CRW3KYGQQ"
      const freeShippingButtonID="693HB3DUBKZPY"
      let shippingState = document.getElementById("hosted_button_id");
      let shippingPrompt = document.getElementById("no_shipping");
      if (shippingState.value == shippingButtonID) {
        shippingState.setAttribute('value',freeShippingButtonID)
        shippingPrompt.setAttribute('value',1)
      } else {
        shippingState.setAttribute('value',shippingButtonID)
        shippingPrompt.setAttribute('value',2)
      }
      return true
    }
  </script>
