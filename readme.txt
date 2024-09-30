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

