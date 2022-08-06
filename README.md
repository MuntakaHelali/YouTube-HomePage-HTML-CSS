<h1> YouTube-HomePage-HTML-CSS </h1>


The YouTube webpage was recreated using features of HTML and CSS. At a first glance, the webpage is almost identical to the main YouTube Home Page presented to a user that is logged in to an account. However, there are some additional functionalites implemented to showcase more advance techniques of using HTML and CSS.

<h2>Header</h2>
Staring with the top of the webpage, the header was created by splitting it into 3 sections, left, middle, and right. This was done using a main header container using the flex property with a fixed position to keep the header at the top of the page. Within, the header container, the first container created was the left. The left container contains the Hamburger icon menu and the YouTube Logo that is used in <a href=https://youtube.com/>YouTube.com</a>. 
<br>
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/57158277/183236554-91b1a27b-503d-4c35-b342-71a02729e9d5.png" width="250">
</p>
<br>
<br>
Next looking at the center of the header container, the middle section consists of the search bar, search icon, and search with your voice icon. Using the flex property for the middle-section container it was simple to add a button with the search bar to contain the search logo and add the voice search logo beside both. As the user screen size decreases, thanks to the usage of the flex-shrink property, the search bar shrinks so that the right section is in focus on smaller screen sizes. 
<br>
<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/57158277/183237281-0ea227d3-84a3-4259-98a9-593590810916.png" width="1050">
  Webpage when the max-width of the middle section container is greater than 500px
  <br>
  <br>
  <img src="https://user-images.githubusercontent.com/57158277/183237310-bb92c807-dd2c-4290-b4db-f07cb8606a7d.png" width="550">
  <br>
  <br>
  Webpage when the max-width of the middle section container is less than 500px 
</p>
<br>
<br>
The last part of the header is the right section. This is where the YouTube Create, Apps, Notification, and User icons are placed. This was done by using the flex property in the right section and spacing the contents of the container evenly. To replicate the functionality of the user clicking on their profile, if you hover over the user icon, a menu is displayed showing more options available to their disposal. 
  <br>
  <br>
  <p align="center">
  <img src="https://user-images.githubusercontent.com/57158277/183237775-4a331da7-ff5a-4df4-b0fe-c24e9f3b9bef.png" width="550">
  </p>
  <br>
  <br>
In the header, for all the icons in the middle and right section except for the user, there is a tooltip created so that when the user hovers over them, they can know what the icons/button functionality performs. Also, the Notification icon shows the number of notifications the user has not read, which was replicated using the position feature by having an absolute property within a relative position property. 
<br>
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/57158277/183237946-2e5dec3b-3805-44e1-a419-13eb11cdbb19.png" width="100" height="100">
<img src="https://user-images.githubusercontent.com/57158277/183237971-97c2948c-ddc6-49c7-8ea9-3e075d7b057b.png" width="200" height="100">
<img src="https://user-images.githubusercontent.com/57158277/183237979-2f4d0b34-6c00-4321-a004-885e9f7e8f5d.png" width="100" height="100">
<img src="https://user-images.githubusercontent.com/57158277/183238003-5f74e1ee-26ef-41bf-864e-99becb736e78.png" width="200" height="100">
<img src="https://user-images.githubusercontent.com/57158277/183238012-08c9b40f-8e61-4dd2-af20-46c975ff50c8.png" width="200" height="100">
</p>
<br>
<br>
<h2>Sidebar</h2>
The sidebar was implemented in a similar manner as the header, by making use of the nav and position element with a fixed property. The major difference from the header is that there are media queries used so that the contents of the sidebar change depending on the size of the user's display. If the width of the web-page is less than 1200px then this will be displayed: 
<br>
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/57158277/183262906-db8fed6d-cb81-41fc-8ace-eba8a9fd7402.png" width="550">
<br>
<br>
The user can hover over each icon and see the change in background to indicate which icon is being focused. 
</p>
<br>
<br>
When the web-page is greater than 1200.1px in width, then the sidebar will increase in size and the contents of the webpage will be shifted to the left to accomodate the changes. The sidebar style will also change with the text of each icon will be on the left with an increase to the font, and a decrease in size for the icons. 
<br>
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/57158277/183263037-f8f04916-ac89-434b-96fa-78c599868cf1.png" width="150">
</p>
<br>
<br>
<h2>Videos</h2>
The main section of the HTML page is the videos which was implemented as a section HTML element. To get the exact layout, the video section is created using a grid display layout. Using properties of the grid layout, the spacing around the videos and between the rows was added. The contents within each video are also created using the grid layout. The user can click on the thumbnail, title of the video, channel icon, and channel name to be redirected to their respective selection. 
<br>
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/57158277/183264284-eb3ea0cf-7263-4207-99d3-16daa5b75836.png" width="850"></p>
<br>
<br>
Similar to the tooltip created for the header, the tooltip is implemented in the video section when the user hovers over a video title. The user can also hover over the channel icon to be shown the channel icon, channel name, and channel subscriber count. 
<br>
<br>
<p align="center">
<img src="https://user-images.githubusercontent.com/57158277/183264357-34c096fc-cff2-4837-8d99-cd09f41a3959.png" width="550">
<br>
<br>
The tooltip presented with the title of the video when the user hovers over the video title
<br>
<br>
<img src="https://user-images.githubusercontent.com/57158277/183264436-77d320d9-4369-46c7-a78f-df8b5f84f382.png" width="550">
<br>
<br>
The tooltip presented with the channel information when the user hovers over the channel icon
