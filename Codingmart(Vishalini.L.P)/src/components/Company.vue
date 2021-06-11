<template>
  <header>
    <div class="border">
      <div style="margin: 5%">
        <p><B>COMPANY NAME:</B></p>
        <input
          class="container"
          name="companyname"
          style="padding-right: 30px"
          ng-model="myText"
          required
        />
        <br />
        <p><B>NATURE OF BUSINESS:</B></p>
        <input
          class="container"
          name="nature"
          style="padding-right: 30px"
          ng-model="myText"
          required
        />
        <br />
        <button class="button" style="margin-left: 200%">Save</button>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Company",
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