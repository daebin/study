<template>
  <p v-for="Customer in CustomerData" :key="Customer">
    <input name="customerName" type="radio"> {{ Customer.cus_name }}
    </p>
</template>

<script>

export default {
    name : 'CustomerVue',
    props : {
        CustomerData: Array,
    }
}
</script>

<style>

</style>
