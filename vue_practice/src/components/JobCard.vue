<template>
  <div>
      <b-col>
        <b-card
        title="This Is a Card"
        img-src="https://picsum.photos/600/300/?images=25"
        img-alt="job-info"
        img-top
        tag="article"
        style="max-width:20rem"
        class="mb-2"
        >
          <b-card-text>
            <h1>Hello!</h1>
          </b-card-text>
          <b-button variant="primary">
            Apply
            </b-button>
        </b-card>
      </b-col>
 
  </div>
</template>

<script>
export default {
  name: 'JobCard'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
