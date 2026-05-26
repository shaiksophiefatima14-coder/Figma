# Ex09 Event Registration Web Application
# Date: 26/5/26
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
globals.css
```
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
/* @FONTWARNING[{"type": "restricted", "family": "Jolly Lodger-Regular", "weight": "400", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Jolly Lodger-Regular";
  src: local("Jolly Lodger-Regular");
}
/* @FONTWARNING[{"type": "restricted", "family": "Jockey One-Regular", "weight": "400", "style": "normal", "allowsCrossOrigin": false}] */

@font-face {
  font-family: "Jockey One-Regular";
  src: local("Jockey One-Regular");
}

```
style.css
```
.home {
  background-image: url(./img/home.png);
  background-size: cover;
  background-position: 50% 50%;
  width: 100%;
  min-width: 402px;
  min-height: 874px;
  display: flex;
  flex-direction: column;
}

.home .rectangle {
  margin-left: 12px;
  width: 358px;
  height: 68px;
  margin-top: 51px;
  object-fit: cover;
}

.home .text-wrapper {
  margin-left: 50px;
  width: 303px;
  height: 78px;
  margin-top: 137px;
  font-family: "Jolly Lodger-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.home .group {
  margin-left: 51px;
  width: 302px;
  height: 60px;
  position: relative;
  margin-top: 112px;
}

.home .ellipse {
  position: absolute;
  top: 0;
  left: 0;
  width: 300px;
  height: 60px;
  border-radius: 150px / 30px;
  background: radial-gradient(
    50% 50% at 50% 50%,
    rgba(23, 72, 175, 1) 66%,
    rgba(10, 30, 73, 1) 100%
  );
}

.home .div {
  position: absolute;
  top: 5px;
  left: 102px;
  font-family: "Jockey One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

```
# OUTPUT:
<img width="549" height="1001" alt="Screenshot 2026-05-25 192501" src="https://github.com/user-attachments/assets/599ab6a0-5aa5-4848-b809-e10da8545ed2" /> 
<img width="629" height="957" alt="Screenshot 2026-05-25 192520" src="https://github.com/user-attachments/assets/0ae9217b-69d1-42bc-b09e-63c68a50555a" />
<img width="558" height="1004" alt="Screenshot 2026-05-25 192529" src="https://github.com/user-attachments/assets/9504d417-ba8c-471d-8656-5c7b7a489cba" />
<img width="607" height="983" alt="Screenshot 2026-05-25 192538" src="https://github.com/user-attachments/assets/bea149f4-1096-42e9-9ef9-44ba2f27785a" />




# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
