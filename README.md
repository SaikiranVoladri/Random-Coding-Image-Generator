# Random-Coding-Image-Generator
Random Coding Image Generator


const accessKey = 'KAUIqn7nY4obFSaPk0olfrQagyAyt46aZilfbls0NAQ'; 
const apiUrl = 'https://api.unsplash.com/photos/random';

fetch(apiUrl, { 
  headers: { 
    Authorization: `Client-ID ${aKAUIqn7nY4obFSaPk0olfrQagyAyt46aZilfbls0NAQ}`
  } 
})
.then(response => response.json())
.then(data => { 
  const imageUrl = data.urls.regular; 
  console.log('Random image URL:', imageUrl); 
})
.catch(error => console.error(error));









