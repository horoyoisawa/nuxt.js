<template>
  <ul>
    <li v-for="n in 10000" :key="n">
      This is row {{ n + 1 }}
    </li>
    <li v-for="n in 100" :key="n">
      This is sample {{ n + 1 }}
    </li>
  </ul>
</template>
