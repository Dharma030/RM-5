# RM-5
1.for the given  JSON iterate overall for loops (for , for in , for each, for of)

Here's an example JSON object that we can use to iterate over with different types of loops:

{
  "name": "Dharma",
  "age": 22,
  "city": "New York",
  "skills": ["JavaScript", "Python", "HTML", "CSS"]
}

Now let's see how we can iterate over this JSON object using different types of loops:

For loop:

const jsonObject = {
  "name": "Dharma",
  "age": 22,
  "city": "New York",
  "skills": ["JavaScript", "Python", "HTML", "CSS"]
};

for (let key in jsonObject) {
  console.log(key, jsonObject[key]);
}

For...in loop:

const jsonObject = {
  "name": "Dharma",
  "age": 22,
  "city": "New York",
  "skills": ["JavaScript", "Python", "HTML", "CSS"]
};

for (let key in jsonObject) {
  if (jsonObject.hasOwnProperty(key)) {
    console.log(key, jsonObject[key]);
  }
}

For...of loop:

const jsonObject = {
  "name": "Dharma",
  "age": 22,
  "city": "New York",
  "skills": ["JavaScript", "Python", "HTML", "CSS"]
};

const entries = Object.entries(jsonObject);
for (const [key, value] of entries) {
  console.log(key, value);
}

For each loop (array iteration):


const jsonObject = {
  "name": "Dharma",
  "age": 22,
  "city": "New York",
  "skills": ["JavaScript", "Python", "HTML", "CSS"]
};

const skills = jsonObject.skills;
skills.forEach((skill) => {
  console.log(skill);
});

2.create a your own resume in JSON format

Here's an example of a resume represented in JSON format:

{
  "name": "Dharma",
  "age": 22,
  "email": "dh.arma@example.com",
  "phone": "123-456-7890",
  "address": "123 Main St, New York, USA",
  "education": [
    {
      "degree": "Bachelor of Science",
      "major": "Computer Science",
      "university": "XYZ University",
      "year": 2015
    },
    {
      "degree": "Master of Business Administration",
      "major": "Finance",
      "university": "ABC University",
      "year": 2017
    }
  ],
  "workExperience": [
    {
      "company": "ABC Corp",
      "position": "Software Engineer",
      "startDate": "2015-06-01",
      "endDate": "2018-12-31",
      "responsibilities": ["Developed web applications", "Collaborated with team members"]
    },
    {
      "company": "XYZ Inc",
      "position": "Senior Developer",
      "startDate": "2019-01-01",
      "endDate": null,
      "responsibilities": ["Led frontend development", "Managed client relationships"]
    }
  ],
  "skills": ["JavaScript", "Python", "HTML", "CSS"]
}
This JSON represents a resume with personal information, education details, work experience, and skills.


3.Read about the difference between window , screen , object , document in javascript

In JavaScript, the terms window, screen, object, and document refer to different entities. Here's a brief explanation of each:

window: The window object represents the browser window or tab that contains the DOM (Document Object Model). It is the global object in client-side JavaScript and provides access to various properties, methods, and events related to the current browser window or tab.

screen: The screen object represents the user's screen or display. It provides properties to obtain information about the screen's dimensions, pixel depth, available colors, etc. It is often used for tasks like determining the screen size or displaying content based on screen resolution.

object: In JavaScript, the object is a built-in data type that serves as a general-purpose container for key-value pairs. It can hold properties and methods. All objects in JavaScript are derived from the Object prototype, and they inherit its properties and methods.

document: The document object represents the HTML document loaded in the current window or tab. It provides methods and properties to interact with the content of the document, such as manipulating the DOM, accessing elements, modifying styles, creating new elements, etc.

In summary, window relates to the browser window or tab, screen represents the user's screen or display, object is a general-purpose data type, and document refers to the HTML document loaded in the browser window. Each of these entities serves different purposes in JavaScript programming.



























