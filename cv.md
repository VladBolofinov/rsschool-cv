# Vladislav Bolofinov

# Contacts
- ##### Telegram: @vladbolofinov 
- ##### Discord: VladBolofinov#6487
- ##### Email: vlad.bolofinov@gmail.com

# About me
I am 25 years old, have a higher education at BNTU as economist. Last years worked in shop where I sell books. Last 3-4 months learn JS and want to be a frontend-developer. I think, I can become a good specialist in this field of activity. My most important goal is to get a job offer as a frontend-developer in 2023!

# Skills
- Good knowledge of HTML/CSS (also SASS preprocessor)
- Basic JS
- Git

# Code example

##### Kata from CodeWars 5kyu:
Write an algorithm that takes an array and moves all of the zeros to the end, preserving the order of the other elements.
`moveZeros([false,1,0,1,2,0,1,3,"a"]) // returns[false,1,1,2,1,3,"a",0,0]`
##### My solution
`function moveZeros(arr) {
let count = 0;
for (let i = 0; i < arr.length; i++) {
    if (arr[i] == 0 && typeof(arr[i]) === 'number') {
        arr.splice(i,1);
        count += 1;
        i--;
    }
}
for (let i = 0; i < count; i++) {
    arr.push(0);
}
  return arr;
}`

# Education
- #### University: Belarusian National Technical University
##### Economics and management at the enterprise
- #### Courses: JavaScript/Front-end 2022Q3 (in progress)

# English
A2