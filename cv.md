# **Sviatlana Shaliankova**
## Novice Front-End Developer
_____
I quickly learn new areas of activity, master new skills. I am considering a career change towards front-end development.
_____
## Education
* 1999 - 2004
    Belarusian National Technical University (BNTU)<br>
    Traffic management and logistics
    
* 2021
  RS School<br>
  JavaScript/Front-end
  
_____
## Work Experience
* 2005 - 2013<br>
    State Enterprise "Minsktrans"<br>
    Transport management engineer

* 2014 - to the present<br>
    VMG "Industry"<br>
    Accounting specialist

_____
## Сode example
```
// Given an n x n array, return the array elements
// arranged from outermost elements
// to the middle element, traveling clockwise.

snail = function(array) {
  let snailBody = [];
  if (array[0].length == 0 || array.length == 0){
    return snailBody;
  }
                              
  let maxI = array.length - 1;
  let maxJ = array.length - 1;
  let minI = 0;
  let minJ = 0;
                            
  while (minI <= maxI && minJ <= maxJ) {
    for (let j = minJ; j <= maxJ; j++) {
      snailBody.push(array[minI][j])
    }
  minI++;
                            
  for (let i = minI; i <= maxI; i++) {
    snailBody.push(array[i][maxJ]);
  }
  maxJ--; 
                                
  for (let j = maxJ; j >= minJ; j--) {
    snailBody.push(array[maxI][j]);
  }
  maxI--;
                            
  for (let i = maxI; i >= minI; i--) {
    snailBody.push(array[i][minJ]);
  }
  minJ++;
  }
  
  return snailBody;
}                            
```
_____
## Skills
* JavaScript
* Html/CSS
* GIT

_____
## Language
* Russian
* Belorussian
* English

_____
## My Contacts
* Phone: +375 (29) 649 89 54
* Telegram: @SviatlanaS
* Discord: Sweet-ka #5165
* Email: sweet-ka@mail.ru
* Adress: Mogilev, Belarus

_____
## Hobbies
* fitness
* dance
* music
* books

