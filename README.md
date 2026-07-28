<!DOCTYPE html>
<html>
<head>
<title>For Nancy 💗</title>

<style>
body {
    background: pink;
    font-family: Arial;
    text-align: center;
    padding-top: 80px;
}

.box {
    background: white;
    width: 80%;
    margin: auto;
    padding: 25px;
    border-radius: 25px;
    box-shadow: 0 0 20px hotpink;
}

button {
    background: hotpink;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 20px;
    font-size: 18px;
}
</style>

</head>

<body>

<div class="box">

<h2 id="message">Tap here Nancy 💌</h2>

<button onclick="nextMessage()">Open 💗</button>

</div>


<script>

let count = 0;

let messages = [

"Hi chsmis baddie 😍💗",

"How are you? I hope you are smiling today 😊✨",

"I heard some tiny insect hurt you 🐜😭 Let me see what happened!",

"Checking... checking... 🤔",

"Wait... I found the problem 😂",

"The insect was jealous because you are too cute 😌💖",

"Don't worry, let me call the doctor 👨‍⚕️📞",

"Doctor is coming with his magic bag 🚑✨",

"Doctor: Let me see... hmm 🤔",

"Doctor says: Nancy, reply fast! You will get better soon 💕",

"Drink enough water, eat healthy food, sleep well and keep smiling always 🌸😊",

"Byyyy Nancy 🥰💗 Stay healthy and happy forever ✨💕"

];


function nextMessage(){

if(count < messages.length){

document.getElementById("message").innerHTML = messages[count];

count++;

}

}

</script>

</body>
</html>
