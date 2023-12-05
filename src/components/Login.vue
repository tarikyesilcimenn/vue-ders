<script>
export default {
    data(){
        
    }
};
</script>
<template>
  <div class="box">
    <label>Email</label>
    <input />
    <label>Şifre</label>
    <input />
    <label>Şifre Tekrarı</label>
    <input />
  </div>
</template>

<style scoped>
.box {
  display: flex;
  padding: 60px 60px;
  border-radius: 12px;
  background-color: cornflowerblue;
  flex-direction: column;
  width: 200px;
}
.box label {
  color: black;
  font-size: 18px;
  margin-bottom: 5px;

}
.box input {
  margin-bottom: 5px;
  height: 30px;
  border-radius: 6px;
  border: 0;
}
</style>