<template>
    <div class="nav-bar">
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
  name: "NavBar",
  data: function(){
    return {
      top1: "My",
      top2: "Resume",
      top3: "Read"
    };
  }
};
</script>

<style>
.nav-bar {
  background-color:goldenrod;
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
