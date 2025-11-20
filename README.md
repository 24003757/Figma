# Ex09 Event Registration Web Application
## Date:20.11.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
page 1:
```
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
      <img class="chess" src="img/chess-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper">REGISTER</div>
      <img class="screenshot" src="img/screenshot-2025-11-15-140134-removebg-preview-1.png" />
      <div class="CHESS-COMPETITION">CHESS<br />COMPETITION..!</div>
    </div>
  </body>
</html>

style.css :
.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 425px;
  min-height: 802px;
  position: relative;
}

.iphone-pro-max .chess {
  position: absolute;
  top: 0;
  left: 0;
  width: 425px;
  height: 802px;
  aspect-ratio: 1.01;
  object-fit: cover;
}

.iphone-pro-max .text-on-a-path {
  position: absolute;
  top: 546px;
  left: 786px;
  width: 227px;
  height: 41px;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 632px;
  left: 34px;
  width: 352px;
  height: 79px;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 636px;
  left: 92px;
  width: 289px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #03081c;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-pro-max .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 420px;
  height: 96px;
  aspect-ratio: 4.54;
  object-fit: cover;
}

.iphone-pro-max .CHESS-COMPETITION {
  position: absolute;
  top: 190px;
  left: 78px;
  width: 324px;
  font-family: "Inter-Italic", Helvetica;
  font-weight: 400;
  font-style: italic;
  color: #06072c;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

```
page 2 :
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone">
      <img class="element-chess" src="img/3-chess-1.png" />
      <div class="UNDER">UNDER 8YRS-10YRS<br /><br />UNDER 10YRS-13YRS<br /><br />UNDER 13YRS-15YRS</div>
      <div class="text-wrapper">ELIGIBLE AGE CATEGORY</div>
      <img class="rectangle" src="img/rectangle-2.svg" />
    </div>
  </body>
</html>

style.css :
.iphone {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 424px;
  min-height: 802px;
  position: relative;
}

.iphone .element-chess {
  position: absolute;
  top: 0;
  left: 0;
  width: 424px;
  height: 802px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone .UNDER {
  position: absolute;
  top: 156px;
  left: 0;
  width: 353px;
  font-family: "Inter-SemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .text-wrapper {
  position: absolute;
  top: 65px;
  left: 28px;
  width: 410px;
  font-family: "JejuGothic-Regular", Helvetica;
  font-weight: 400;
  color: #06072c;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone .rectangle {
  position: absolute;
  top: 216px;
  left: 666px;
  width: 294px;
  height: 60px;
}


```
page 3:
```
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
      <div class="text-wrapper">EVENT REGISTRATION</div>
      <img class="skull" src="img/skull-1.png" />
      <div class="div">Mobile :</div>
      <div class="rectangle"></div>
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">Name :</div>
      <div class="dept">Dept&nbsp;&nbsp;&nbsp;&nbsp;:</div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="text-wrapper-3">Reg NO:</div>
      <div class="text-wrapper-4">Email Id :</div>
      <div class="rectangle-6"></div>
      <div class="select-event">Select <br />Event</div>
      <div class="text-wrapper-5">:</div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-6">SUBMIT</div>
    </div>
  </body>
</html>

style.css:
.iphone-pro-max {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 427px;
  min-height: 802px;
  position: relative;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 25px;
  left: 48px;
  width: 407px;
  font-family: "JejuMyeongjo-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .skull {
  position: absolute;
  top: 0;
  left: 0;
  width: 427px;
  height: 802px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .div {
  position: absolute;
  top: 355px;
  left: 26px;
  font-family: "Poppins-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 91px;
  left: 154px;
  width: 260px;
  height: 51px;
  background-color: #d9d9d9;
  border-radius: 55px;
}

.iphone-pro-max .rectangle-2 {
  position: absolute;
  top: 179px;
  left: 154px;
  width: 260px;
  height: 49px;
  background-color: #d9d9d9;
  border-radius: 55px;
}

.iphone-pro-max .text-wrapper-2 {
  position: absolute;
  top: 91px;
  left: 26px;
  font-family: "Poppins-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .dept {
  position: absolute;
  top: 267px;
  left: 26px;
  font-family: "Poppins-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-3 {
  position: absolute;
  top: 265px;
  left: 154px;
  width: 260px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: 20px;
  border: 1px solid;
  border-color: #000000;
}

.iphone-pro-max .rectangle-4 {
  position: absolute;
  top: 352px;
  left: 154px;
  width: 260px;
  height: 51px;
  background-color: #d9d9d9;
  border-radius: 20px;
}

.iphone-pro-max .rectangle-5 {
  position: absolute;
  top: 440px;
  left: 154px;
  width: 260px;
  height: 50px;
  background-color: #d9d9d9;
  border-radius: 20px;
}

.iphone-pro-max .text-wrapper-3 {
  position: absolute;
  top: 179px;
  left: 26px;
  font-family: "Poppins-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-4 {
  position: absolute;
  top: 441px;
  left: 6px;
  font-family: "Poppins-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-6 {
  position: absolute;
  top: 542px;
  left: 154px;
  width: 260px;
  height: 99px;
  background-color: #d9d9d9;
  border-radius: 20px;
}

.iphone-pro-max .select-event {
  position: absolute;
  top: 542px;
  left: 6px;
  font-family: "Poppins-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .text-wrapper-5 {
  position: absolute;
  top: 566px;
  left: 129px;
  font-family: "Poppins-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle-7 {
  position: absolute;
  top: 693px;
  left: 83px;
  width: 256px;
  height: 54px;
  background-color: #d22c2c;
  border-radius: 30px;
  box-shadow: 0px 4px 4px #00000040;
}

.iphone-pro-max .text-wrapper-6 {
  position: absolute;
  top: 694px;
  left: 129px;
  width: 225px;
  font-family: "Poppins-Black", Helvetica;
  font-weight: 900;
  color: #ffffff;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

```
page 4:
```
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <div class="thank-you-for">Thank You<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For<br />Registering</div>
      <p class="contact-us-email">
        <span class="text-wrapper">contact us :<br /><br />Email : </span>
        <span class="span">vinochess@gmail.com<br /></span>
        <span class="text-wrapper"><br />phone : +91xxxxxxxxxx</span>
      </p>
    </div>
  </body>
</html>

style.css:

.frame {
  background-color: #031663;
  width: 100%;
  min-width: 427px;
  min-height: 802px;
  display: flex;
  flex-direction: column;
  gap: 48px;
}

.frame .thank-you-for {
  margin-left: 90px;
  width: 246px;
  height: 198px;
  margin-top: 122px;
  -webkit-text-stroke: 1px #701f1f;
  font-family: "Oleo Script-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 3.36px;
  line-height: normal;
}

.frame .contact-us-email {
  width: 410px;
  height: 316px;
  font-family: "Oleo Script-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 40px;
  line-height: normal;
}

.frame .text-wrapper {
  letter-spacing: 1.12px;
}

.frame .span {
  font-size: 32px;
  letter-spacing: 0;
}
```
## OUTPUT:
![alt text](<Screenshot 2025-11-20 145152.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
