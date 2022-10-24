+++
title = "Pricing"
description = "Our differents packages"
date = "2019-02-28"
aliases = ["packages", "pricing", "Inleaf"]
author = "Corentin"
+++

<style>
p, li { color: rgba(0, 0, 0, 0.61); }

* {
  box-sizing: border-box;
}

.columns {
  float: left;
  width: 33.3%;
  padding: 8px;
}

.price {
  list-style-type: none;
  border: 1px solid #eee;
  margin: 0;
  padding: 0;
  -webkit-transition: 0.3s;
  transition: 0.3s;
}

.price:hover {
  box-shadow: 0 8px 12px 0 rgba(0,0,0,0.2)
}

.price .header {
  background-color: #111;
  color: white;
  font-size: 25px;
}

.price li {
  border-bottom: 1px solid #eee;
  padding: 20px;
  text-align: center;
}

.price .grey {
  background-color: #eee;
  font-size: 20px;
}

.button {
  background-color: #00e0c0;
  border: none;
  color: white;
  padding: 10px 25px;
  text-align: center;
  text-decoration: none;
  font-size: 18px;
}

@media only screen and (max-width: 800px) {
  .columns {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="columns">
  <ul class="price">
    <li class="header" style="background-color:#018673">Basic</li>
    <li class="grey">€ 9.99 / month / device</li>
    <li>Up to 3 Inleaf users</li>
    <li>Up to 50 devices</li>
    <li>Jamf integration</li>
    <li>7 days backup</li>
    <li>5 support /month</li>
    <li class="grey"><a href="/contact" class="button">Choose</a></li>
  </ul>
</div>

<div class="columns">
  <ul class="price">
    <li class="header" style="background-color:#FF87B0">Pro</li>
    <li class="grey">€ 19.99 / month / device</li>
    <li>All Basic features</li>
    <li>Unlimited Inleaf users</li>
    <li>Unlimited support</li>
    <li>Up to 500 devices</li>
    <li>Inleaf APIs</li>
    <li>SSO authentification</li>
    <li>14 days backup</li>
    <li class="grey"><a href="/contact" class="button">Choose</a></li>
  </ul>
</div>

<div class="columns">
  <ul class="price">
    <li class="header">Premium</li>
    <li class="grey">€ 39.99 / month / device</li>
    <li>All Pro features</li>
    <li>Unlimited devices</li>
    <li>Custom Alerting</li> 
    <li>Custom KPIs</li> 
    <li>Custom development</li>
    <li>Custom integration</li>
    <li>1 year backup</li>
    <li class="grey"><a href="/contact" class="button">Choose</a></li>
  </ul>
</div>

</body>
</html>
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XL5C408EK9"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-XL5C408EK9');
</script>
