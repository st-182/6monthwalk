<template>
  <div class="nutrition-facts">
    <h2>Nutrition Facts</h2>
    <table>
      <thead>
        <tr>
          <th>Nutrient</th>
          <th>Amount per serving</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="(value, nutrient) in nutritionFacts" :key="nutrient">
          <td>{{ nutrient }}</td>
          <td>{{ value }}</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script lang="ts">
export default {
  props: {
    nutritionFacts: {
      type: { value: number, nutrient: string },
      default: { value: 10, nutrient: 'dfs' }
    } // Assuming you pass in an object with nutrient values
  }
}
</script>

<style scoped>
.nutrition-facts {
  font-family: 'Arial', sans-serif;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
}

th,
td {
  border: 1px solid #ddd;
  padding: 8px;
  text-align: left;
}

th {
  background-color: #f2f2f2;
}
</style>
