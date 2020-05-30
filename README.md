# responsive-portfolio
Coursework Assignment No. 2 for Coding Bootcamp
Link to deployed application: https://benorule.github.io/responsive-portfolio/

## Shared Elements

The three pages index, portfolio and contact have some elements in common. These elements were completed first. The following descriptions apply for each html document as the code was completed in one and then transferred to the others.

### Navigation Bar

I found a navigation bar from bootstrap and implemented it into my html document. I changed the names of the navigation links and the navbar title. I removed the dropdown button and the search box from the nav bar. I set the href of About, Portfolio and Contact to index.html, portfolio.html and contact.html respectively. I set the active navigation link (which is the link that appears in bold) to be About in index.html, Portfolio in portfolio.html and Contact in contact.html.

I put the navbar within a bootstrap container to make it easier to format with other elements.

I tested the responsiveness of the navbar in multiple frameworks and was satisfied with it so did not see it as necessary to create any media queries.

### Footer

I found a footer from bootstrap and implemented it into my html document. I changed the text in the footer to be "Copyright" and it automatically included a link titled GitHub because of the copyright link in the headtag for the bootstrap repository.

I put the footer within a bootstrap container to make it easier to format with other elements.

I tested the responsiveness of the navbar in multiple frameworks and was satisfied with it so did not see it as necessary to create any media queries.

## Contact

The following elements were implented into the contact.html file only.

### Input Group

I found an input group from bootstrap and implemented it into my html document. I deleted two of the input sections as they were not necessary. I renamed the titles of the input sections that were left. I edited the placeholder text of each input box. I moved the title of the seciton input section to the left from the right.

I put the input group within a bootstrap container using a row to contain a column and the column itself to constrict the box to the left side of the window rather than having it taking up the entire viewport.

I tested the responsiveness of the navbar in multiple frameworks and was satisfied with it so did not see it as necessary to create any media queries.

## Index

The following elements were implented into the index.html file only.

### Card

I found a card from bootstrap and implemented it into my html document. I deleted the button as it is not necessary. I renamed the title of the card. I edited the placeholder text of the card to Lorem Ipsum.

I put the card within a bootstrap container using a row to contain a column and the column itself to constrict the box to the left side of the window rather than having it taking up the entire viewport.

I tested the responsiveness of the card in multiple frameworks and was satisfied with it so did not see it as necessary to create any media queries.

## Portfolio

The following elements were implented into the portfolio.html file only.

### Images

I found a format for images with captions beneath them from bootstrap and implemented it six times into my html document. I used a placeholder image for each six image links. I renamed each caption as Untitled Project seeing as each image represents a project as part of a portfolio.

I put each image within a bootstrap container. I used internal styles to make each image with a caption float left.

I tested the responsiveness of the images in multiple frameworks and was satisfied with it so did not see it as necessary to create any media queries although I noticed that the footer formatted itself upward next to the images which made me realise the need for a sticky footer in each html document.

## Shared Elements

The three pages index, portfolio and contact have some elements in common. These elements were completed first. The following descriptions apply for each html document as the code was completed in one and then transferred to the others.

### Sticky Footers

In order to make the existing footer a sticky footer, meaning that it appears at the bottom of the window and note the page so it will be visible even when scrolling. I added style="position: fixed; left: 0; bottom: 0; width: 100%; text-align: center;" to the tag that already had the bootstrap class "footer-margin" in it. The added style elements make the footer have a fixed position on the window and the parameters of left and bottom define where on the window it stays. The width makes sure it takes up 100% of the window of any viewport and the text-align makes the text appear in the center of the window of any viewport.


