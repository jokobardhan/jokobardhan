<html>
    <body>
        <h1>Hai prenn</h1>
        <img src="https://cdn130.picsart.com/301097254071201.gif?to=min&r=1024">
        <h1>aku cakep ga?</h1>
        <button id='btn_Cakep' onclick='alert("I KNOW HAHA")'>Cakep</button>&nbsp;
        <button id='btn_Ga' onclick='Ga(this)' style='position:absolute'>Ga</button>
    </body>
    <script>
        function Ga(id){
            var Cakep = document.getElementById('btn_Cakep');
            var i = Math.floor(Math.random()*300)+1;
            var j = Math.floor(Math.random()*100)+Cakep.offsetTop;
            id.style.left = i+'px';
            id.style.top = j+'px';
        }
    </script>
</html>
