# Ex09 Event Registration Web Application
## Date:

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
```
home page

<div data-layer="home page" class="HomePage" style="width: 390px; height: 844px; position: relative; background: #03D2E5">
  <div data-layer="Frame 1" class="Frame1" style="width: 100px; height: 100px; left: 198px; top: 559px; position: absolute"></div>
  <img data-layer="SEC-Logo 1" class="SecLogo1" style="width: 106px; height: 101px; left: 0px; top: 123px; position: absolute" src="https://via.placeholder.com/106x101" />
  <img data-layer="speech 1" class="Speech1" style="width: 3px; height: 2px; left: 132px; top: 277px; position: absolute" src="https://via.placeholder.com/3x2" />
  <div data-layer="DANCE COMPETITION" class="DanceCompetition" style="width: 340px; height: 142px; left: 26px; top: 251px; position: absolute; text-align: center; color: #F7ECEC; font-size: 40px; font-family: Inter; font-weight: 700; word-wrap: break-word">DANCE COMPETITION</div>
  <img data-layer="logo 1" class="Logo1" style="width: 390px; height: 59px; left: 3px; top: 27px; position: absolute" src="https://via.placeholder.com/390x59" />
  <img data-layer="SEC-Logo 5" class="SecLogo5" style="width: 301px; height: 304px; left: 45px; top: 355px; position: absolute; opacity: 0.35" src="https://via.placeholder.com/301x304" />
  <div data-layer="Rectangle 1" class="Rectangle1" style="width: 335px; height: 83px; left: 31px; top: 669px; position: absolute; background: #0AFA0A; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid"></div>
  <div data-layer="Register Now" class="RegisterNow" style="width: 315px; height: 67px; left: 38px; top: 677px; position: absolute; text-align: center; color: black; font-size: 40px; font-family: Inter; font-weight: 500; word-wrap: break-word">Register Now</div>
  <div data-layer="The Dance club of Saveetha Engineering college welcomes everyone to participate in the exclusive inter-college dance competition" class="TheDanceClubOfSaveethaEngineeringCollegeWelcomesEveryoneToParticipateInTheExclusiveInterCollegeDanceCompetition" style="width: 340px; height: 179px; left: 22px; top: 416px; position: absolute; text-align: center; color: black; font-size: 25px; font-family: Inter; font-weight: 800; word-wrap: break-word">The Dance club of Saveetha Engineering college welcomes everyone to participate in the exclusive inter-college dance competition</div>
</div>

/* home page */

position: relative;
width: 390px;
height: 844px;

background: #03D2E5;


/* Frame 1 */

position: absolute;
width: 100px;
height: 100px;
left: 198px;
top: 559px;



/* SEC-Logo 1 */

position: absolute;
width: 106px;
height: 101px;
left: 0px;
top: 123px;

background: url(SEC-Logo.png);


/* speech 1 */

position: absolute;
width: 3px;
height: 2px;
left: 132px;
top: 277px;

background: url(speech.png);


/* DANCE COMPETITION */

position: absolute;
width: 340px;
height: 142px;
left: 26px;
top: 251px;

font-family: 'Inter';
font-style: normal;
font-weight: 700;
font-size: 40px;
line-height: 48px;
text-align: center;

color: #F7ECEC;

text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);


/* logo 1 */

position: absolute;
width: 390px;
height: 59px;
left: 3px;
top: 27px;

background: url(logo.png);


/* SEC-Logo 5 */

position: absolute;
width: 301px;
height: 304px;
left: 45px;
top: 355px;

background: url(SEC-Logo.png);
opacity: 0.35;


/* Rectangle 1 */

box-sizing: border-box;

position: absolute;
width: 335px;
height: 83px;
left: 31px;
top: 669px;

background: #0AFA0A;
border: 1px solid #000000;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);


/* Register Now */

position: absolute;
width: 315px;
height: 67px;
left: 38px;
top: 677px;

font-family: 'Inter';
font-style: normal;
font-weight: 500;
font-size: 40px;
line-height: 48px;
text-align: center;

color: #000000;



/* The Dance club of Saveetha Engineering college welcomes everyone to participate in the exclusive inter-college dance competition */

position: absolute;
width: 340px;
height: 179px;
left: 22px;
top: 416px;

font-family: 'Inter';
font-style: normal;
font-weight: 800;
font-size: 25px;
line-height: 30px;
text-align: center;

color: #000000;


dance-styles

<div data-layer="dance-styles " class="DanceStyles" style="width: 390px; height: 844px; position: relative; background: #F718EF">
  <img data-layer="SEC-Logo 3" class="SecLogo3" style="width: 301px; height: 304px; left: 46px; top: 342px; position: absolute; opacity: 0.50" src="https://via.placeholder.com/301x304" />
  <div data-layer="Line 3" class="Line3" style="width: 390px; height: 0px; left: 0px; top: 117px; position: absolute; background: #B30C0C; border: 4px #1C1CFD solid"></div>
  <img data-layer="logo 3" class="Logo3" style="width: 390px; height: 59px; left: 0px; top: 31px; position: absolute" src="https://via.placeholder.com/390x59" />
  <div data-layer="Rectangle 9" class="Rectangle9" style="width: 317px; height: 598px; left: 36px; top: 127px; position: absolute; opacity: 0.30; background: black; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid"></div>
  <div data-layer="Classical Dance Western Dance Hip-Hop Free-style Folk Dance    Contemporary Dance    Tango Dance    ballet Dance    Jazz Tap Dance .. or other" class="ClassicalDanceWesternDanceHipHopFreeStyleFolkDanceContemporaryDanceTangoDanceBalletDanceJazzTapDanceOrOther" style="width: 236px; height: 507px; left: 86px; top: 202px; position: absolute; color: white; font-size: 20px; font-family: Inter; font-weight: 300; word-wrap: break-word"> Classical Dance<br/> <br/> Western Dance<br/><br/> Hip-Hop<br/><br/> Free-style<br/><br/> Folk Dance   <br/> Contemporary Dance   <br/> Tango Dance   <br/> ballet Dance   <br/> Jazz<br/><br/> Tap Dance<br/><br/> .. or other<br/>  <br/></div>
  <div data-layer="DANCE STYLES" class="DanceStyles" style="width: 251px; height: 52px; left: 65px; top: 150px; position: absolute; text-align: center; color: white; font-size: 25px; font-family: Inter; font-weight: 700; word-wrap: break-word">DANCE STYLES</div>
  <div data-layer="Rectangle 9" class="Rectangle9" style="width: 254px; height: 47px; left: 68px; top: 786px; position: absolute; background: #0AFA0A; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid"></div>
  <div data-layer="REGISTER" class="Register" style="width: 232px; height: 33px; left: 75px; top: 793px; position: absolute; text-align: center; color: black; font-size: 25px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTER</div>
</div>

/* dance-styles  */

position: relative;
width: 390px;
height: 844px;

background: #F718EF;


/* SEC-Logo 3 */

position: absolute;
width: 301px;
height: 304px;
left: 46px;
top: 342px;

background: url(SEC-Logo.png);
opacity: 0.5;


/* Line 3 */

position: absolute;
width: 390px;
height: 0px;
left: 0px;
top: 117px;

background: #B30C0C;
border: 4px solid #1C1CFD;


/* logo 3 */

position: absolute;
width: 390px;
height: 59px;
left: 0px;
top: 31px;

background: url(logo.png);


/* Rectangle 9 */

box-sizing: border-box;

position: absolute;
width: 317px;
height: 598px;
left: 36px;
top: 127px;

background: #000000;
opacity: 0.3;
border: 1px solid #000000;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);


/* Classical Dance Western Dance Hip-Hop Free-style Folk Dance  Contemporary Dance  Tango Dance  ballet Dance  Jazz Tap Dance .. or other */

position: absolute;
width: 236px;
height: 507px;
left: 86px;
top: 202px;

font-family: 'Inter';
font-style: normal;
font-weight: 300;
font-size: 20px;
line-height: 24px;

color: #FFFFFF;



/* DANCE STYLES */

position: absolute;
width: 251px;
height: 52px;
left: 65px;
top: 150px;

font-family: 'Inter';
font-style: normal;
font-weight: 700;
font-size: 25px;
line-height: 30px;
text-align: center;

color: #FFFFFF;



/* Rectangle 9 */

box-sizing: border-box;

position: absolute;
width: 254px;
height: 47px;
left: 68px;
top: 786px;

background: #0AFA0A;
border: 1px solid #000000;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);


/* REGISTER */

position: absolute;
width: 232px;
height: 33px;
left: 75px;
top: 793px;

font-family: 'Inter';
font-style: normal;
font-weight: 800;
font-size: 25px;
line-height: 30px;
text-align: center;

color: #000000;

register page

<div data-layer="register page" class="RegisterPage" style="width: 390px; height: 844px; position: relative; background: #F0FC0C">
  <div data-layer="Line 2" class="Line2" style="width: 390px; height: 0px; left: 0px; top: 114px; position: absolute; background: #B30C0C; border: 4px #1C1CFD solid"></div>
  <img data-layer="SEC-Logo 2" class="SecLogo2" style="width: 96px; height: 98px; left: 0px; top: 114px; position: absolute" src="https://via.placeholder.com/96x98" />
  <img data-layer="logo 2" class="Logo2" style="width: 390px; height: 59px; left: 0px; top: 27px; position: absolute" src="https://via.placeholder.com/390x59" />
  <img data-layer="SEC-Logo 4" class="SecLogo4" style="width: 301px; height: 304px; left: 48px; top: 354px; position: absolute; opacity: 0.50" src="https://via.placeholder.com/301x304" />
  <div data-layer="Rectangle 2" class="Rectangle2" style="width: 160px; height: 43px; left: 113px; top: 253px; position: absolute; background: #FEF9F9"></div>
  <div data-layer="Rectangle 3" class="Rectangle3" style="width: 160px; height: 43px; left: 113px; top: 311px; position: absolute; background: #FEF9F9"></div>
  <div data-layer="Rectangle 4" class="Rectangle4" style="width: 160px; height: 43px; left: 113px; top: 369px; position: absolute; background: #FEF9F9"></div>
  <div data-layer="Rectangle 5" class="Rectangle5" style="width: 160px; height: 43px; left: 113px; top: 427px; position: absolute; background: #FEF9F9"></div>
  <div data-layer="Rectangle 6" class="Rectangle6" style="width: 160px; height: 43px; left: 113px; top: 491px; position: absolute; background: #FEF9F9"></div>
  <div data-layer="Rectangle 7" class="Rectangle7" style="width: 160px; height: 43px; left: 113px; top: 562px; position: absolute; background: #FEF9F9"></div>
  <div data-layer="Name :" class="Name" style="width: 96px; height: 28px; left: 17px; top: 260px; position: absolute; text-align: center; color: #D61313; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Name :</div>
  <div data-layer="college :" class="College" style="width: 96px; height: 28px; left: 7px; top: 319px; position: absolute; text-align: center; color: #D61313; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">college :</div>
  <div data-layer="year :" class="Year" style="width: 96px; height: 28px; left: 22px; top: 384px; position: absolute; text-align: center; color: #D61313; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">year :</div>
  <div data-layer="dept :" class="Dept" style="width: 96px; height: 28px; left: 22px; top: 434px; position: absolute; text-align: center; color: #D61313; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">dept :</div>
  <div data-layer="Ph no. :" class="PhNo" style="width: 96px; height: 28px; left: 13px; top: 499px; position: absolute; text-align: center; color: #D61313; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">Ph no. :</div>
  <div data-layer="dance style :" class="DanceStyle" style="width: 96px; height: 49px; left: 16px; top: 559px; position: absolute; text-align: center; color: #D61313; font-size: 20px; font-family: Inter; font-weight: 400; word-wrap: break-word">dance <br/>style :</div>
  <div data-layer="Rectangle 8" class="Rectangle8" style="width: 254px; height: 47px; left: 69px; top: 675px; position: absolute; background: #0AFA0A; box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25); border: 1px black solid"></div>
  <div data-layer="SUBMIT" class="Submit" style="width: 232px; height: 33px; left: 81px; top: 682px; position: absolute; text-align: center; color: black; font-size: 25px; font-family: Inter; font-weight: 800; word-wrap: break-word">SUBMIT</div>
</div>

/* register page */

position: relative;
width: 390px;
height: 844px;

background: #F0FC0C;


/* Line 2 */

position: absolute;
width: 390px;
height: 0px;
left: 0px;
top: 114px;

background: #B30C0C;
border: 4px solid #1C1CFD;


/* SEC-Logo 2 */

position: absolute;
width: 96px;
height: 98px;
left: 0px;
top: 114px;

background: url(SEC-Logo.png);


/* logo 2 */

position: absolute;
width: 390px;
height: 59px;
left: 0px;
top: 27px;

background: url(logo.png);


/* SEC-Logo 4 */

position: absolute;
width: 301px;
height: 304px;
left: 48px;
top: 354px;

background: url(SEC-Logo.png);
opacity: 0.5;


/* Rectangle 2 */

position: absolute;
width: 160px;
height: 43px;
left: 113px;
top: 253px;

background: #FEF9F9;


/* Rectangle 3 */

position: absolute;
width: 160px;
height: 43px;
left: 113px;
top: 311px;

background: #FEF9F9;


/* Rectangle 4 */

position: absolute;
width: 160px;
height: 43px;
left: 113px;
top: 369px;

background: #FEF9F9;


/* Rectangle 5 */

position: absolute;
width: 160px;
height: 43px;
left: 113px;
top: 427px;

background: #FEF9F9;


/* Rectangle 6 */

position: absolute;
width: 160px;
height: 43px;
left: 113px;
top: 491px;

background: #FEF9F9;


/* Rectangle 7 */

position: absolute;
width: 160px;
height: 43px;
left: 113px;
top: 562px;

background: #FEF9F9;


/* Name : */

position: absolute;
width: 96px;
height: 28px;
left: 17px;
top: 260px;

font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #D61313;



/* college : */

position: absolute;
width: 96px;
height: 28px;
left: 7px;
top: 319px;

font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #D61313;



/* year : */

position: absolute;
width: 96px;
height: 28px;
left: 22px;
top: 384px;

font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #D61313;



/* dept : */

position: absolute;
width: 96px;
height: 28px;
left: 22px;
top: 434px;

font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #D61313;



/* Ph no. : */

position: absolute;
width: 96px;
height: 28px;
left: 13px;
top: 499px;

font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #D61313;



/* dance style : */

position: absolute;
width: 96px;
height: 49px;
left: 16px;
top: 559px;

font-family: 'Inter';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 24px;
text-align: center;

color: #D61313;



/* Rectangle 8 */

box-sizing: border-box;

position: absolute;
width: 254px;
height: 47px;
left: 69px;
top: 675px;

background: #0AFA0A;
border: 1px solid #000000;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25), 0px 4px 4px rgba(0, 0, 0, 0.25);


/* SUBMIT */

position: absolute;
width: 232px;
height: 33px;
left: 81px;
top: 682px;

font-family: 'Inter';
font-style: normal;
font-weight: 800;
font-size: 25px;
line-height: 30px;
text-align: center;

color: #000000;


```

## OUTPUT:
![alt text](<Screenshot (54).png>)
![alt text](<Screenshot (55).png>)
![alt text](<Screenshot (56).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
