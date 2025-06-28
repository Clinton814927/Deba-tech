# Deba-tech
1a. How do you creat a paragraph in html?
  #paragraph are created with p <tag>
1b.What is  the difference between <ol> and <ul> in html?
  #<ol> is for ordered lists, while <ul> is for unordered lists.
1c. How do you create a link  to an email address in html?
<a href="mailto:emmanuelwaribo6@gmail.com">Email Me</a>
2a.How do you creat css grid layout?
  #CSS grid layout is created using the display: grid; property on a container element.
2b.What is the purpose of CSS custom propertise (variables)?
  #CSS custom properties allow you to define reusable values that can be used throughout your stylesheet.
2c.What is the di9fference between grid and flexbox in CSS?
  #Grid is a two-dimensional layout system that allows you to create complex layouts with rows and columns, while Flexbox is a one-dimensional layout system that is used for aligning items in a single direction (either row or column).
3a. What are the purpose of closures in javascript?
    #Closures allow functions to have access to variables from their outer scope even after that scope has finished executing.
3b. How do you create a promises and async/await in javascript?
    #Promises are created using the Promise constructor, and async/await is used to handle asynchronous operations in a more readable way. Example:
```javascript
async function fetchData() {
    try {
        const response = await fetch('https://api.example.com/data');
        const data = await response.json();
        console.log(data);
    } catch (error) {
        console.error('Error fetching data:', error);
    }
}
fetchData();
