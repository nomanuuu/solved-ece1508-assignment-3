Download Link: https://assignmentchef.com/product/solved-ece1508-assignment-3
<br>
<ul>

 <li>Deploy the following topology using <em>Mininet</em><strong>. </strong></li>

 <li>Create the <strong><em>blue slice</em></strong>, <strong><em>red slice, and </em></strong><strong><em>green slice</em></strong> using <em>FlowVisor</em></li>

</ul>

○ Blue slice spans <strong>h1, s1, s2, and h2</strong>. It enables bi-directional communication between only h1 and h2. This slice will be controlled by a controller running on <em>TCP port 8000</em>.

○ Red slice spans <strong>h3, s3, s4, and h4</strong>. It enables bi-directional communication between only h3 and h4. Red slice will be controlled by a controller running on <em>TCP port 9000</em>.

○ Green slice spans <strong>h2, s2, s3, and h3</strong>. It enables bi-directional communication between only h2 and h3. Green slice will be controlled by a controller running on <em>TCP port 10000</em>.

<strong>Blue Slice     </strong><strong>Green Slice   </strong><strong>Red Slice<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/811.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/811.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></strong>

<strong>What to submit?</strong>

<table width="864">

 <tbody>

  <tr>

   <td width="57">●</td>

   <td colspan="2" width="807">Put the following files inside a compressed folder named<strong>&lt;lastname_firstname_university.zip&gt;</strong> where university is one of waterloo, toronto, ets, laval.</td>

  </tr>

  <tr>

   <td width="57">●</td>

   <td width="672">Files created by executing the following commands: ○ fvctl -n list-slice-info red &amp;&gt; red</td>

   <td width="135"><strong>                 (5)</strong></td>

  </tr>

  <tr>

   <td width="57"> </td>

   <td width="672"><strong>○ </strong>fvctl -n list-slice-info blue &amp;&gt; blue</td>

   <td width="135"><strong>                 (5)</strong></td>

  </tr>

  <tr>

   <td width="57"> </td>

   <td width="672"><strong>○ </strong>fvctl -n list-slice-info green &amp;&gt; green</td>

   <td width="135"><strong>                 (5)</strong></td>

  </tr>

  <tr>

   <td width="57"> </td>

   <td width="672"><strong>○ </strong>fvctl -n list-flowspace &amp;&gt; flowspace</td>

   <td width="135"><strong>               (15)</strong></td>

  </tr>

 </tbody>

</table>

<strong>Resources</strong>

<table width="669">

 <tbody>

  <tr>

   <td width="57">●</td>

   <td width="612">An already created slice can be removed using<strong>○ </strong><strong>fvctl -n remove-slice &lt;slice-name&gt;</strong></td>

  </tr>

  <tr>

   <td width="57">●</td>

   <td width="612">A flowspace created under a slice can be removed using<strong>○ </strong><strong>fvctl -n remove-flowspace &lt;flowspace-name&gt;</strong></td>

  </tr>

  <tr>

   <td width="57">●</td>

   <td width="612">Running <strong>fvctl </strong>without any other argument will show a list and description of possible sub-commands supported by <strong>fvctl</strong></td>

  </tr>

 </tbody>

</table>


