<h2>World Travel Guide</h2>
<h3>AIM</h3>
<p>The aim of this project was to create and build an interactive front-end site, that responds to the user’s actions, allowing users to actively engage with data; using HTML, CSS and JavaScript. The World Travel Guide would allow users to search for their next city break and help users find hotels, restaurants, shopping, spa and art galleries.</p>

<p>The website contains various articles, that highlight the best countries to visit for that experience.
 Some of the articles I chose to present were:</p>
<ul>
<li>Shopping</li>
<li> Best Dessert places</li>
<li> Most Popular Waterfalls etc</li>
</ul>
<p>I have also included a Google Map, with a search bar that allows you to search for the city in your desired country and filter the results by clicking on one of the checkboxes provided.</p>

<p>By Including a map on the page, it gives the user an insight to the destination they are looking to travel to, and by being able to filter the results it will help the user see the distance between everything.
For instance, the user might want to travel from London to Manchester to Scotland; by using the map they can now see the closest hotels to the airport as well as where the nearest restaurants, shopping malls and spas are.</p>

<p>Along with the map and articles, I have also added a personal package section where once clicked the user can fill out a form to enquire about creating their personal travel package.</p>

<p>I have created a very simple layout, in hope all users both young and old, will find it easy to navigate.</p>

<h3>Demo</h3>
Please click on the link below to view my site 
<href https://saffiya.github.io/Interactive-FrontEnd-Development-Milestone-Project/ >
<h3>UX</h3>
<p>The goal for this design was to make it as easy as possible to access information on the site, whilst striving for a fun yet simple design; that is easy to navigate and use. The colour palette strives for simplicity. There are three very consistent colours that are seen throughout the site; # charcoal, white and # light pink. The # pink was a shade found in my image and the #charcoal was used as a contrasting colour.</p> 

<p>Wireframes can be viewed by this link: <href https://balsamiq.cloud/soofkeb/prgilkf></p>

<p>The following goals are what I wanted to achieve for this website:</p>
<ul>
<li>I wanted to choose the country and city where my city break will be</li>
<li>I wanted there to be multiple countries to choose from so all areas in the world are covered</li>
<li>I want a map to centre on the city I select</li>
<li>I want the map to show me points of interest (POI) like hotels, restaurants, shopping malls, spa, art gallery and train stations when clicked on</li>
<li>I want to be able to use this on different screen sizes</li>
<li>I want to be able to move around on the map</li>
<li>I wanted more information to be displayed about the POI when clicked on such as star rating</li>
<li>I wanted there to be articles about best places around the world that once clicked on would go straight to the article</li>
<li>I wanted a form that could be filled out to enquire about a travel package </li>
</ul>
<p>The start of the site has an opening message welcoming the user and telling the user what they can expect to find on the site. I placed an image with a transparent overlay to make the white text stand out. To define the text further I made the font weight bold.
Below the image is a map that I created using Google Maps Place Autocomplete Hotel Search, I adjusted the code so that users are able to search for more than just hotels and added interactive checkboxes which the user is able to click on to filter the outcome according to their needs.
After the maps is an article section that has individual articles that when clicked takes the user to the article. 
At the end of the page I placed a Personal package section for users to fill in so that they are able to enquire a personalised travel package. I did this using a button which led to a modal form.</p>

<h3>Features</h3>

<p>Features on this website are:</p>
<ul>
<li>The country input field has an autocomplete function to aide the user in selecting/finding the city they wish to find</li>
<li>Markers on the map when clicked or tapped bring up an info window with detailed information about that POI</li>
<li>The results cards are linked to the map and when clicked or tapped will bring up its respected info window for additional information</li>
<li>The form has required fields so users have to type in their full name, email etc</li>
<li>The booking form send the information to an email address using emailJS</li>
<li>The modal can be closed using the close cross</li>
</ul>
<h3>Technologies Used</h3>
<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
<li>Google API</li>
<li>Bootstrap (Used for its grid system, button, modal, form and pagelayout)</li>
<li>Fontawesome (Used for the down arrow icon)</li>
<li>AWS Cloud9 used to write the code </li>
<li>Balsamiq used to create the wireframe</li>
<li>Google Fonts</li>
<li>Git</li>
<li>GitHub</li>
<li>Google (Used to find and attach articles and find copyright free images</li>
</ul>
<h3>Testing</h3>
<p>The site was tested across multiple browsers:</p>
<ul>
<li>Safari</li>
<li>Yahoo</li>
<li>Chrome</li>
<li>Google</li>
<li>Internet Explorer</li>
</ul>
<p>Also on multiple devices:</p>
<ul>
<li>Iphone 5-8</li>
</ul>
<p>To ensure compatability and responsiveness I also asked friends and family to test it across their devices to make sure it worked properly and was easy to use.</p>

<p>During Testing stages I came across a range of problems with my code most being with my map. 
Such as:</p>
<ul>
<li>The map wasn’t loading all the places in that area</li>
<li>The maps filter wasn’t working as planned and instead of just showing a specific thing like restaurants it was showing everything</li>
<li>As it was my first time adding in an API I tried and tested a few different add ons to my API link in order to make it work as wanted; in the end I added libraries=places&callback=initMap</li>
<li>The checkboxes alignment weren’t where I wanted them on different screens which was actually a very easy fix</li>
<li>At times the map would show, but that was due to restrictions placed on the API which I adjusted.</li>
<li>The article section spread over the page leaving large white spaces on the sides of my page which I fixed with a overflow and by adjusting the size of the images on screen </li>

<h3>Deployment</h3>
<p>The website was created with AWS Cloud 9 using Ubuntu with BASH. Git was used for version control and pushed to a repository hosted on Github.
The website is deployed using Github</p>

<p>How to deploy the code locally</p>
<ul>
<li>Download the code from the Github repository at:  https://saffiya.github.io/Interactive-FrontEnd-Development-Milestone-Project/</li>
<li>Click on Clone or download then Download ZIP, This will downloaf the code into a ZIP folder locally on your computer</li>
<li>Uncompress the ZIP folder</li>

<h3>Credits</h3>


