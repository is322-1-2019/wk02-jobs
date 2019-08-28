<template>
  <div class="main">
    <h1>Monster Hunter</h1>

    <p>There are 2 clans for you to choose!</p>

    <div class="row">
      <div class="col-md-6" id="player1">
        <div class="card">
          <div class="card-header">
            <h3>Hunter</h3>
          </div>
          <div class="card-body">
            <img id="hunter" src="../assets/img/hunter.png" />
          </div>
          <div class="card-footer">
            <p>First is Hunters the good man who were born to protect the world.</p>
          </div>
        </div>
      </div>

      <div class="col-md-6" id="player2">
        <div class="card">
          <div class="card-header">
            <h3>Monster</h3>
          </div>
          <div class="card-body">
            <img id="hunter" src="../assets/img/monster.jpg" />
          </div>
          <div class="card-footer">
            <p>Next is Monster the evil creatures that will devour all the life and bring chaos to the world.</p>
          </div>
        </div>
      </div>

      </div>

    <h3>Game Design by Jobs Krittanon</h3>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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

#hunter {
  width: 200px;
  height: 250px;
}

.card {

 text-align: center;
 vertical-align: middle;

}

.card :hover { 

  background-color: lightblue;
  cursor: pointer;
}

@media only screen and (max-width: 600px) {
  .card {
    background-color: red;
  }
}

</style>
