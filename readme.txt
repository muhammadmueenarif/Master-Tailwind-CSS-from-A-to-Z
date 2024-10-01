Lecture 01. It is similar to bootstrap. What we learned before in css was vanilla css. in which we use custom css. 
Tailwind saves time. 

Lecture 02. Overview of Tailwind
Copy cdn link form tailwind or learn how to install tailwind. tailwind is better than in ui than bootstrap.

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


Lec 13. Borders in Tailwind CSS. 
rounded will round the box. rounded-xl, -sm, -2xl, 3xl, rounded-full and so many. 

Lec 14. Border Radius in Tailwind CSS. 
border-4 will set boreder length. border-yellow-400 is color. border-double will give double line border. 


Lec 15. Divider in Tailwind CSS.
If we have multiple boxes in one box so we can divide them using this. divide-x-2 will divide in x axis and similarly divide-y will divide in 
y-axis. if we want to give color between divide we can give it as divide-green-500. we can also use divide dotted 
divide dashed and other like this. 

Lec 16. Outline
Border and outline works in same way but they are different. if we have box of 300px and give border of 20px, 
it means total is now 320px. but outline is the outside area of box. it does not increase width of box. box will remain 300. 
border works inside the box but outline works outside the box. 
outline will give default black color outline but if we give color we use outline-pink-300. 
outline offset will give some space between the box and outline and we can also use offset-8, 
and outline-dotted, dashed etc.,

Lec 17. Opacity and Box shadow
we can give shadow by shadow-lg, xl, sm etc.,, shadow-red-600/60 will give shade.

Lec 18. Flex box with Tailwind CSS
in grid, we can use both but in flex, we can use only one horizontal or vertical. we can increase size of boxes 
using basis-16, 32 and the number which we want. row-reverse will reverse. flex-col will convert to column. 
flex-wrap will will wrap on small screen and nowrap will not wrap. grow property is used to give width to each box 
if we are using flex. and h will give height. 
we can also use order property to give order. like if one is at the first position and we give it order-last and 
one will move to last order and all other will move one step behind. we can also give our own order like 2-3, 
justify-center will center the content and align-center will center vertically. similarly all other css flex 
propeties can be used here. space-between space-around space-evenly flex-start flex-end etc.,


Lecture 19. Designing with Tailwind. Hover, focus and active styles. 
hover:bg-pink-500 and also we can use transition like ease in out and delay-100 class. 
similarly we can use active and focus but remove transition as it will not work. 

Lec 20. Apply Directives 
Apply Directives is just like when we give bg-red-500 class and it give red color so we can make our own this type of class 
and give our own class.
create style.css and import @tailwind base; @tailwind components; @tailwind utilities; and then make all your own 
class. 
.btn-blue { @apply bg-blue-500 text-white hover:bg-blue-600; }
