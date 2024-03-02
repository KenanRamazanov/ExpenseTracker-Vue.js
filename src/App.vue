<template>
  <Header/>
  <div class="container">
  <Balance/>
  <IncomeExpense/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Balance from "./components/Balance.vue";
import IncomeExpense from "./components/IncomeExpenses.vue";
export default  {
    components : {
        Header,
        Balance,
        IncomeExpense
    }
}
</script>