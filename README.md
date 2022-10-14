# Landing page for National Art Museum of Ukraine
Implement landing page according to [Figma design](https://www.figma.com/file/HL3XGt5ZatvJoYBhOaWY5x/museum-prototype?node-id=323%3A1957) - Use HTML5, SCSS, Flex-box, Grid, JavaScript, BEM, Gulp.

The landing is adaptive to different screen extensions, has a stylish design, contains a swiper with slides, burger menu, links, animations and a form to fill.

Check font styles. Use [Playfair Display](https://fonts.google.com/specimen/Playfair+Display?query=Playfair+Display), [Raleway](https://fonts.google.com/specimen/Raleway?query=Raleway)

- The design 1440px
- Desktop 1280px
- Tablet 640px
- Mobile (> 320px)

1. Implement the header with menu.
2. Implement `Актуальтні виставки` block.
3. Implement `Найближчі події` block.
4. Implement `Сплануйте візит до музею` block.
5. Implement `Новини` block with the three cards.
6. Implement `Підпишіться на дайджест` block.
7. Implement footer.

    - [DEMO LINK](https://PastolNapas.github.io/NAMU-landing/)
# Instruction  
1. Add a favicon
2. Don’t forget to add a title for the whole web page (it could be the name of your landing)
3. All Logos on the page should be links to home page
4. Change text color on hover for phone, email and address
5. When you click on phone icon or phone number in contacts section, make sure that there is no 404 error, make it a real link to start a call on device
6. Same when you click on logo. There shouldn't be any error.
7. When clicking on any location / address - prevent errors and make it to open location in Google Maps
8. Pictures in Gallery should increase on hover
9. Location-related addresses / links / images should open google maps in a new tab `target="_blank"`
10. Apply `:hover` effect for images on page (testimonials / gallery, other sections).
11. Make sure everything looks neat on mobile and without horizontal scrolling
12. The speed of animations is the same throughout the landing page (for example, increasing when hovering or moving blocks when scrolling)
13. Placeholders in the forms suggest what to enter; apply validation of the form fields (`required`, `email / tel etc.`), then it is clear in what format to enter the data
14. Form shouldn't be submitted if some of the fields are not filled
15. Page shouldn't be reloaded on form submit (https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault)
16. Add a smooth scroll for the whole page
17. Fix menu for small screens (if there is not enough space for all the menu items)

## Github flow
1. **Fork** the repo.
2. **Clone** the forked one. (The project link should have your name but not `mate-academy`)
3. Run `npm install` (or just `npm i`).
4. Run `npm start`.
5. Open one more terminal window for the next steps.
6. `git checkout -b develop` - to create new branch and switch on it.
7. Write you code in `src` folder.
8. Run `npm run lint` and fix code style errors.
9. Run `npm run deploy` to deploy your solution to `gh-pages`.
10. `git add . && git commit -m 'write a short description of the changes you made'` to save your changes.
11. `git push origin develop` - to send you code for PR.
12. Create a Pull Request (PR) from your branch `develop` to branch `master` of original repo.
13. Replace `<your_account>` with your Github username in the
  [DEMO LINK](https://<your_account>.github.io/Museum_2/).
14. Copy `DEMO LINK` to the PR description.

> To update you PR repeat steps 7-11.
