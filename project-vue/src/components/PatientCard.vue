<template>
  <router-link
    class="event-link"
    :to="{ name: 'EventDetails', params: { id: event.id } }"
  >
    <Card class="event-card">
      <template #header>
        <img :src="event.photo" />
      </template>
      <template #title> {{ event.name }} {{ event.surname }} </template>
      <template #content> Patient ID: {{ event.id }} </template>
    </Card>
  </router-link>
</template>

<script>
export default {
  name: 'PatientCard',
  props: {
    event: {
      type: Object,
      required: true
    }
  }
}
</script>

<style scoped>
.event-card {
  height: 100%;
  cursor: pointer;
  margin-bottom: 18px;
}

.event-card:hover {
  transition: 0.25s;
  transform: scale(1.05);
  box-shadow: 0 3px 12px 0 rgba(0, 0, 0, 0.2);
}

.event-link {
  color: #2c3e50;
  text-decoration: none;
}
</style>
