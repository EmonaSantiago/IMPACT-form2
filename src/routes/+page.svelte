<body>
<div class="row">
    <div class="column">
      <h1>IMPACT</h1>
      <h3>Welkom bij ons <span>aanmeldingsformulier</span> voor een <span>positie bij Impact!</span> We zijn verheugd dat je interesse toont om deel uit te maken van ons team.</h3>
    </div>

    <div class="column">
        <ul>
            <li><a class="button" href="/creative">CREATIVE</a></li>
            <li><a class="button" href="/crew">CREW</a></li>
            <li><a class="button" href="/model">MODEL</a></li>
         </ul>
    </div>
</div>
</body>

<style>
    * {
        margin: 0;
  box-sizing: border-box;
  font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    }

    :root {
        --impact-yellow: #F8F053;
    }

body {
    margin: 0;
    background-image: url("TEAM.png");
    height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: center;
}

.column {
  float: left;
  width: 50%;
  padding: 10px;
  padding-top: 30px;
  height: 300px;
}


.row:after {
  content: "";
  display: table;
  clear: both;
}

h1 {
    color: var(--impact-yellow);
    font-size: 120px;
}

span { 
        color: white;
    }

h3 {
    color: var(--impact-yellow);
}

a {
        text-decoration: none;
        color: black;
    }


li {
        list-style-type: none;
        width: 250px;
        padding: 1em;
        margin-bottom: 30px;  
        background-color: var(--impact-yellow);
        text-align: center;
    }

    ul {
        padding: 0;
        display: inline-block;
        text-align: left;
    }


@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>