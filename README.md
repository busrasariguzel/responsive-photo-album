## `Motivation`

* Cats are human's best friend! Even though they don't show it as much, they love us! Cats make the world a better place! 2 years ago, I adopted a small kitty and my life have changed. Now she is huge(I mean-huge!) and the queen of our life. Since then, I am leaving parties and any social event early to go home and see my little potato. I cannot describe how much I love her so I decided to make a photo album of cats. I included my fat baby too in the pictures. I think everyone should see these pictures and smile at least once while looking at them!

## `Challenges`
* I had a hard time making my photo album responsive. The pictures were getting smaller but they were not changing their locations.
* I also had hard time figuring out the layout of my album. I was not sure where to put each section. 
* I struggled with what to write on this readme file but here we are :) 
* I overcame my challenges by spending more time on the project and trying different things to make it work.
  
## `Goals`
* My first goal on this project was to show people how amazing the cats are!
* My second goal is to practice responsive grid and css tools.I tried to have 3 different layouts and that helped me to understand the grids better.

## `Code`
* I mainly used CSS in this project. 
* The code I used for grid areas :

``` 
grid-template-areas: 
        "hd01 hd01 hd01 hd01 hd01"
        "nv01 nv01 nv01 nv01 nv01"
        "pc01 pc02 pc03 pc04 pc05"
        "pc06 pc07 pc08 pc09 pc10"
        "pc11 pc12 pc13 pc14 pc15"
        "pc16 pc17 pc18 pc19 pc20"
        "ft01 ft01 ft01 ft01 ft01"
    ;

```
* Layout codes used:
```@media (min-width : 501px) and (max-width:800px) {
    
    #photo-album {
        display: grid;
        grid-template-columns: repeat(4,1fr);
        grid-auto-rows: repeat(8,1fr);
        grid-auto-flow: dense;
        height: 100vh;
        width: 100%;
        border: black solid;
        font-size: 18px;
```






