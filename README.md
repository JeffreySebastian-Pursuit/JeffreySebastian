# Hi there 👋


# Module 1
Intro to JavaScript
Created a textBasedAdventure

```textBasedAdventure
// This function validate the users age before playing the game//
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
![textAdventure](textAdventure![image](https://user-images.githubusercontent.com/75052251/113074023-40041d00-9198-11eb-95c4-5a8bba84350d.png)
)




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
![personalProject](PersonalWebsite.gif![image](https://user-images.githubusercontent.com/75052251/113073826-dd128600-9197-11eb-9634-7483dd0c026e.png)
)

