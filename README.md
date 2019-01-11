# Brandon Sanderson Works

## Introduction
Welcome to my website README.
This website has been built to showcase some of the books and novel series by the author Brandon Sanderson.

On this site you will find information on the Mistborn series, the Stormlight Archive series and other books that are set within the Cosmere universe.
You will also be able to watch videos of Brandon Sanderson teaching and listen to the Writing Excuses podcast. Furthermore there is a page for you to be able to contact Brandon with any questions or enquire about booking him for signing events.

So please, step in and learn about the wonderful universe that Brandon Sanderson has created.


## UX
This website has been built to be responsive so that it works on all size devices. The user that I had in mind when creating this site was a person who either knows nothing about Brandon Sanderson, or someone who may have read some of his other works and wants to find out more about his other works.
The aim was to provide compelling information about the books to encourage users to go and seek more information, or to buy the books and read them.

### User Stories

- as a user, i want to see information on the mistborn series, so that i can learn more about the books
- as a user, i want to see information on the Stormlight Archives series, so that i can learn more about the books
- as a user, i want to see information on other books Brandon Sanderson has written, so that i can learn more about those books
- as a user, i want to be able to fill out a form, so that i can ask questions or request a booking
- as a user, i want to watch videos on Brandons lectures, so that i can learn more abotu writing
- as a user, i want to listen to the podcast "Writing Excuses", so that i can listen to the podcast and learn about different topics
- as a user, i want to have a page that has a biography of Brandon, so that i can learn more about him.
- as a user, i want to have a place to read about the Cosmere, so that i can learn more about the universe he has created
- as a user, i want to be able to view the webpage on mobile devices, so that i can look at the information on the go


### Mockups

As part of the design process I created the mockups that can be found [here](https://github.com/ALDrinkwater1989/stream-one-project/tree/master/assets/Mockups) i was happy with these to begin with, however as the project went on
I decided to change the lay out of a couple of pages, and also i created the gallery page after i was looking at the mobile view nad thought that as the
book covers are not shown on a mobile, i wanted a place to show them off for mobile users, so the gallery was created, which is why there is no mockup for it.

![Mockup 1](./asests/Mockups/img13122018_001.jpg)

## Features

On this page the user is able to do a number of things.

### Existing Features

* YouTube video - this lets the user watch Brandons teaching videos, it is located on the Teaching page, they can watch all of the playlist.
* Podcast - Users are able to listen to an episode of the Writing Excuses pocast, currently it is only one episode that is saved locally.
* Contact form - this allows users to submit questions or request event bookings for Brandon. Currently it is not linked up to a web server, becuase it was out of scope for this project
This can be found on the coontact page.
* Gallery - The gallery shows off all of the book covers found on the website, it was deisgned for mobile users mainly, however it is a good place to view
the covers properly on other devices as well.

### Features left to implement

Creating a proper RSS feed for the podcast, it was not done because i did not feel comfortable doing it and I felt it was beyond the scope of this project.



## Technologies used
The technologies used in creating this website are:
* HTML this was used to create the pages.
* CSS this was used as standard to style the page.
* Bootstrap. This was used as a framework to help with the positioning, for a grid system it provides and also the responsiveness of the website, as Bootstrap is brilliant for creating responsive websites.
It was also used to create the nav bar.
* Javascript & Jquery. This was used for the modal on the gallery page. It is a standard modal set up from w3 schools [found here](https://www.w3schools.com/howto/howto_css_modal_images.asp) with some modifications I had to make because that did not work quite as intended, this is because the modal set up from. W3 schools is just for one inage, rather than numerous. Igor the solution for this issue from stack overflow [found here.](https://stackoverflow.com/questions/41275958/modal-image-galleries-multiple-images)


## Testing

Some area of the site that required testing are;

- the contact form, to make sure that it would only submit if all the required fields were filled in.
- the gallery modal.
- the responsiveness ofthe site, to make sure it worked on devices of all sizes.
- the youtube video works.
- the podcast works.

you can find the tests that i ran [here](https://github.com/ALDrinkwater1989/stream-one-project/tree/master/assets/test-document)

### Known bugs

Currently there are two known bugs, that i have not been able to fix.

- The first bug is on the Gallery page, at a certain resolution one of the rows does not properly align, so it cuases the row to have one image on one, to the right, then the other 3 images on another row, but to the left. there is no reason this should happen, as the HTML markup is the same as all of the other rows on the page.
- The second bug is with the navbar. On some screen resolutions, it pushes the gallery link and sometimes the contact link onto a second row, which overlays the main body of the page you are on.


## Deployment

This site was deployed on GitHub, with regular pushes to make sure all changes are documented and backed up safely.

as of writing this document, there are no differences between the deployed version and the development version.

in order to run the website locally, you will need to download all the files and load them into an IDE so that you can see the code, and then run it. you do not need to download the "mockups", "test-document" and "user stories" files.

## Credits

### Content
The content on this site comes from a variety of different places. Some if it was my own writing, others were copied from other pages and some was heavily influenced, below is a list of places where information came from and a reason why it did so;
- The text for the biography section was copied from [Brandon Sanderson Wikipedia](https://en.wikipedia.org/wiki/Brandon_Sanderson) This is because all of the information that is needed is in the Wikipedia article, so it made sense to copy it, rather than rewriting it.
- The text for the Cosmere section was heavily influenced by site [The coppermind](https://coppermind.net/wiki/Cosmere) this is because, while it has all of the information, I wanted to explain my take on it, while still having it be factual.
- The information on all the books came from the backs of the books. The reason I chose to do this is back the blurb of all the books are very compelling and I found that in the group of people I have shown this too, when they have read the sections it has made them want to go and find out more and even purchase some.
- The overview sections for the books are my own writing. As with the Cosmere, I wanted it to be my take on the stories and series and how I felt about them.

### Media
The photos used in this site were obtained from Google. A Google search for the books returned the image results. From there I saved them locally and then uploaded them to Cloud9. All images have been saved onto my GitHub repository.
The video that was used on the teaching page is an embedded YouTube video, it also allows you to play other videos in the playlist, or go straight to the YouTube channel itself.
The podcast used on the teaching page comes from the writing excuses page (https://writingexcuses.com/) there is an RSS feed for the podcast, however implementing it into the webpage was beyond my current skills, so the podcast is a downloaded version and uploaded to Cloud9 and GitHub.

### Acknowledgements
The reason I decided to build a site showcasing Brandon Sanderson’s work is because his writing style and the stories he tells are some of my favourite books I have ever read, he makes you invest in the characters and care about them. I wanted to pay a small tribute to an author who creates such fantastic worlds.
