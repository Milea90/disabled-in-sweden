# Disabled in Sweden
Link to the page:

The background story of this website, is actually that I had a dream about creating it. So I did.

The main purpose of this website, is to help people, especially those with disabilities, to access information about the Swedish support systems for disabled, if they for example are planning to move to Sweden and need to know about this before moving. The goal is to present the content in an accesseble manner. That includes creating the website with accessibility in focus during every step on the way - from choosing the background colors to writing code that is filled with semantic code as well as alt-attributes and aria-labels.

Since the topic of the website is about support systems that can assist people with disabilities, I thought it would be a great oportunity to demonstrate what a website with a main focus on accesibiliity could look like. By doing so, the website adds a value to the user in two ways: by presenting valueble content about a topic that otherwise can be very difficult to find and/or understand once found, but also by doing so in a way that is accessible for those with different kind of disabilities. At least that is the goal.


### Implemenation
In order to create a website with accessibility as the main focus, I was quite limited in what I could and could not do, but I thought it was a fin experience. Even if the site looks simple, I have put a lot of thought into it. This is a list of how and why I did what I did: 

* The colors of the site is blue and yellow. Apperently, people who are colorblind struggle to see red and green, but most of them can see blue and yellow, o that became the two colors I chose. It is also the colors of the swedish flag, sp that seemed like a perfect match. The colors are also very light so it would be easier to read the content.
* The fontsizes are all on the bigger side, simply to make the content easier to read. 
* All the images and links, exept from the background-image, has alt or aria attributes. 
* The text in well structured using semantic coding. 
* The layout is clean and simple to not distract the user.
* The textcontent has been tested for typos with a spelling-tool to make sure screanreaders will read the content correctly. 
* The font-families that I chose are the most accessible, Arial and Helvetica.
* The slashes in the navigation bar is there for the screanreaders, but also for stylingpurposes.. 
* Shortenings has a dot between every letter so a screanreader will read it as (DO) for example and not aas "do".
* The content itself is short and split into sections.
  

### Home-page
On the home page is an introduction to the website and gathered information of what the website covers and a Google map over Sweden.
![](readme-images/home.png)
![](readme-images/map.png)

### LSS-page
On the LSS page is information about what LSS really is. 
![](readme-images/lss.png)

### DO-page
On the DO page is information about what DO does and there is also a link to their website.
[](readme-images/do.png)

### FK-page
On the FL page is information about what FK is and there is also a link to their website.
![](readme-images/fk.png)

### Learn more-page
On the Learn more page is information about the view on disabilities in Sweden. There is also a video with facts about Sweden.
![](readme-images/lm.png)
 ![](readme-images/lm-video.png)
 
### Contact-page
On the contact page is links to the different institutions mentioned on the site.
 ![](readme-images/contact.png)


## Features

I have included some features where I thought it would give the website more value to the user. But overall, the website is very simple.

### Navigation
On all pages there is a navigation bar at the top. The navigation changes color when the mouse hovers over the different topics to make sure it is easy to know where one should click. The shortenings in the navigationbar,D.O for example, have dots between them. This is so a screenreader will read is as "DO" and not "do". 
![Image of homepage](readme-images/home.png)

### Images
All the images,exept the background-image and contact-image, display disability in some way or another to make sure the topic of the website is clear. All have alt-attributes. 

### Map on landing page
I thought it would be a good idea to insert a Google map over Sweden on the landing page to make it easier to use it
in order to find Sweden on the map. 
![An image of a map](readme-images/map.png)

### Youtube video 
On the page "Learn all" I have inserted a Youtube video about Sweden and swedes which I thought would be a funny complement to that page. 
![An image og a Youtube video](readme-images/lm-video.png)

### Links to institutions
Since a lot of the content is about swedish institutions, I have included links to their websites to make it easier for the user to navigate to them for mor information om the subject. 
![An image of links](readme-images/contact.png)

### Features left to implement
The goal was to create a very simple website so I do not want the website to have too much going on. I was however planning to add icons to the sections/divs to make them a bit more pleasing to the eye. But I was not able to find any that I was happy with and/or that was suitable for the topic of the website. After searching among hundreds of icons I finally gave up. If I find any in the future I would like to implement them.

## Testing
In order to make sure everything works as expected, I have:

### Used Lighthouse on order to check the accessibility ratio.

![](readme-images/access-test.png)
![](readme-images/access-test1.png)


  ### Tested CSS and the HTML code for errors in W3. 
  ![](readme-images/css-valid.png)
  ![](readme-images/html-valid.png)
  
  Unfortunatly, it seemed like I could not use an aria-label to my div for the background image. The validator said it was not ok. So my background image will not be accessible for blind people.
  
  ### Used dev tools to see what needed to be done in order to create a responsive design. 
  When it comes to responsive design, my biggest issue where the images. The rest was working fine due to relative units on divs and fonts. So when using a smaller screen, the site adjusts quite well. There is a few exeptions and that is my so called bugs. 
   ![](readme-images/dev.png)
  
  ### Bugs found (all - including unfixed)
  I have been very fortunate with this project for not having to deal with a lot of bugs. But I did find some and that is the Youtube video and Google map.
  The Google map and the Youtube video was not responsive att all. First, I solved it by changing their set sizes to % units instead and that worked perfectly. But when I was validating the html code, it did not pass. So I had to change it back to the original units. Then I tried to fit them into divs but they just would not behave accordingly to the divs. So I ended up with making them very small and putting them in the left corner of a div so that even if screen sizes reduced, they would be in some way responsive to that. I did search on Google and found a syntax for it, but it did not work either and I had no time left to fix it.  
  
  Also, I wanted to see how the site would behave if I was minimizing the whole site to under 100% and it quickly became very disorted. But that was late into the project and I had no time to look further into that.
 
## Deployment
The site was deployed to GitHub pages. The steps for deploying are:
* Go to the GitHub repository and navigate to the Settings tab.
* From the source section drop-down menu, select the Master Branch.
* When master branch is selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - <>

## Languages used
HTML5, CSS


## Technologies used
Git, Github, Code Anywhere.
I also tried to install a Chrome screanreader on my computer but I could not figure out how it worked. So unfortunatly, I do not know how well my implemantations work with screanreaders.

## Media
The images is downloaded from Pixabay.com
The video is from Youtube.com
The map is from Google Maps

## Written content
The content is written totally by myself. 
The soucres for the content comes from swedish websites such as: 
www.do.se
www.fk.se
www.kunskapsguiden.se


## Colors
In order to set the colors for the website, I used this website: https://www.colorblindguide.com/post/colorblind-friendly-design-3 to help me choose colors that worked well with colorblind, like yellow and blue.


## UX-design
I imagine that the main user will be, but does not have to be, someone with disabilities. Therefore I have created a website that takes that into account thruout the complete website, on every page, from top to bottom. That will include things like: 
  

## Used code
I have used syntax snippets to create my navigation bar from this website:
https://www.w3schools.com/howto/howto_js_topnav.asp


## Acknowledgements
I would like to acknowledge everyone on slack for helping out with miner issues. And also tutors. Some youtubers has also been helpful, mainly Kevin Powell.
