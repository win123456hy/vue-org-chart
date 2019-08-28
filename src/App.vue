<template>
  <div id="app">
    <!--<OrgChart/>-->
    <OrgChartTest/>
  </div>
</template>

<script>
import OrgChart from './components/OrgChart.vue'
import OrgChartTest from './components/OrgChartTest.vue'

export default {
  name: 'app',
  components: {
    OrgChart,
    OrgChartTest
  }
}
</script>

