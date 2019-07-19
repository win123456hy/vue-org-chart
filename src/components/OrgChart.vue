<template>
  <div>
    <CsOrgChart
              :tree="tree"
              :nodeWidth="180"
              :nodeHeight="100"
              :nodeSpacing="12"
              :animationDuration="350"
              lineType="angle"
    />
  </div>
</template>

<script>
  import CsOrgChart from "../OrgChart/src/index.js";
  import fakeData from '../OrgChart/src/utils/fake-data';

  export default {
    name: 'OrgChart',

    components: {
      CsOrgChart
    },

    data(){
      return {
        tree: fakeData()
      }
    }
  }
</script>
