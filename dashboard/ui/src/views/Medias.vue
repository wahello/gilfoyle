<template>
  <v-container>
    <v-row>
      <v-col md="12">
        <MediaList></MediaList>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { Vue } from "vue-property-decorator";
import MediaList from "../components/MediaList.vue";

export default Vue.extend({
  components: { MediaList },
  data: () => ({})
});
</script>
