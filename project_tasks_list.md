General Requirements for the HTML:

1. Three icons at the top

   - MIDDLE ICON will be highlighted always

2. main image -> for the dog

   - Image information on top of the image.
     1. name, age of the Dog
     2. bio of the Dog
   - Either LIKE or NOPE ON TOP OF THE IMAGE

3. Two clickable icon below the image.
   - First Icon: Cross Icon
   - Second Icon: Heart Icon

**FUNCTIONALITIES:**

1. When user click on the ❌,

   - Nope should appear on top of the image

2. When user click on the 💖,

   - Like should appear on top of the image

3. When either of the icon is clicked, the next image should be rendered after 1 or 2 second.

<!-- BREAKDOWN -->

**HTML and CSS**

_FIRST TASK:_

1. Have the three icons in the header.✅
2. Highlight the middle one.✅

_SECOND TASK:_

1. Have the dog image rendered on the page.✅
2. Have the text on top of the image, at the left bottom of the image.✅

_THIRD TASK:_

1. Have the heart and cross icon below the image on the page.✅

**JAVASCRIPT**

1. add Dogs data to the data file✅
2. store dogs images to the dogs folder✅

<!-- HIGH LEVEL OVERVIEW FOR FUNCTIONALITY -->

1. When user click on the heart icon, Like image will appear on top of the dog's image.
2. When user click on the cross icon, Nope image will appear on the top of the dog's image.
3. When either NOPE or LIKE has been appeared on the dog's image, both the heart and cross icon will be disabled, UNTIL the new image has appeared.
4. STEP#1 till STEP#3, WILL repeat itself, until all the data has been appeared on the page.

_FIRST TASK:_

<!-- Render the html along with DOG container on the page, when the app starts. -->

1. Render the html from Dog class, which will render the data.

<!-- How to loop through data and render it dynamically using Dog Class. -->

1. Attach an event listener to the heart icon.
   - When click on it, "Heart Icon" msg will be printed on console.
