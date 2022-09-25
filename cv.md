# Artyom Bagaev

## Contacts

* Location: Astrakhan, Russia
* Phone: +79XXXXXXXXX
* GitHub: [VaultDweller13](https://github.com/VaultDweller13)
* Discord: Corwin13(@VaultDweller13)

## About me

Currently working as instrumentation and control engineer, my true passion is information technology and computer science. My goal is to become highly professional programmer equipped with diverse, relevant stack of technologies.  

It's hard to imagine today's world without Internet - it permeates almost every aspect of our life. Technologies define who we are, giving us endless possibilities to create, to express ourselves, to be a part of rapidly growing, evolving community, which unite people all around the globe. I aspire to be an active part of this community.

## My skills

* HTML5 & CSS3
* JavaScript
* Python basics
* Git
* Visual Studio Code
* Chrome Dev Tools, Firefox Dev Tools


## Code examples 

Check if brackets sequence valid, with config provided.

```
function check(str, bracketsConfig) {
  const stack = [];

  for (let i = 0; i < str.length; i++) {
    const currentBracket = str[i];
    const currentConfig = bracketsConfig.find((item) => item.includes(currentBracket));
    const openingBracket = currentConfig[0];
    const closingBracket = currentConfig[1];
   
    if (currentBracket === closingBracket && stack[stack.length - 1] === openingBracket) {
      stack.pop();
    } else stack.push(currentBracket);
  }
 
  return !stack.length;
}
```

## Work experience

* [Travel](https://vaultdweller13.github.io/travel/)
* [Momentum](https://vaultdweller13.github.io/Momentum/)
* [Codejam Eldritch horror](https://vaultdweller13.github.io/codejam-eldritch/)
* [Etch-a-sketch](https://vaultdweller13.github.io/etch-a-sketch/)


## Education

* Astrakhan State Technical University
* CS50 lectures
* RS School JE/FE Pre-School 2022Q2
* The Odin Project (in progress)

## Languages

* Russian - Native
* English - Intermediate (B1)
