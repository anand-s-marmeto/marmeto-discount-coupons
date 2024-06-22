Create a metafield called 'discount coupons' with type set to 'meta-object'. Create a meta-object with two fields 'discount offer' and 'discount description'. Set this metaobject as the reference metaobject of the 'discount coupons' metafield.

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