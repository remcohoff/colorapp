<template>
    <div class="message">
        <p v-if="hours < 12"> Goede morgen!</p>
        <p v-if="hours >= 12 && hours < 18"> Goede middag!</p>
        <p v-if="hours >= 18"> Goede avond!</p>
    </div>
</template>

<script>
export default {
  name: "Hello",
  data: function () {
      return {
          hours: new Date().getHours()
      }
  }
};
</script>