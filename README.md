# Hi there 👋


# Module 1
Intro to JavaScript
Created a textBasedAdventure

```textBasedAdventure
// This function validate the users age before playing the game //
const howOldAreYou = () => {
  let age = Number(readLineSync.question("How old are you?"));
  if (!age) {
    console.clear();
    console.log("Not a valid input");
    howOldAreYou();
  } else if (age >= 18) {
    console.clear();
    console.log("You are old enough to play this game!");
    startGame();
  } else if (age < 18) {
    console.log("You are underage");
    exitGame();
  }
};
```
# Image
![image](https://user-images.githubusercontent.com/75052251/113074370-f2d47b00-9198-11eb-80dc-e9bba6add4e3.png)




# Module 2
HTML, CSS, and DOM
Created a Personal Websites

```personalWebsite

//created a local storage to save dark mode to light mode//
const button = document.querySelector("#toDarkMode")
const mode  = localStorage.getItem('mode');
const body = document.body
if(mode !== null){
    body.classList.add(mode)
}
button.addEventListener("click", (e) =>{
  body.classList.toggle("dark-mode");
  if(button === "Dark Mode"){
      localStorage.setItem("mode", "dark-mode")
      
  } else {
      localStorage.setItem ("mode", "body")
  }
  if(button.textContent === "Dark Mode"){
      button.textContent = "Light Mode"
  }else{
      button.textContent = "Dark Mode"
  }
})
```
# Project gif
[![gif](https://user-images.githubusercontent.com/75052251/113078149-86f61080-91a0-11eb-83e2-f018b08c63aa.png)](https://user-images.githubusercontent.com/75052251/113077386-0c78c100-919f-11eb-94f1-1059cd614254.mp4)

