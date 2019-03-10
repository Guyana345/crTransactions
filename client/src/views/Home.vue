<template>
  <div>
    <h2>Home</h2>
    <transitions></transitions>
    <edit-transactions></edit-transactions>
  </div>
</template>

<script>
import Transactions from "../components/Transactions";
import EditTransactions from "../components/EditTransactions";
export default {
  name: "home",
  components: {
    Transactions,
    EditTransactions
  }
};
</script>

<style scoped>
</style>