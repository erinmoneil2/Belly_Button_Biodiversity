# Belly_Button_Biodiversity

## Overview 
Belly Button Biodiversity is an interactive website created to help Improbable Beef find a bacteria grown within the human naval to develop and manufacture a synthetic beef. The data analyzes the top ten most commonly found bacteria in each subjects naval, how often each subject washes, and as well as all of the bacteria found within one subject's belly button. 

## Summary 
When you arrive at the webpage, the default screen is displayed below. The first subject ID is for subject 940. All of the charts (bar, gauge, and bubble, will automattically populate with subject 940's information. 
![Screen Shot 2022-01-17 at 12 00 35 PM](https://user-images.githubusercontent.com/92831268/149833352-7c344e43-0755-46aa-a964-afaccbad763e.png)

### Bar Chart 
The bar chart is intended to show the top ten most frequently found bacteria in each subject. This example belows show the top 10 bacteria found in Subject 959. 

<img width="454" alt="Screen Shot 2022-01-17 at 12 12 34 PM" src="https://user-images.githubusercontent.com/92831268/149833997-b2f7e6b6-008a-4854-9e0f-48be9c4951c3.png">


### Bubble Chart 
THe bubble chart shows all of the bacteria found in each subject. The below image shows all of the bacteria for subject 1511. 

<img width="794" alt="Screen Shot 2022-01-17 at 12 13 04 PM" src="https://user-images.githubusercontent.com/92831268/149834148-88dd2d14-a072-4847-9a18-2cb7102343d5.png">


### Gauge Chart 
The gauge chart shows how many times a subject washes their belly button in one week. The below image is of subject 1246 who washes 7 times per week. 

<img width="805" alt="Screen Shot 2022-01-17 at 12 12 44 PM" src="https://user-images.githubusercontent.com/92831268/149834096-911fd62a-c87a-49ca-b3a9-a4a823e9eb97.png">

### Customizations
The following customizations were made to the original webpage.

Original:

![Screen Shot 2022-01-17 at 11 14 12 AM](https://user-images.githubusercontent.com/92831268/149833515-0d5ecce6-27eb-4bfe-bec8-46cc6703ddf7.png)

Customized:

![Screen Shot 2022-01-17 at 12 00 35 PM](https://user-images.githubusercontent.com/92831268/149834464-4dd11e8d-6da3-477a-a8fc-67364847743f.png)


1. I was able to add an image to the jumbotron <div class> by adding an additional style with a backgroun image. 

//<div class="col-md-12 jumbotron text-center" style="background-image: url(https://media.wired.co.uk/photos/606da8809a15f73a597a1f76/master/w_1600,c_limit/Navelgazing.jpg);">
  
2. I was able to change the color of the font to contract the dark image by adding the color white to the font. 
  
//<h1 style="color:white;">Belly Button Biodiversity Dashboard</h1>
   //<p style="color:white;">Use the interactive charts below to explore the dataset</p>
  
3. I was able to change the background of all of the charts by adding a background color within the layout on charts.js.

//paper_bgcolor: "lightsteelblue"
  
4. I added a brief description of each chart by adding it to the HTML file placing the paragraph underneath and centered on each graph. 
  
      //<div class="col-md-5">
        //<div id="bar"></div>
        //<p>This bar graph shows the Top 10 Bacteria cultures found in each subject.</p>
      //</div>
      //<div class="col-md-5">
        //<div id="gauge"></div>
        //<p class=text-center>This gauge chart shows how often a subject washes their belly button per week.</p>
      //</div>
    //</div>
    //<div class="row">
      //<div class="col-md-12">
        //<div id="bubble"></div>
        //<p class=text-center>This bubble chart shows every bacteria that exists within the selected subject's belly button.</p>
      //</div>
