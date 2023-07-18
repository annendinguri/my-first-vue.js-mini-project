<template>
    <div>
        <form action="">
            <h1>signup here</h1>
            <input type="text" placeholder="enter username">  <br/>
             <input type="text" placeholder="enter password"> <br/>
            <BUtton>submit</BUtton> <br/>
        </form>
    </div>
</template>
 
 <script>
 export default {
  name: 'SignupComponent',
  props: {
    msg: String
  }
}
 </script>

 <style scoped>
 h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
 </style>
 