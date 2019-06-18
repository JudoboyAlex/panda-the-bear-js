#Part1

document.querySelector(".profile-image").src = "https://placebear.com/200/300";

document.querySelector("h1").textContent = "Alexander The Great II"

document.getElementById("employment").querySelector(".info-title").textContent = "Raptors"

document.body.style.backgroundColor = "lightblue"

var myNodelist = document.querySelectorAll(".highlight");
var i;
for (i = 0; i < myNodelist.length; i++) {
  myNodelist[i].style.backgroundColor = "lightgreen";
}

document.querySelector("h1").style.fontFamily = "monospace";

document.querySelectorAll(".action-icon-bg")[0].style.backgroundColor = "purple"
document.querySelectorAll(".action-icon-bg")[1].style.backgroundColor = "purple"

document.querySelector("name").placeholder = "identify yourself"

document.querySelector("textarea").placeholder = "state your business"

var btn = document.createElement("value");
btn.innerHTML = "your nemesis";
document.getElementById("name").appendChild(btn);

var btn = document.createElement("value");
btn.innerHTML = "koalathebear@gmail.com";
document.getElementById("email").appendChild(btn);

document.getElementById("submit").value = "En Garde"

document.getElementById("submit").removeAttribute("type")

var list = document.querySelector(".bio-info"); 
while (list.hasChildNodes()) {   
list.removeChild(list.firstChild);
}

#Part2

list = document.querySelectorAll('.bar-default')
list[0].parentNode.removeChild(list[2])

var itm = document.querySelector("#right-image img");
var cln = itm.cloneNode();
document.querySelector(".portfolio-container").appendChild(cln)

itm = document.querySelector('#right-image img')
cln = document.querySelector('.portfolio-container')
for (i=0;i<10;i++){ newImage = drawing.cloneNode(); div.appendChild(newImage); }


const listItem = document.createElement('li');
const leftSpan = document.createElement('span');
var lastUpdated = document.createTextNode('Page last updated on');
leftSpan.appendChild(lastUpdated);
listItem.appendChild(leftSpan);
document.querySelector(".bio-info").appendChild(listItem);
const rightSpan = document.createElement('span');
var lastUpdatedAgain = document.createTextNode('Fri April 2016 03:53:16 GMT-0400(EDT)');
rightSpan.appendChild(lastUpdatedAgain);
listItem.appendChild(rightSpan);