<template>
    <h1>Job Details Page</h1>
    <p>The job id is {{ id }}</p>
  <div v-for="job in jobs" :key="job.id">
    <h2>{{ job.title }}</h2></div>
</template>

<script>
export default {
data() {
    return {
        id: this.$route.params.id
    }
}
}
</script>

<style>

</style>