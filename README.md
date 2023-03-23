# African Presidents
   + URL: https://f-clement.github.io/famous-african-presidents/index.html

African Presidents is a website that aims at providing lovers of history (political history) with the history of famous African leaders. This is achieved by stating different categories of fame like wealth, term of reign achievements and education.  The site also provides an opportunity for interested persons in African to vote for the best president ever in their history. 

![Screenshot of home page](/assets/images/home-page.png)

## Existing Features
**Navigation Bar**
+ Featured on all pages is the sites navigation bar that provides links to the homepage, presidents and the best president page where you can vote. This navigation bar is fully responive and identical in each page to allow for easy navigation.

+ Using the navigation bar will allow users to easily navigate through out the website without having to use the revert back to the previous page button on browsers.

**Landing Page**

+ The landing page at first instance displays a catchy image which is a gride of various African Presidents which a good number if not all Africans will search to see if they find their presidents.

![Hero Image](/assets/images/hero-image.png)

**Famous Presidents Section**
+ This section displays four famous African presidents and brief history of each of them. 
Fontawesome logos are also placed besides each of their names to demonstrate the kind of person they were.

![Famous Presidents](/assets/images/famous-presidents.png)

**Fame category section**

+ In this section we considered four categories of fame. We have wealth, term of reign, achievements and education.
+ For each category of fame you can see the top three African Presidents that dominate.

![Fame Categories](/assets/images/fame-categories.png)

**The Footer**

+ The footer section for this website display three links to external website (wikipedia, Google and Youtube) were you can read more about any of the Presidents you might be interested in. These links open in a new tab when clicked.
+ This section is thesame for all pages as it improves first time user learner experience.

![Footer Section](/assets/images/footer.png)

**Presidents**
+ This page provides the user with clearer images of African presidents

![Pictures of Presidents](/assets/images/presidents.png)

**Best President**

+ This page allows interested users to vote for their best president. The exercise is open to the world at large and in particular to Africans.

![Vote Best President](/assets/images/best-president.png)

**Vote Confirmation**
+ After filling the form to vote for the best president, you then get a confirmation to let you know you have completed the voting process.

![Vote Confirmed](/assets/images/confirmation.png)

## Features Left to Implement

**Presidents**
Where we have clearer pictures of the presidents, we want that when an image is clicked, the complete history of that particular president should be displayed together with the same image on a different page.

## Testing

<table>
<tr>
<th> Action</th>
<th>Expected Results</th>
<th>Actual Results</th>
</tr>

<tr>
<td>Entering the live url for African Presidents</td>
<td>Home page loads</td>
<td>Pass</td>
</tr>

<tr>
<td>Click on the Wikipedia link in the footer</td>
<td>Opens the home page of Wikipedia in a new tab</td>
<td>Pass</td>
</tr>

tr>
<td>Click on the Google link in the footer</td>
<td>Opens the home page of Google in a new tab</td>
<td>Pass</td>
</tr>

tr>
<td>Click on the Youtube link in the footer</td>
<td>Opens the home page of Youtube in a new tab</td>
<td>Pass</td>
</tr>


<tr>
<td>Click on Vote Now button without filling any of the form fields</td>
<td>First name field calls for your attention to fill it out</td>
<td>Pass</td>
</tr>

<tr>
<td>Filll only first name field and then click the Vote Now button</td>
<td>Second name field calls for your attention to fill it out</td>
<td>Pass</td>
</tr>

<tr>
<td>Filll first name and second name field then click the Vote Now button</td>
<td>Email address field calls for your attention to fill it out</td>
<td>Pass</td>
</tr>

<tr>
<td>Filll only first name, second name and email address field and then click the Vote Now button</td>
<td>Datalist field calls for your attention to select or input your choice of president</td>
<td>Pass</td>
</tr>

<tr>
<td>Click Vote Now button after filling all fields but with a wrong format email address in the email address field</td>
<td>Email address field calls for your attention to correct the email</td>
<td>Pass</td>
</tr>

<tr>
<td>Click Vote Now button after filling all fields correctly</td>
<td>Vote is confirmed and takes you to a confirmation page in the same website</td>
<td>Pass</td>
</tr>

<tr>
<td>Click Home on navigation menu</td>
<td>Home page of our websites loads</td>
<td>Pass</td>
</tr>

<tr>
<td>Click Presidents on the navigation menutd>
<td>Navigates to a page containing pictures of african presidents</td>
<td>Pass</td>
</tr>

<tr>
<td>Click on "Best President" on the navigation menum</td>
<td>Navigates to a page where you can vote for the best African president</td>
<td>Pass</td>
</tr>

<tr>
<td>Test website on different screen sizes</td>
<td>It is responsive</td>
<td>Pass</td>
</tr>

</table>
**Responsive Test**

![Lighthouse desktop Test](/assets/images/responsive.png)


### Validator Testing
**HTML**
+ The code passed through the official [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Ff-clement.github.io%2Ffamous-african-presidents%2Findex.html) without any errors.

**CSS**
+ The code passed through the [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Ff-clement.github.io%2Ffamous-african-presidents%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en) without any errors.


**Lighthouse**
+ The website was tested on lighthouse in devtools and the results are good as seen below.
  + Desktop Results

![Lighthouse desktop Test](/assets/images/lighthouse-test.png)

  + Mobile Results

![Lighthouse mobile test](/assets/images/lighthouse-mobile.png)

## Deployment
This site was deployed to GitHub pages using the following steps:
+ In GitHub repository, nagivate to the settings tab
+ Click on pages in the left columng 
+ From the source section drop-down munu, select main and save
+ Then refresh your page and and you will see it has been successfully deployed with the live link available. It can take a few minutes at times.

+ The live link for African President is: https://f-clement.github.io/famous-african-presidents/index.html

## Credits

**Design**
+ The design of the landing page is thanks to the [code institute](https://code-institute-org.github.io/love-running-2.0/index.html) love running project.
+ We then used balsamiq to design a wirframe that looks almost exactly as that of the love running project as seen below.

  + Wireframe for desktop view of home page

![Wireframe](/assets/images/wireframe.png)

  + Wireframe for desktop view of presidents page

![Wireframe](/assets/images/presidents-desktop-wireframe.png)

  + Wireframe for desktop view of best president page

![Wireframe](/assets/images/vote-desktop-wireframe.png)

  + Wireframe for tablet view of home page

![Wireframe](/assets/images/home-tablet-wirefram.png)

  + Wireframe for tablet view of presidents page

![Wireframe](/assets/images/presidents-tablet-wirframe.png)

  + Wireframe for mobile view of home page

![Wireframe](/assets/images/mobile-wirefram.png)

**Content**
+ Content for this project comes from several websites after researching on Google.
+ The famous president sections information comes from [Wikipedia](https://www.wikipedia.org/)
+ The fame categories content is gotten as follows:
  + [Wealth](https://peakng.com/richest-presidents-in-africa/)
  + Achievements: Personal believe.
  + [Term of reign](https://furtherafrica.com/2022/08/13/7-africas-longest-serving-presidents/)
  + [Education](https://www.nairaland.com/2162675/robert-mugabe-tops-most-educated)
+ Icons on the famous president section are from the [Fonts Awesome](https://fontawesome.com/icons) website.

**Media**
+ The hero image is from [sporcle](https://www.sporcle.com/games/OneoftheBhoys/20th-century-african-leader-click)
+ All other images used here are images gotten from Google.

**Code**
+ The code to keep the arrow pointing down in the voting form was gotten from [stackoverflow](https://stackoverflow.com/questions/35196782/how-to-make-datalist-arrow-to-be-always-visible)
