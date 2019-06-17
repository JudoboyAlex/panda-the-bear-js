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