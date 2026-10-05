# Birthday website source

No installation or build is needed. Extract this ZIP, then open index.html in your browser.

## Add your own photos

1. Copy your images into the images folder. For example: images/photo1.jpg and images/photo2.jpg.
2. Open app.js in a text editor. The photos list is at the very beginning.
3. Replace each Unsplash photo ID with your local image path. Example:

const photos = [
  ['images/photo1.jpg', 'My favorite place', 'RIGHT NEXT TO YOU'],
  ['images/photo2.jpg', 'Little adventures', 'BIG, BEAUTIFUL MEMORIES'],
  ['images/photo3.jpg', 'Golden moments', 'THE WORLD FELT SO SOFT'],
  ['images/photo4.jpg', 'Just because', 'YOU DESERVE ALL THE FLOWERS'],
  ['images/photo5.jpg', 'You & me', 'MY FAVORITE KIND OF MAGIC'],
  ['images/photo6.jpg', 'More adventures', 'A WHOLE WORLD AHEAD OF US']
];

Replace only the existing photos array; leave the code that follows it.
The first photo and fourth photo also appear on the welcome page.
Image paths and file extensions must match your actual files exactly.
Add more entries to show more gallery photos; keep at least four entries for the welcome page.
After replacing all sample photos, remove the sample photographs notice and edit the image alt descriptions in app.js.

## Personalize the text

The birthday greeting, photo captions, love letter and wish text are in app.js.
The layout and animation styling are in style.css.
The four pages are index.html, memories.html, letter.html and wish.html.

## Put your edited version online

Upload the four HTML files, style.css, app.js and the images folder together to a static website host.
Editing this downloaded copy does not automatically update the existing hosted link.
The existing sample photos and Google Fonts require an internet connection. Your local photos work offline.
