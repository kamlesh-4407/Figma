# Ex08 Event Registration Web Application
## Date:20-11-2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
### Login Page
#### HTML
```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="logo" src="img/logo-1.png" />
      <img class="vector" src="img/vector.svg" />
      <div class="text-wrapper">REGISTER</div>
      <div class="rectangle"></div>
      <div class="div">LOGIN</div>
    </div>
  </body>
</html>
```
#### CSS
```css
.iphone-pro-max {
  position: relative;
  width: 430px;
  height: 932px;
  background-color: #9b4aad;
}

.iphone-pro-max .logo {
  position: absolute;
  top: 86px;
  left: 33px;
  width: 366px;
  height: 55px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.iphone-pro-max .vector {
  position: absolute;
  top: 482px;
  left: 73px;
  width: 285px;
  height: 83px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 489px;
  left: 87px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 70px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 383px;
  left: 74px;
  width: 284px;
  height: 83px;
  background-color: #682477;
  border: 1px solid;
  border-color: #2b1c1c;
}

.iphone-pro-max .div {
  position: absolute;
  top: 396px;
  left: 137px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 70px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```
### Event Page
#### HTML
```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="text-wrapper">Events Available</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-2">CTF</div>
      <div class="text-wrapper-3">VALORANT GAME</div>
      <div class="text-wrapper-4">DANCE BATTLE</div>
      <div class="text-wrapper-5">TREASURE HUNT</div>
      <div class="text-wrapper-6">TABLE TENNIS</div>
      <div class="text-wrapper-7">JAM</div>
    </div>
  </body>
</html>
```
#### CSS
```css
.iphone-pro-max {
  background-color: #9b4aad;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  position: relative;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 82px;
  left: 9px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 65px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .rectangle {
  top: 229px;
  position: absolute;
  left: 39px;
  width: 351px;
  height: 55px;
  background-color: #682477;
  border: 1px solid;
  border-color: #2b1c1c;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .div {
  top: 327px;
  position: absolute;
  left: 39px;
  width: 351px;
  height: 55px;
  background-color: #682477;
  border: 1px solid;
  border-color: #2b1c1c;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .rectangle-2 {
  top: 425px;
  position: absolute;
  left: 39px;
  width: 351px;
  height: 55px;
  background-color: #682477;
  border: 1px solid;
  border-color: #2b1c1c;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .rectangle-3 {
  top: 523px;
  position: absolute;
  left: 39px;
  width: 351px;
  height: 55px;
  background-color: #682477;
  border: 1px solid;
  border-color: #2b1c1c;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .rectangle-4 {
  top: 621px;
  position: absolute;
  left: 39px;
  width: 351px;
  height: 55px;
  background-color: #682477;
  border: 1px solid;
  border-color: #2b1c1c;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .rectangle-5 {
  top: 719px;
  position: absolute;
  left: 39px;
  width: 351px;
  height: 55px;
  background-color: #682477;
  border: 1px solid;
  border-color: #2b1c1c;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 239px;
  left: 183px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 332px;
  left: 72px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 430px;
  left: 89px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 528px;
  left: 77px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 626px;
  left: 89px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 724px;
  left: 173px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```
### Event Registration
#### HTML
```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="EVENT-REGISTRATION">
        EVENT REGISTRATION<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FORM
      </div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper">Full Name</div>
      <div class="text-wrapper-2">Age</div>
      <div class="text-wrapper-3">Gender</div>
      <div class="text-wrapper-4">Registration number</div>
      <div class="text-wrapper-5">Department</div>
      <div class="text-wrapper-6">Mobile number</div>
      <div class="text-wrapper-7">Email</div>
      <div class="text-wrapper-8">Event Name</div>
    </div>
  </body>
</html>
>
```
#### CSS
```css
.iphone-pro-max {
  background-color: #9b4aad;
  width: 100%;
  min-width: 430px;
  min-height: 932px;
  position: relative;
}

.iphone-pro-max .EVENT-REGISTRATION {
  position: absolute;
  top: 99px;
  left: calc(50.00% - 184px);
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  top: 233px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .div {
  top: 305px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .rectangle-2 {
  top: 377px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .rectangle-3 {
  top: 449px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .rectangle-4 {
  top: 521px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .rectangle-5 {
  top: 593px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .rectangle-6 {
  top: 665px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .rectangle-7 {
  top: 726px;
  position: absolute;
  left: 24px;
  width: 382px;
  height: 49px;
  background-color: #682477;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 237px;
  left: 40px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 308px;
  left: 40px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 380px;
  left: 33px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 451px;
  left: 35px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 524px;
  left: 35px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 597px;
  left: 37px;
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-7 {
  position: absolute;
  top: 668px;
  left: calc(50.00% - 177px);
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .text-wrapper-8 {
  position: absolute;
  top: 730px;
  left: calc(50.00% - 175px);
  font-family: "Jersey 25-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 45px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```
### Thank You Page
#### HTML
```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="text-wrapper">THANK YOU</div>
      <p class="we-are-eagerly">
        We Are Eagerly Waiting For
        Your&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Participation
        In The Event
      </p>
      <img class="element-removebg-preview" src="img/2-removebg-preview-1.png" />
    </div>
  </body>
</html>
```
#### CSS
```css
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <div class="text-wrapper">THANK YOU</div>
      <p class="we-are-eagerly">
        We Are Eagerly Waiting For
        Your&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Participation
        In The Event
      </p>
      <img class="element-removebg-preview" src="img/2-removebg-preview-1.png" />
    </div>
  </body>
</html>

```
## OUTPUT:

<img width="1523" height="1008" alt="image" src="https://github.com/user-attachments/assets/08a9bbba-f823-4795-90c0-b6fef5e667f3" />

<img width="1859" height="1084" alt="image" src="https://github.com/user-attachments/assets/d8100fa2-69bf-47ff-b444-7b439868e4ef" />

<img width="1857" height="1076" alt="image" src="https://github.com/user-attachments/assets/a99d8ba8-08d7-4979-9390-868b870e7a4e" />

<img width="1859" height="1084" alt="image" src="https://github.com/user-attachments/assets/93731871-ef12-40b1-bac1-e47959479768" />

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
