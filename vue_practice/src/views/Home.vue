<template>
  <b-container>
 <b-row align-v="center">
  <job-card></job-card>
  <job-card></job-card>
  <job-card></job-card>
  <job-card></job-card>
      
    </b-row>
  </b-container>
</template>

<script>

import JobCard from '../components/JobCard.vue'
// @ is an alias to /src

export default {
  name: "home",
  components: {
    "job-card" : JobCard
  }
};
</script>
