> # Rodionov Misha

### Contacts
 [![Telegram](img/telegram.svg)](https://t.me/mi6aRdnv)  [![Github](img/github.svg)](https://github.com/Mi6aRdnv)  [![Codewars](img/codewars.svg)](https://www.codewars.com/users/Mi6aRdnv) 

### About me
> I have completed a degree in Software Engineering from the university. I have one year of experience working in IT as a PPC marketer, where I developed strong skills in teamwork, remote work, and familiarity with project management tools.

### Experience

> ######  [Web Game: Hangman](https://rolling-scopes-school.github.io/mi6ardnv-JSFE2023Q4/hangman/)
> ###### [Coffee Shop Website](https://rolling-scopes-school.github.io/mi6ardnv-JSFE2023Q4/coffee-house/pages/home/)
> ###### [Axit Website Layout](https://mi6ardnv.github.io/Layout-template-Axit/dist/)
>###### [SVG Graphics Project](https://mi6ardnv.github.io/Melody-layout/)

### Skills
> 1. HTML/CSS
> 2. Javascript
> 3. Figma(_and other graphic editors_)
> 4. Git/Github  

### Education

> ###### Pyryatyn branch of the European University
> **Degree:** Professional Junior Bachelor  
> **Major:** 121 Software Engineering  
> **Dates:** September 2021 – June 2024

### Languages
> * **Russian** _Native_
> * **English** _B1_ ([EF SET certificate](https://cert.efset.org/7wUq2x))
> * **German** _A1_

### Code example
``` javascript
function duplicateEncode(word){
  let result = '';
  word = word.toLowerCase().split('');
    for(let i = 0; i < word.length; i++){
        for(let j = 0; j < word.length; j++){
            if(i != j){
                if(word[i] == word[j]){
                  result += ')'
                  break
                }
            }
        }
      if(result.length == i + 1){
        continue
      }
      result += '('
    }
  return result
}
```