# Tool Learning Log

Tool: Aframe

---

### 3/14/24:
* Links you used today (websites, videos, etc)

  * My partner and I created a [wireframe](https://wireframe.cc/zawn6r) to have a rough draft of our project. This is to help us envision certain parts in a general way but as we gradually continue to edit our content to be more thorough, we'll add more details to that original layout (or even completely change it).
  * [JS Bin](https://jsbin.com/betaqigope/edit?html,output)
  * I used [getbootstrap.com](https://getbootstrap.com/docs/5.0/customize/components/) to research and test out different bootstrap components. 
  
* Things you tried, progress you made, etc
  
  * After completing our plan, we decided to also plan our individual roles in the project. For example, HTML is my responsibility while the CSS is my partner's. Some parts, however, we decided to work on together as they were complex tasks which involved their own seprate individual roles.
  * In terms of HTML code, I was able to test out a few bootstrap components, specifically including cards, navbars, and listgroups. Ahough, I wasn't able to properly execute these components in [JS Bin](xhttps://jsbin.com/betaqigope/edit?html,output), I was able to get a rough idea of what I wanted to incorporate into the project.
  *  These are the components I tinkered with:
 
###### Navbar

  ```html
  <ul>
  <li><a href="Navbar">Home</a></li>
  <li><a href="Navbar">News</a></li>
  <li><a href="Navbar">Contact</a></li>
  <li><a href="Navbar">About</a></li>
  </ul>
  ```

###### Card

  ```html
  <div class="card">
  <img src="img_avatar.png" alt="Avatar" style="width:100%">
  <div class="container">
    <h4>  Lorem ipsum </h4>
    <p>  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
  </div>
  </div>
  ```

###### Listgroup

  ```html
   <ul>
    <li>Lorem ipsum</li>
    <li>Lorem ipsum</li>
    <li>Lorem ipsum</li>
  </ul>
  ```
  
* Challenges, a-ha moments, etc

  * Upon initially starting our plan, I was lost on the concept on bootstrap in terms of its sub categories. This included cards, collapse, dropdowns, etc. I'm now beginning to slowly learn about the various components and now realize that bootstrap, as a whole, is a complex system.  

* Questions you still have

  * What components of bootstrap might be more applicable to certain categories of content? Are there general links? 

* What you're going to try next
 
  * I'm going to continue to try to research and execute more bootstrap code to see what's most fit for the given project content.
 





### 3/21/24:
* Links you used today (websites, videos, etc)

  * I used [W3Schools](https://www.w3schools.com/) to research and test out different bootstrap components and general outcomes. 
  
* Things you tried, progress you made, etc
  
  * After testing out different components of bootstrap, my partner and I decided to use a navbar and listgroup as our primary components. We decided on a more difficult component (the navbar) to challenge ourselves and then we decided to use a less challenging components (listgroups) to practice what we already knew.  
  * We ended up going through different methods of inputting code for these particular components (deciding on whther we should put them through css or html, or what particular navbar setting we wanted, etc.).
  * Ultimately, we ended using this particular html code:
 
###### Navbar

  ```html
  <div class="topnav" id="myTopnav">
        <a href="#home" >Home</a>
        <a href="#gallery" >Gallery</a>
        <a href="#moreinfo" >More Information</a>
        <a href="#testimonials" >Testimonials</a>
        <a href="#contact" >Contact information</a>
  </div>
  ```

###### Listgroup

  ```html
  <ul class="list-group list-group-flush">
        <li class="list-group-item"> Time:
            Due to climatic conditions, we can safely fly only in the early morning hours with our primary season and most beautiful months being May through November. Since our launch times vary through the seasons, we ask all our guests to call ahead for the exact meeting time.</li>
        <li class="list-group-item">Weather: High winds and/or inclement weather prevent us from flying. We ask all our guests to contact us in the early afternoon prior to their scheduled flight between 12:00 noon and 2:00 p.m. to verify that the forecasted weather conditions will allow their balloon flight.</li>
        <li class="list-group-item">Flight
            Our actual flight time is approximately one to one and a half hours averaging closer to one and a half hours and we suggest to allow three to three and a half hours for the entire adventure.</li>
        <li class="list-group-item">Participation
            We encourage all of our guests, if they wish, to participate in both the inflation and deflation of the balloon. We have found it adds greatly to the fun of the entire ballooning experience.</li>
  </ul>
  ```

We chose these components mainly also because they're evidently similiar to each other in terms of code as they both heavily rely on classifying, organizing, etc.  
  
* Challenges, a-ha moments, etc

  * We found particulalry the navbar difficult to execute being that we wanted to create something functional and complex. While the idea itself is definitely functional, we simply weren't there yet in terms of difficulty and didn't want to overwhelm ourselves with inevitable challenges so we decided to work on a default navbar. Even then, we found trouble with how to make it compatible with scrolling as we wanted to add the navigational component instead of making it just a visible feature. Eventually we passed that point though.  

* Questions you still have

  * What other forms of navigation are there in the navbar besides the one we used? 

* What you're going to try next
 
  * I'm going to continue to research and execute more bootstrap code to extend my knowledge on the different components out there and what might be beneficial in future projects.

