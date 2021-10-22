<template>
    <div class="event-card">
    <h1>First Dose</h1>
    <p>Date : {{GStore.patient.vaccinedata[0].firstdose.Date}}</p>
    <p>Manufacturer : {{GStore.patient.vaccinedata[0].firstdose.type}}</p>
    <p>Lot No. : {{GStore.patient.vaccinedata[0].firstdose.LotNo}}</p>
    <p>Hospital : {{GStore.patient.vaccinedata[0].firstdose.Hospital}}</p>
    <!--  <h4>{{ events.name }} {{events.surname}}</h4> -->
    </div>
    <div class="event-card">
    <h1>Second Dose</h1>
    <p>Date : {{GStore.patient.vaccinedata[0].Seconddose.Date}}</p>
    <p>Manufacturer : {{GStore.patient.vaccinedata[0].Seconddose.type}}</p>
    <p>Lot No. : {{GStore.patient.vaccinedata[0].Seconddose.LotNo}}</p>
    <p>Hospital : {{GStore.patient.vaccinedata[0].Seconddose.Hospital}}</p>
    <!--  <h4>{{ events.name }} {{events.surname}}</h4> -->
    </div>
  
</template>

<script>
export default {
  name: 'VaccineCard',
  inject: ['GStore'],
  props: ['events']

}
</script>

<style scoped>
.event-card {
  padding: 20px;
  width: 15.625 rem;
  cursor: pointer;
  border: 1px solid #39495c;
  margin-bottom: 18px;
  text-align: left;
  }

.event-card:hover {
  transform: scale(1.01);
  box-shadow: 0 3px 12px 0 rgba(0, 0, 0, 0.2);
}

.event-link {
  color: #2c3e50;
  text-decoration: none;
}
</style>
