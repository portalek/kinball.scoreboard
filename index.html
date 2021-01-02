// query our HTML elements using their ids / class names
const modraplusButton = document.querySelector("#modra-plus");
const modraminusButton = document.querySelector("#modra-minus");
const sedaplusButton = document.querySelector("#seda-plus");
const sedaminusButton = document.querySelector("#seda-minus");
const cernaplusButton = document.querySelector("#cerna-plus");
const cernaminusButton = document.querySelector("#cerna-minus");
const resetButton = document.querySelector("#reset");

function pricti(barva) {
    var x = document.getElementById(barva).textContent;
    x = Number(x);
    document.getElementById(barva).innerHTML = x + 1;
}

function odecti(barva) {
    var x = document.getElementById(barva).textContent;
    x = Number(x);
    if (x>0){
      document.getElementById(barva).innerHTML = x - 1;
      }
    }

document.onkeydown = checkKey;

var last="NaN";

function checkKey(e) {

    e = e || window.event;

    console.log(e.keyCode);
    
    if (e.keyCode == '38') {
        // up arrow
       pricti("modra");
       pricti("cerna");
       last="chybaSeda";       
    }
    else if (e.keyCode == '40') {
        // down arrow
    }
    else if (e.keyCode == '37') {
       // left arrow
       pricti("seda");
       pricti("cerna");
       last="chybaModra";
    }
    else if (e.keyCode == '39') {
       // right arrow
       pricti("modra");
       pricti("seda");
       last="chybaCerna";
       
    }
    else if (e.keyCode == '27') {
       // back
       // pridat pamatovani posledniho pricteni a revertovat ho
       if(last=="chybaSeda") {
         odecti("modra");
         odecti("cerna");      
       }
       else if(last=="chybaModra") {
         odecti("seda");
         odecti("cerna");      
       }
       else if(last=="chybaCerna") {
         odecti("modra");
         odecti("seda");      
       }
       last="NaN"
    }
    else if (e.keyCode == '179') {
       // play
       odecti("modra");
    }
    else if (e.keyCode == '174') {
       // volume -
       odecti("seda");
    }
    else if (e.keyCode == '34') {
       // page down
        odecti("cerna");
    }

}

resetButton.onclick = function() {
  document.getElementById("modra").innerHTML = 0;
  document.getElementById("seda").innerHTML = 0;
  document.getElementById("cerna").innerHTML = 0;
};

modraplusButton.onclick = function() {pricti("modra")}; 
modraminusButton.onclick = function() {odecti("modra")};
sedaplusButton.onclick = function() {pricti("seda")};
sedaminusButton.onclick = function() {odecti("seda")};
cernaplusButton.onclick = function() {pricti("cerna")};
cernaminusButton.onclick = function() {odecti("cerna")};
