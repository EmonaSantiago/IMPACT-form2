<script>
  import Form from "../../lib/components/3form.svelte";
    import Navigation from "../../lib/components/3navigation.svelte";
</script>

<body>
<Navigation></Navigation>
<div class="row">
    <div class="column">
        <h1>IMPACT</h1>
    </div>
    <div class="column">
      <Form></Form>
    </div>
  </div>
</body>
<style>
    * {
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    }

    :root {
        --impact-yellow: #F8F053;
    }

    body {
    margin: 0;
    background-image: url("/images/crew.png");
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: center;
    }

    * {
  box-sizing: border-box;
  margin: 0;
}

h1 {
    color: var(--impact-yellow);
    font-size: 120px;
}

h2 {
  color: white;
}


/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>