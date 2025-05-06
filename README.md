A Wepage in Cheetah Genomics

Alexandra Chichester

Abstract: The purpose of this project was to design a webpage in html with the purpose of informing the reader about cheetah genomics. This was done by researching papers with different experiments revolving around cheetah conservation genomics and why it is so important for conservationists to undertand genetic diversity. This project wss purposed and completed with the intention of researching more about the cheetah population's low genetic diversity and what contributes to them being endangered. 

Introduction: 

Cheetahs are one of the most well known felines in  the world. They are known for their iconic speed and signature spotted fur, evolutionary adaptations like their slim bodies abd long limbs. However, conservation efforts have been needed now more than ever as their population has dropped significantly over the course of their histroy. Now standing at fewer than 7,000 if the big cats left

Methods:

<!DOCTYPE html> # declares what document type is being used, 
<html lang="en"> # specifies the language if the document
<head> # opens the head section for information about the webpage,
<title>Conservation Genetics on Cheetahs</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif, Times New Roman;
  margin: 0;
}
/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: Black;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: LightGray;
  color: black;
}


}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
