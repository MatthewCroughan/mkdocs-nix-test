---
unit:
  price: 5000
---

# Welcome to Foundries

For full documentation visit [docs.foundries.io](https://docs.foundries.io/latest).

{% if page.meta.unit.price >= 5000 %}
  The current price of a Foundries.io subscription is **${{ page.meta.unit.price }}**, WOW that's expensive!
{% elif page.meta.unit.price < 5000 %}
  The current price of a Foundries.io subscription is **${{ page.meta.unit.price }}**, that's a lot cheaper.
{% endif %}

