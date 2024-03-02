<template>
  <Header/>
  <div class="container">
  <Balance/>
  <IncomeExpense/>
  <TransactionList/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Balance from "./components/Balance.vue";
import IncomeExpense from "./components/IncomeExpenses.vue";
import TransactionList from "./components/TransactionList.vue";
export default  {
    components : {
        Header,
        Balance,
        IncomeExpense,
        TransactionList
    }
}
</script>