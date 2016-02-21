---
layout: page
title: "Bitcoin arbitrage"
description: "Where to trade Bitcoin? What are good exchanges for altcoin trading? Who has lowest fees?"
permalink: /category/arbitrage.html
---

<h4 class="exa">All posts related to <b>arbitrage with Bitcoin or altcoins</b></h4>

<note>"Bitcoin Arbitrage"</note>

{% for post in site.posts %}
  {% if post.category contains "bitcoin arbitrage" or post.categories contains "bitcoin arbitrage" %}
  <h4 class="post">
  <strong>
  <a href="/{{ post.url }}">{{ post.title }}</a>
  </strong>
  <small>{{ post.date | date_to_string }}</small>
  </h4>
  <p>
  {{ post.description }}
  </p>
  {% endif %}
{% endfor %}

<note>"Altcoin Arbitrage"</note>

{% for post in site.posts %}
  {% if post.category contains "altcoin arbitrage" or post.categories contains "altcoin arbitrage" %}
  <h4 class="post">
  <strong>
  <a href="/{{ post.url }}">{{ post.title }}</a>
  </strong>
  <small>{{ post.date | date_to_string }}</small>
  </h4>
  <p>
  {{ post.description }}
  </p>
  {% endif %}
{% endfor %}


<note>"Trading Bots"</note>

{% for post in site.posts %}
  {% if post.category contains "bitcoin bots" or post.categories contains "bitcoin bots" %}
  <h4 class="post">
  <strong>
  <a href="/{{ post.url }}">{{ post.title }}</a>
  </strong>
  <small>{{ post.date | date_to_string }}</small>
  </h4>
  <p>
  {{ post.description }}
  </p>
  {% endif %}
{% endfor %}



<div style="text-align:center">
<a rel="nofollow" target="_blank" href="https://www.ledgerwallet.com/r/e274">
<img alt="Ledger Wallet protects your bitcoins" src="https://www.ledgerwallet.com/images/promo/ledger-468x90-01.jpg">
</a>
</div>

&nbsp;

<h4 class="exa" id="summary">Summary  on trading bots</h4>

Bitcoin trading bots need maintenance.

Additionally, you need to either buy or build one and you might need to rent server space for it to run.

_If you though of it as of long-lasting income with no investment and effort, you should forget it._

#### If you decide to do the work yourself.

* Get accounts on several Bitcoin exchanges that are fit for trading

  * [Bitcoin Exchanges Good for Trading](/best-exchange-bitcoin-trading.html#exchanges)

* Get an app to trade on mobile

  * [Bitcoin Trading Basics / Mobile Trading](/bitcoin-trading-basics.html#mobile)

* Get a mobile bitcoin wallet to manage your funds

  * [Bitcoin Wallets / Mobile Apps](/best-bitcoin-wallet.html#mobile)

* Get an app to notify you on price swings

  * [Bitcoin Checker (Android)](https://play.google.com/store/apps/details?id=com.mobnetic.coinguardian&hl=en) supports 80 different exchanges for which you can set an alarm. Bitcoin Paranoid is a bit more intrusive option.

  * [Bitcoin Paranoid (Android)](https://play.google.com/store/apps/details?id=br.eti.fml.satoshi) is probably the best. You choose the exchanges, it keeps flushing their BTC price into the top bar. In the alarm set up you can choose the price difference the app should notice. It will make some sound.

  * [Bitcoin ticker widget (Android)](https://play.google.com/store/apps/details?id=st.brothas.mtgoxwidget) - similar alternative, not so funny language.

* Make the decision on whether to trade or not yourself

#### If you are experienced in technical analysis and want to run bitcoin trading bots.

There is no doubt bots can execute tasks much faster than a human would ever be able to. But it is also true that bots need to be configured, tested and adjusted from time to time. If you are a good trader chances are trading bot will help you, if you really learn how to use it.

* Get a legit trading bot. A good one was designed by a Dutch company {% aff HaasOnline https://www.haasonline.com/?ref=49 %} and can be bought by 3 months subscription cycles. It is an actively maintained project available on all OS (Windows primarily, Mac OS and Linux if you ask for access). Version 3.0 was released in January '16 and is being tested now.

* The cheapest beginner license on {% aff HaasOnline https://www.haasonline.com/?ref=49 %} costs 0.22 BTC. If you want to learn using a bot and don't want to code one yourself, {% aff HaasOnline https://www.haasonline.com/?ref=49 %} is about as most legit solution you can get.

* {% aff HaasOnline https://www.haasonline.com/?ref=49 %} people state themselves in their FAQ that {% aff HaasBot https://www.haasonline.com/?ref=49 %} is not a one-click money making machine so keep that in mind.

* You will also need some solid hardware to run the HaasBot ([See this section for advice](#where-to-run-a-bitcoin-trading-bot)). You will need either a good Windows computer that you don't use or a VPS.
  * Dual-core processor (1,6GHz and up)
  * 2 GB random access memory
  * Stable internet connection (minimum 1mbit download)


<hr>
