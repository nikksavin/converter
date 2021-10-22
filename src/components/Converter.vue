<template>
    <div class="converter-field">
      <ConverterSelect/>
        <ConverterInput/>
    </div>
</template>

<script>
import ConverterSelect from "./ConverterSelect";
import ConverterInput from "./ConverterInput";
    export default {
        name: "Converter",
        components: {
          ConverterSelect, ConverterInput
        },
        methods: {

        }
    }
</script>

<style scoped>
.converter-field {
    max-width: 300px;
}
</style>