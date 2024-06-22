Add this code in main-product.liquid or your main-product file:

To render the snippet:
{% when 'discount-coupon' %}
  {% render 'discount-coupons' %}


Add this to the section-blocks:
{
  "type":"discount-coupon",
  "name":"Discount coupon"
}

Note: Change the css properties based on your requirement.