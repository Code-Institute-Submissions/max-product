# Max Product furniture:

This is the website for Max Product, freshly started furniture business. It is not an official company website, the idea is to present it to owner as a mock-up, and then he can make further decisions. That being said, it's important to point out that facebook icon in footer does not have a source written in, and form is not functional since I did not apply the values.
 
## UX:
 
In initial conversation with the owner of the business, we discussed the goal of the site. He told me that they are having trouble with explaining their clients what services do they offer, and how are they realising them. So the major goal of the web-site would be to guide clients through self-explanatory way from starting point (Home page) to ending point (Contact page), where they will get all the basic information they need.


#### Client Frequently Asked Questions:

- What is exactly your business with furniture?
- How do you start with the project?
- How do you end with project?
- What is 3D modeling?
- Is delivery for free?
- Can you make exactly what I am looking for?

### Demographics:

Clients are usually between 25 an 65 years of age, Croatian citizens.

## Web-site Content:

- Home page

    - Introduction
    - Our Projects

- Services page

    - Services, icluding comics

- Gallery

    - Carousels of projects

  
- Contact

    - Contact form, non-functional.

- About

    - About Us


## Features:

#### Navbar:

I started the project from bare beginning, with navbar. I made it completely using Bootstrap, added logo, and added golden border with outline and shadow to liven it up. That line started whole thematics for the web-site.

#### Footer:

In comparison to navbar, footer was much easier for me to make. Simple columns with logo, company motto, contact info. and icon link to company facebook page. It's important to say that I didn't  add the source attribute for the facebook link since the whole idea of the web-site is to be a mock-up. Added the copyright info at the bottom of the footer.

#### Home Page:

I designed the hero image for the home page, it's an image form [pexels](pexels.com) with logo sticked to the drill. Whole point of the home page is to get the quick impression on what the company is all about. On the hero image, there is a company motto  with quick welcome text, and a button which leads to About page for more information about the company. Underneath that, there is the section which presents company projects with buttons that lead to Gallery page, to exact part of Gallery page users select, to be precise.

#### Services Page

Services page is made to make a clearer image on what exactly working part looks like. It consists of four different parts which are: Measuring of space, 3D Modeling, Delivery and Assembly. Every one of them is described in short notes, but since this is the aspect of work clients are having most of the questions about, I decided to make small comic with quick demonstration on how it's actually done. Accordion for the first part worked perfectly, however, I was stuck already on second one. After testing it out from few angles, I realised that every data target class in button, which triggers comics to show up should be named differently. At the end, when I tested the code in W3 markup validator, I needed to change comic ID names as well, even though they were working. Also, when the comic showed up, I had trouble removing the included border, and I founded the solution for that [here](https://kriesi.at/support/topic/remove-border-from-accordion-element/).

#### Gallery Page

I divided Gallery page on three carousels, each of them presenting specific set of project images. Those parts are kitchen, living room and bedroom. I had a problem with adjusting same carousel three times, and the problem was similar like on Services page. All of them had to have different ID, and that ID had to be targeted as well. I also had to adjust the correct numeric order so images can slide correctly.

#### Contact Page
 
 It's important to point out that the form is not functional since it's a mock-up web-site, it's there just to present the aesthetics.

#### About Page

I made a simple 50%-50% deal on the About page. 50% is an image of worker, and other 50% is company and their workers described in few words. Button from About page leads to Contact page.

#### Bugs faced along the way

1.At first I tried to include Bootstrap final version, but it didn't work for me, so I decided to try include v4.6.0 
 which worked for me, and I started the project.

2.As mentioned above, on Services page accordion for the first part worked perfectly, however, I was stuck already on second one. After testing it out from few angles, I realised that every data target class in button, which triggers comics to show up should be named differently. At the end, when I tested the code in W3 markup validator, I needed to change comic ID names as well, even though they were working. Also, when the comic showed up, I had trouble removing the included border, and I founded the solution for that [here](https://kriesi.at/support/topic/remove-border-from-accordion-element/).

3.As mentioned above, on the Gallery page, I had a problem with adjusting same carousel three times, and the problem was similar like on Services page. All of them had to have different ID, and that ID had to be targeted as well. I also had to adjust the correct numeric order so images can slide correctly.

4.There was a problem with responsiveness of images in columns on Services and About page, most of those problems I fixed by handy Bootstrap classes w-100 and h-100 and by adding my own class which removes left and right paddings.

## Technologies Used

- HTML 5

- CSS 3

- Bootstrap v4.6.0
    - Used through whole web-site for it's responsive features and styling.

- Font Awesome v5.6.3
    - Used icons to add more character to the footer.

- Google Fonts

- Chrome Developer Tools
    - Used for live testing.

- kraken.io
    - Used to reduce images in size and to compress them.

- Adobe Photoshop
    - Used to design comics in services.html and hero image.

- Adobe Illustrator
    - Used to design logo and images of icon and screws.

- Visual Studio Code
    - Code editor used for project.   

- Git
    - Used for version control by commiting, keeping track on the project and pushing to Github.

- Github
    - Used for storing the project and sharing it.        


- [JQuery](https://jquery.com)
    - The project uses **JQuery** as part of Bootstrap.


## Testing

#### Website is tested on three different web-browsers:

- Google Chrome:
    - Tested and working perfectly.

- Mozilla Firefox:
    - Tested and working perfectly.

- Microsoft Edge:
    - Tested and working perfectly.

#### Website is tested for fluidity, speed and responsiveness on different devices using Chrome Dev tools:

- Galaxy S5:
    - Tested and working perfectly.

- Pixel 2:
    - Tested and working perfectly.

- Pixel 2 XL:
    - Tested and working perfectly.

- iPhone 5/SE:
    - Tested and working perfectly.

- iPhone 6/7/8:
    - Tested and working perfectly.

- iPhone 6/7/8 Plus:
    - Tested and working perfectly.

- iPhone X:
    - Tested and working perfectly.

- Regular tablet size:
    - Tested and working perfectly.


#### W3 Markup Validator and W3 CSS Jigsaw

- W3 Validator:
    - Tested and corrected all the errors.

- W3 Jigsaw:
    - Tested and no errors at all.


## Deployment

Final version of project is uploaded to Github Pages, it can be visited here:

[Max-Product](https://barbirm.github.io/max-product/)


## Credits
- All photos used for purposes of the web-site are downloaded from  [Pexels](http://pexels.com) and [pixabay](http://pixabay.com). Therefore, big thank you to wonderful people for sharing their pictures for free with the world:
- [Ono Kosuki](https://www.pexels.com/@ono-kosuki)
- [Ksenya Chernaya](https://www.pexels.com/@kseniachernaya)
- [Artem Podrez](https://www.pexels.com/@artempodrez)
- [Andrea Piacquadio](https://www.pexels.com/@olly)
- [Max Vakhtbovych](https://www.pexels.com/@max-artbovich)
- [Mark McCammon](https://www.pexels.com/@markmccammon)
- [StruffelProductions](https://pixabay.com/users/struffelproductions-589546/)
- Youtube channel [Drew Ryan](https://www.youtube.com/channel/UCtXGz0MBuqZUC8rmGddc07Q), handy channel where I picked up some of Bootstrap knowledge.
- Stack overflow, where I found solution for my problem with [buttons](https://stackoverflow.com/questions/2906582/how-to-create-an-html-button-that-acts-like-a-link).
- And I found solution for toggle borders [here](https://kriesi.at/support/topic/remove-border-from-accordion-element/)


### Media
- Photos downloaded from  [Pexels](http://pexels.com) and [pixabay](http://pixabay.com), some of them designed using Adobe Photoshop, some of them used as they are.
- I designed the logo using Adobe Illustartor.

### Acknowledgements

- My mentor Sandeep Aggarwal, for patience, feedbacks and support.
- My brother, the owner of the business, who approved my idea.
- Code Institute team for guiding me through the course, and teaching me necessary skills for the project.
