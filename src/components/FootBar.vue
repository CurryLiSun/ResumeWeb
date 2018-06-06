<template>
    <div class="foot-bar">
        <ul>
            <li> {{top1}} </li>
            <li> {{top2}} </li>
            <li> {{top3}} </li>
        </ul>
        <ul>
          <router-link to ="/">Go To Home</router-link>
          <li>
            <router-link to ="/MyTurn">Go To My Turn</router-link>
          </li>
        </ul>
    </div>
</template>

<script>
export default {
  name: "FootBar",
  data() {
    return {
      top1: "Li",
      top2: "haung",
      top3: "chi"
    };
  }
};
</script>

<style>
.foot-bar {
  background-color: chocolate;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
