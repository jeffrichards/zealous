---
title: House of Payne
date: 2025-03-01T11:38:31-08:00
cover: tshirt.jpg
categories:
  - custom
tags:
  - HRM
---

Welcome to the House of Payne...
<!--more-->

This is the good kind of Payne, that which makes us Stronger Together.

## T-Shirt 
Seen above is Unisex soft cotton T-shirt with Trainer Tanna's "House of Payne" skull on front centre of T-shirt, and Stronger Together on sleeve.

## Sweatshirt
Unisex large fitting, drawstring sweatpants with Trainer Tanna's 'House of Payne' skull on front pocket of sweatpants.
![Unisex large fitting, drawstring sweatpants with Trainer Tanna's 'House of Payne' skull on front pocket of sweatpants.
](sweatshirt.jpg "Unisex large fitting, drawstring sweatpants with Trainer Tanna's 'House of Payne' skull on front pocket of sweatpants.")

## Sweatpants
Unisex large fitting, drawstring sweatpants with Trainer Tanna's 'House of Payne' skull on front pocket of sweatpants.
![Unisex large fitting, drawstring sweatpants with Trainer Tanna's 'House of Payne' skull on front pocket of sweatpants.](pants.jpg "Unisex large fitting, drawstring sweatpants with Trainer Tanna's 'House of Payne' skull on front pocket of sweatpants.")



<h2 id="order_now"> Order Now!</h2>
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
  <input type="hidden" name="cmd" value="_s-xclick" />
  <input type="hidden" id="hosted_button_id" name="hosted_button_id" value="2XDCXC48293TJ" />
  <table class="not-prose">
    <tr>
      <td>
        <input type="hidden" name="on0" value="Style"/>
        <strong>Style</strong>
      </td>
    </tr>
    <tr>
      <td>
        <select id="os0" name="os0" class="input input-bordered" style="appearance:auto; -webkit-appearance: auto" onChange="updateItemName()">
          <option value="T-Shirt">
            T-Shirt $38.00 CAD
          </option>
          <option value="Sweatshirt">
            Sweatshirt $59.00 CAD
          </option>
          <option value="Sweatpants">
            Sweatpants $54.00 CAD
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
          <option value="Black">
            Black
          </option>
          <option value="Grey">
            Grey
          </option>
          <option value="Green">
            Green
          </option>
          <option value="Red">
            Red
          </option>
          <option value="Maroon">
            Maroon
          </option>
          <option value="Navy">
            Navy
          </option>
          <option value="Heather Grey">
            Heather Grey
          </option>
          <option value="Purple">
            Purple
          </option>
          <option value="Royal Blue">
            Royal Blue
          </option>
          <option value="Pink">
            Pink
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
  <input type="hidden" id ="item_name" name="item_name" value="House of Payne">
  <input type="hidden" id ="os4" name="os4" value="House of Payne">
  <input type="hidden" name="currency_code" value="CAD" />
  <input style="margin-top:10px" type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_buynowCC_LG.gif" border="0" name="submit" title="PayPal - The safer, easier way to pay online!" alt="Buy Now" onClick="updateItemName()"/>
  <div>Shipping Costs Calculated at Checkout</div>
  <script>
    let designName = document.getElementById("title");
    let designNameField = document.getElementById("os4");
    designNameField.setAttribute('value',designName.innerText)
    function updateItemName() {
      let design = document.getElementById("title");
      let shirtStyle = document.getElementById("os0");
      let shirtSize = document.getElementById("os1");
      let shirtColor = document.getElementById("os2");
      let itemName = document.getElementById("item_name");
      console.log(
        design.innerText + " " + 
        shirtStyle.options[shirtStyle.selectedIndex].value + " " + 
        shirtSize.options[shirtSize.selectedIndex].value + " " + 
        shirtColor.options[shirtColor.selectedIndex].value
      )
      itemName.setAttribute('value', 
        design.innerText + " " + 
        shirtStyle.options[shirtStyle.selectedIndex].value + " " + 
        shirtSize.options[shirtSize.selectedIndex].value + " " + 
        shirtColor.options[shirtColor.selectedIndex].value
      )
    }
    function toggleLocalPickup() {
      const shippingButtonID="2XDCXC48293TJ"
      const freeShippingButtonID="ZWFF9QBX8ZAPE"
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
