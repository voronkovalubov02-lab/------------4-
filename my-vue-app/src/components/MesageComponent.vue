<template>
    <div class="mesag-bloc">
        <h1>{{ title }}</h1>
        <p>{{ mesag }}</p>
    </div>
</template>
<script>
export default{
name:'MesageComponent',
props: {
    title:{type:String,
        required: true
    },
      mesag:{
        type:String,
        required:true
      }
}


}

</script>
<style scoped>
.mesag-bloc {
  background-color: #1b2838; 
  color: #ffffff;        
  text-align: center;        
  padding: 20px;             
  margin: 20px auto;   
  max-width: 400px;       
  border-radius: 10px;     
  font-family: sans-serif;
}

.mesag-bloc h1 {
  color: #66c0f4;           
  margin-bottom: 10px;
}

.mesag-bloc p {
  color: #c6d4df;     
  margin: 0;
}
</style>