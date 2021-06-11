<template>
  <header>
    <div class="border">
      <div style="margin: 5%">
        <p><B>Company Name</B></p>
        <input
          class="container"
          name="companyname"
          style="padding-right: 30px"
          ng-model="myText"
          required
        />
        <br />
        <p><B>Branch Name:</B></p>
        <input
          class="container"
          name="branch"
          style="padding-right: 30px"
          ng-model="myText"
          required
        />
        <br />
        
        <p><B>GST No:</B></p>
        <input
          class="container"
          name="gst"
          style="padding-right: 30px"
          ng-model="myText"
          required
        />
        <br />
        
        <p><B>Address:</B></p>
        <input
          class="container"
          name="address"
          style="padding-right: 30px"
          ng-model="myText"
          required
        />
        <br />
        <button class="button" style="margin-left:55%">Search</button>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Branch",
  props:
  {
    title:
    {
      String,
    },
  },
  components:
  {

  }
};
</script>
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-botton: 20px;
}
.container {
  background-color: lightgrey;
  margin-left: 100%;
  border-width: none;
  padding: 10px;
}
.border {
  border: 2px solid;
  border-width: 10;
  border-color: black;
  margin: 5%;
  padding: 50px 300px 75px 100px;
}
.button {
  background-color: darkgrey;
  border: none;
  color: white;
  padding: 10px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}
</style>