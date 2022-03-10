<template>
<div>
<div class="head">
  <nav>
    <div class="logo">
      <p>Logo</p>
    </div>
    <h1>Cloud Cost Monitoring</h1>
    <button>Ajouter a la liste</button>
  </nav>
</div>

<table>
       <tr class="table-header"> 
        <th>Liste</th>
        <th>Temps</th>
        <th>Coût</th>
       </tr>

       <tr class="table-row"> 
        <th>AWS</th>
        <th>00:10:00</th>
        <th>10$</th>
       </tr>

       <tr class="table-row"> 
        <th>Azure</th>
        <th>00:00:00</th>
        <th>0$</th>
       </tr>

       <tr class="table-row"> 
        <th>Google Cloud</th>
        <th>00:00:00</th>
        <th>0$</th>
       </tr>    
    </table>

    <footer>
  <p>Footer</p>
</footer>
</div>
</template>

<style>
.head{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
nav{
    color: white;
    display: flex;
    min-height: 12vh;
    background-color: #5d4954;
}
h1{
    margin-left: auto;
    margin-right: auto;
}
button{
    margin-right: 10px;
    margin-top: 26px;
    margin-bottom: 26px;
    border-radius: 4px;
    transition-duration: 0.4s;
    background-color: rgb(20, 141, 193);
    border: none;
}
button:hover {
  background-color: gray; 
  color: rgb(10, 9, 9);
}
.logo{
    text-align: left;
    width: 10%;
}

table
{
    border-collapse: collapse;
    margin-right: auto;
    margin-left: auto;
    margin-top: 50px;
    width: 50%;
    height: 100%;
    max-width: 500px;
	justify-content:center;
	align-items:center;
	min-height:60vh;
}
td, th /* Mettre une bordure sur les td ET les th */
{
    border: 1px solid black;
}
.table-header {
	background:#000;
	padding:(half-spacing-unit * 1.5) 0;
    color: white;
}

footer {
    display: flex;
    justify-content: center;
    padding: 5px;
    background-color: #45a1ff;
    color: #fff;
    flex-shrink: 0;
    border-top: 1px dashed black;
    width: 100%;
    bottom: 0;
    position: absolute;
}
</style>