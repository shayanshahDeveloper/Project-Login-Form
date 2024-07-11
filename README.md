# Login Form
Language Uses: HTML, CSS, JAVASCRIPT
## ScreenShots
![Form img](https://github.com/shayanshahDeveloper/Project-Login-Form/assets/161978365/ae256bf9-400c-494a-8411-6ddbdb50fd00)
![Sign img](https://github.com/shayanshahDeveloper/Project-Login-Form/assets/161978365/e2d2f99b-60f2-471e-9933-fec01649ab63)


JavaScript Code For User Interaction 👨‍💻
```javascript
let signUpBtn = document.querySelector(".signupbtn");
let signInBtn = document.querySelector(".signinbtn");
let nameField = document.querySelector(".namefield");
let title = document.querySelector(".title");
let underline = document.querySelector(".underline");
let text= document.querySelector(".text");


signInBtn.addEventListener("click", ()=>{
    nameField.style.maxHeight = '0';
    title.innerHTML ="Sign In";
    signUpBtn.classList.add("disable");
    signInBtn.classList.remove("disable");
    underline.style.transform ="translateX(35px)";
    text.innerHTML="Lost Password";

});

signUpBtn.addEventListener("click", ()=>{
    nameField.style.maxHeight = '60px';
    title.innerHTML ="Sign Up";
    text.innerHTML="Password Suggestion";

    signUpBtn.classList.remove("disable");
    signInBtn.classList.add("disable");
    underline.style.transform ="translateX(0)";

});
```
## Check Out The Website 👇

[Login Form Website](https://shayanshahdeveloper.github.io/Project-Login-Form/)

## Developed By Shayan Shah
Social media Handles 👉
[Linkdin](https://www.linkedin.com/in/shayan-shah-b31439296/)


