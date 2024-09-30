Lecture 01. It is similar to bootstrap. What we learned before in css was vanilla css. in which we use custom css. 
Tailwind saves time. 

Lecture 02. Overview of Tailwind
Copy cdn link form tailwind or learn how to install tailwind.

if we want to give color we will give class in this way: text-red-500 (first tell the color of text and then 
other shows opacity and it will be given only in 100 not in 120 or 180 or anything like that ).
500 is perfect red value and if we move < it, it will give make like opacity and if we move >it, it will make color strong.

font-bold property used to bold the font. 

m-10 will give margin of 10 on each side. if we want only x oy y margin we can use m-x, m-y.
similarly p-10 will give padding of 10 on each side. if we want only x y margin we can use p-x, p-y.

to do something flex, we will simply use flex class.


Lecture 03. install tailwind using npm.
goto tailwind website, copy commands and install. this will install node modules and create tailwind.config.js file
Then goto package.json file and add the following code in it.
 "scripts": {
    "start": "vite"
  },
   "dependencies": {
    "vite":"^2.8.6"
  }

  Next open tailwind.config.js file and write * in the content[].


  Lec 04. Why we use tailwind?
  Largely used and we don't need to reuse classes. and template is not removed. 


  Lec 05. Margin and Padding
  mx and my and px, py. space-x-3 class will give space b/w multiple items. flex-row-reverse will reverse.
 space-x-reverse will give space in reverse if we are using fle-reverse.
  we also have mt for margin top and mb for margin bottom and similar pt, pb for padding.  


 Lec 06. Width and Height.
 we have min width height and max width height.  w-1/3 will take one third of screen. w-full give full width
 and w-fit will give fit. we can also give 2/5, 2/6 and so on. 
 min-w-fit, max-w-6xl. we can use minimum and maximum width and height this way. max-w-lg. 


 Lec 07. Font Size 
text-lg for large text and xl for xtra large. text-base is by default size and sm for small and xs.


Lec 08. Font weight and Style.
font-normal, medium, bold. font-black, and then font-thin is for smaller. We can give font style like font-italic, 
sans-serif, serif etc.,


Lec 09. Line Spacing
tracking-tight, tighter, normal, wide, wider, widest etc., it is for letter Spacing. for line spacing, we use 
leading property. leading is from 0 to 10. leading snug, and loose.
if we have list, list-disc will give points/bullets, and list-decimal will give numbers. we will need to give 
margin if the list is not showing.
next we have list inside, it will give something like margin type and show inside but if we use list outside
it will give margin outside and show at the start.


Lec 10. Text capatalize and uppercase. 
if we use uppercase it will make all text capital but if we use capatalize, it will make first letter of each 
word capital. lowercase will give all in small letters. if text is going outside the box, means overflowing, 
we will use truncate property. this will show the text until it is not overflowing in width and height. 
if i use overflow-hidden, it will not show the overflowing text. overflow-auto will show scroll line. there are 
many other properties of overflow like visible, scroll, overflow x, overflow y etc., 


Lec 11. Text Decoration. 
underline will give underline. text-red-500 will give color to text. text-justify will justify the content. 
if we use underline and give it decoration-solid, wavy, dotted or dashes, it will look like that which we give. 
we can also use double to give it double underline. if we want to give some more weight to underline, we can use
decoration-1, or decoration-5 or which value we want to give. 
decoration from font.we can use decoration from font, it will give us the decoration from the font itself.

Lec 12. Background in Tailwind CSS
bg-gradient-to-r from-blue-600 to to-red-500. items-center and justify-center are used for centering using flex. 
if we used Background, we can use bg-contain. bg-no-repeat. bg-repeat-x, bg-repeat-y. bg-center.bg-left-bottom.
bg-scroll, bg-fixed, bg-scroll. 