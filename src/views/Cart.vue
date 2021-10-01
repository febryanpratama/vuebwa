<template>
  <div>
    <HeaderShayna />

    <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-left">
            <div class="breadcrumb-text product-more">
              <a href="./home.html"><i class="fa fa-home"></i> Home</a>
              <span>Shopping Cart</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Breadcrumb Section Begin -->

    <CartProduct />
    <FooterShayna />
  </div>
</template>

<script>
import carousel from "vue-owl-carousel";

// import carousel from "vue-owl-carousel";
import HeaderShayna from "@/components/HeaderShayna.vue";
import CartProduct from "@/components/CartProduct.vue";

import FooterShayna from "@/components/FooterShayna.vue";
export default {
  name: "Cart",
  components: {
    HeaderShayna,
    CartProduct,
    FooterShayna,
  },
};
</script>
