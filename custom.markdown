---
layout: custom
title: My custom page
permalink: /custom/
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus dapibus nunc ac tellus eleifend, vitae venenatis purus volutpat. Curabitur id felis sit amet tellus euismod vulputate vitae et diam. Nam maximus convallis luctus. Donec blandit elit est, vitae egestas lacus bibendum a. Pellentesque at quam ullamcorper, porttitor ipsum eu, condimentum nisl. Duis consectetur pellentesque ipsum ut faucibus. Duis imperdiet luctus tincidunt. Phasellus malesuada elementum cursus.

Sed quis gravida lorem. Nam mauris magna, varius non massa eget, feugiat ullamcorper enim. Vestibulum eu nulla ac mi rhoncus hendrerit ac id ex. Sed laoreet nisl et orci sagittis convallis. In vitae ante eget dui iaculis posuere. Curabitur facilisis sapien sit amet suscipit vestibulum. Praesent sapien magna, congue vel faucibus sed, posuere at orci. Quisque risus dolor, ultrices at egestas sed, sodales nec ipsum. Phasellus elementum libero eget risus tincidunt, sit amet volutpat dui condimentum. Etiam eu magna maximus, congue nisi ut, malesuada leo. Integer ullamcorper efficitur convallis. Suspendisse eget erat mauris. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nulla et diam eu dui aliquam scelerisque. Nam euismod lorem sem, sed laoreet turpis tempor ac.

Nullam id ligula non odio interdum laoreet. Etiam ut lectus feugiat, sagittis eros consectetur, iaculis arcu. Sed imperdiet viverra lorem, vel gravida diam imperdiet sed. Morbi feugiat placerat leo. Suspendisse pulvinar nisl luctus, fringilla sapien ut, hendrerit justo. Etiam viverra justo felis, eget scelerisque justo tempor nec. Pellentesque nec augue quam. Aenean tincidunt laoreet dolor nec malesuada. Praesent volutpat in magna non varius.

<table>
  <caption>Statement Summary</caption>
  <thead>
    <tr>
      <th scope="col">Account</th>
      <th scope="col">Due Date</th>
      <th scope="col">Amount</th>
      <th scope="col">Period</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Account">Visa - 3412</td>
      <td data-label="Due Date">04/01/2016</td>
      <td data-label="Amount">$1,190</td>
      <td data-label="Period">03/01/2016 - 03/31/2016</td>
    </tr>
    <tr>
      <td scope="row" data-label="Account">Visa - 6076</td>
      <td data-label="Due Date">03/01/2016</td>
      <td data-label="Amount">$2,443</td>
      <td data-label="Period">02/01/2016 - 02/29/2016</td>
    </tr>
    <tr>
      <td scope="row" data-label="Account">Corporate AMEX</td>
      <td data-label="Due Date">03/01/2016</td>
      <td data-label="Amount">$1,181</td>
      <td data-label="Period">02/01/2016 - 02/29/2016</td>
    </tr>
    <tr>
      <td scope="row" data-label="Acount">Visa - 3412</td>
      <td data-label="Due Date">02/01/2016</td>
      <td data-label="Amount">$842</td>
      <td data-label="Period">01/01/2016 - 01/31/2016</td>
    </tr>
  </tbody>
</table>

<h2 class="mb-4">Properties</h2>
<div class="row">
    {% for file in site.static_files %}
        {% if file.image %}
        <div class="col-4 mb-4">
            <img src="{{ file.path }}" class="img-fluid" alt="">
        </div>
        {% endif %}
    {% endfor %}
</div>
