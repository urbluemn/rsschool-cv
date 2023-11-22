---
layout: cv
title: Nick Yaroshko's CV
---

# Nick Yaroshko
*JavaScript Developer*

## Summary  

Last few years I've been working on a different major. Currently
I'm studying and dealing with C# and ASP.Net Core, at the same
time I independently learn HTML5, CSS3 and JavaScript to
achieve optimal levels of personal performance and
accomplishment. I’ve always worked harmoniously and effectively
within a team. I want to study and grow as a software developer.
I'm learning rapidly and adapt quickly to changing situations,
maintaining an optimistic outlook when I face difficulties.


## Contact  

* Phone number : +375 (25) 933-71-62
* Email : [nyaroshko1404@gmail.com](nyaroshko1404@gmail.com)
* [GitHub](https://github.com/urbluemn)
* [LinkedIn](http://linkedin.com/in/nickyaroshko)
* Discord: @urbluemn


## Languages  

* **Russian -** Native
* **English -** B2-C1

## Education  

>**Belarusian National Technical University**  
Belarus, Minsk  
2018-2020

*Unfinished degree: Electronics Engineer*

## Experience

#### .Net Developer (graduate)
>“TeachMeSkills” online School
* C#, .Net Core, Entity Framework, REST API
* Gained a strong knowledge of OOP and design patterns.
* Learned about SQL an NoSQL databases, built my own
databases, using MSSQL and SQLite.
* Discovered CI/CD process, using GitHub Actions, Docker and
Kubernetes, got intoduced into Azure DevOps.
* Built my own web application, an
API with EF Core, an Auth server with IdentityServer4 and .Net
Core MVC project as a frontend part.

[Recipe Book API project](https://github.com/urbluemn/RecipeBook.API)  
[Recipe Book AuthServer project](https://github.com/urbluemn/Recipe.Identity)  
[Recipe Book MVC Frontend project](https://github.com/urbluemn/Recipe.MVC)

#### Web Developer (studying)
>"Rolling Stones" school
* HTML5
* CSS3
* Vanilla JavaScript
* Markdown language
* Git and GitHub

[rsschool-cv project](https://github.com/urbluemn/rsschool-cv)

## Code Example
#### This took me quiet time to solve when i was just starting:
Write a function, persistence, that takes in a positive parameter num and returns its multiplicative persistence, which is the number of times you must multiply the digits in num until you reach a single digit.
```
function persistence(num) {
   //code me
  let count = 0;
  let newArr = (num.toString().split('')).map(Number);
  if(num.toString().length === 1){
    return 0;
  }
  for(let i = 0; newArr.length > 1; i++){
    newArr = newArr.reduce((a, b) => a * b).toString().split('').map(Number);
    count++;
  }
  return count;
}
```

## Hard Skills
> C# | .Net Core | MSSQL | SQLite | PostgreSql | Design Patterns | OOP | SOLID Principals | Unit testing |  
> JavaScript | HTML5 | CSS3 | Markdown language | Git | GitHub
