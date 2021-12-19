#Maksim Nikaniuk
***
###My Contact Info:
- Discord: maxlablearn
- E-mail: maxlablearn@gmail.com
- GitHub: maxlablearn
- Location: Belarus Baranovichi
***
##Briefly About Myself
I have a higher technical education. Worked as the head of laboratory of non-destructive testing. Currently I am working as an engineer on the railway.
I decided to change my profession, and because I was always interested in computers, I participated in school and city programming olympiads, I chose Front-End development. Studied microcontrollers  and assembler.
I enjoy understanding code, developing new and interesting things.
***
##Skills
- Html
- CSS
- JavaScript (Basic)
- Git
***
##Code Examples
> __CodeWars:__ _Write a function which partitions a list of items based on a given predicate.
After the partition function is run, the list should be of the form [ F, F, F, T, T, T ] where the Fs (resp. Ts) are items for which the predicate function returned false (resp. true)._
```
function partitionOn(pred, items) {
  let firstArr=[];
  let secondArr=[];
  let med;
    for (let i=items.length; i>0; i--){  
      if (!pred(items[0])){               
        firstArr.push(items.shift()); 
      } else {                            
        secondArr.push(items.shift());
      }
    }
  med=firstArr.length;
  items.push.apply(firstArr,secondArr);    
  items.push.apply(items,firstArr); 
  return med;
}
```
***
##Language
English level - A2 (Training in Duolingo)