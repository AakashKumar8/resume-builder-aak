# Resume-Builder (AlmaBetter Capstone Project)


## Introduction
* Resume builder is a web application where anyone can create a resume with ease and choose from different available templates.
* It has three tabs: 1) Resume Templates (Home Page), 2)Resumes (Saved Resumes) 3) About us 
* Set profile picture in the resume.
* Before downloading we have a preview option to view your resume.
* You can save resumes to the local hard drive.
* Saved resumes can be deleted as well as modified by the user.

## Used in this project:
* React-Router-Dom
* Material UI
* React-Redux
* Store
* React-Avatar-edit
* Vanilla JS
* JSX
* Uniq ID
* React-Hook-Forms
* Jspdf converter
* Redux connect method
* Images
* Raw data

## Pages
* Home (Resume Templates) <br/> -Choose one from the available templates &amp; <br/> -Navigated to details filling page 
* My Resumes
* About us

## Demo about the pages:
-  *Home Page*
<img width="1120" alt="image" src="https://github.com/user-attachments/assets/ded63fe0-07b6-4e0a-90f7-aae16494c683">

- *Details Filling page*
<img width="1117" alt="image" src="https://github.com/user-attachments/assets/388950b4-c436-4a7b-8a89-4072b02b0d74">

- *My Resumes*
<img width="1120" alt="image" src="https://github.com/user-attachments/assets/b8e0445d-63e4-4276-b356-0cfb01480bc6">

- *About us*
<img width="1119" alt="image" src="https://github.com/user-attachments/assets/3a54bf24-b357-44f8-81f4-1c7fd0979715">

*__Live Link__* <br/>
<b>Click [Here](https://aak-resume-builder.netlify.app/)</b>

</hr>

## Folder Structure
+---public
|       apple-icon.png
|       favicon.ico
|       index.html
|       logo192.png
|       logo512.png
|       manifest.json
|       robots.txt
|       
\---src
    |   App.js
    |   index.css
    |   index.js
    |   Store.js
    |   
    +---Components
    |   |   CheckSelectedId.js
    |   |   
    |   +---BackNextBtn
    |   |       BackNextBtnComponent.css
    |   |       BackNextBtnComponent.js
    |   |       
    |   +---BlackScreen
    |   |       BlackScreen.css
    |   |       BlackScreen.js
    |   |       
    |   +---DetailFillingSidebar
    |   |       DetailFillingSidebar.js
    |   |       DetailsFillingSideBar.css
    |   |       
    |   +---Education
    |   |       EducationComponent.css
    |   |       EducationComponent.js
    |   |       
    |   +---Header
    |   |       TemplateHeader.css
    |   |       TemplateHeader.js
    |   |       
    |   +---Heading
    |   |       TemplateHeading.css
    |   |       TemplateHeading.js
    |   |       
    |   +---Input
    |   |       InputComponent.css
    |   |       InputComponent.js
    |   |       
    |   +---KeySkills
    |   |       KeySkillsComponent.css
    |   |       KeySkillsComponent.js
    |   |       
    |   +---MainBar
    |   |       Navbar.css
    |   |       Navbar.js
    |   |       
    |   +---PersonalInfo
    |   |       PersonalInfoComponent.css
    |   |       PersonalInfoComponent.js
    |   |       
    |   +---Preview
    |   |       PreviewComponent.css
    |   |       PreviewComponent.js
    |   |       
    |   +---Select
    |   |       SelectComponent.css
    |   |       SelectComponent.js
    |   |       
    |   +---TemplateEducation
    |   |       TemplateEducationComponent.css
    |   |       TemplateEducationComponent.js
    |   |       
    |   +---TemplateKeySkill
    |   |       TemplateKeySkillComponent.css
    |   |       TemplateKeySkillComponent.js
    |   |       
    |   +---TemplateOneExperience
    |   |       TemplateOneExperienceComponent.css
    |   |       TemplateOneExperienceComponent.js
    |   |       
    |   \---WorkExperience
    |           WorkExperienceComponent.css
    |           WorkExperienceComponent.js
    |           
    +---Pages
    |   |   AboutUs.js
    |   |   DetailsFilling.js
    |   |   Home.js
    |   |   index.js
    |   |   MyResumes.js
    |   |   
    |   \---Styles
    |           DetailsFilling.css
    |           Home.css
    |           MyResumes.css
    |           
    +---Redux
    |   +---Actions
    |   |       actions.js
    |   |       
    |   \---Reducers
    |           combinedReducers.js
    |           reducers.js
    |           
    \---Utils
        |   inputChecks.js
        |   
        +---Data
        |       data.js
        |       templates.js
        |       
        +---Images
        |       aboutCV.jpg
        |       sample_1.jpg
        |       sample_2.jpg
        |       sample_3.jpg
        |       sample_4.jpg
        |       
        \---Templates
                Template.css
                Template1.js
                Template2.js
                Template3.js
                Template4.js


