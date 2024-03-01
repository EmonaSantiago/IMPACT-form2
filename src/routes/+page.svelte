<body>
<div class="row">
    <div class="column">
      <h1>IMPACT</h1>
      <h3>WELCOME TO THE IMPACT <span>APPLICATION FORM</span></h3>
    </div>

    <div class="column">
        <ul>
            <li><a class="button" href="/creative">CREATIVE</a></li>
            <li><a class="button" href="/crew">CREW</a></li>
            <li><a class="button" href="/model">MODEL</a></li>
         </ul>
      
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
    background-image: url("/images/TEAMimpact.png");
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

.button {
      flex: 1;
      max-width: 30%;
      text-align: center;
      margin: 5px; 
      margin-top: 1em;
      padding: 10px;
      text-decoration: none;
      border: none;
      transition: background-color 0.3s;
    }

h1 {
    color: var(--impact-yellow);
    font-size: 120px;
}

span { 
        color: var(--impact-yellow);
    }

h3 {
    color: white;
}

h3, span {
    font-family: MADE Future X;
    font-size: 20px;
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
        background-color: #F8F053;
        text-align: center;
        border-radius: 5px;
    }

    ul {
        padding: 0;
        display: inline-block;
        text-align: left;
    }



  

    .nav {
        padding: 0;
        display: flex;
        text-align: left;
    }


@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
</style>