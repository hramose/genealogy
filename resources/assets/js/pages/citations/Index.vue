<template>

    <vue-table class="box"
        :path="path"
        id="citations">
    </vue-table>

</template>

<script>
import VueTable from '../../components/enso/vuedatatable/VueTable.vue';

export default {
    components: { VueTable },

    data() {
        return {
            path: route('citations.initTable'),
        };
    },
};
</script>
