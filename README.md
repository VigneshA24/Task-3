# Task-3
Day-3 Task
# Day-3-task

1. Own resume Data in JSON Format

{
"Resume": {
"name": "Thangavel S",
"email": "parvathythangam1402@gmail.com",
"phone": "9600704401",
"Qualification": "Diploma in Mechanical Engineering",
"Location": {
"address": "Krishna nagar",
"Postal code": 635126,
"city": "Hosur",
"State": "Tamilnadu",
"Country": "India",
},

"Profiles": [
{
"network": "https://www.linkedin.com/in/thangavel-selvaraj-66381886",
"github": "https://github.com/thangam17",
}
]
},
"Work": [
{
"Company": "Titan Engineering and Automation Limited",
"Position": "Senior Production Engineer",
"start date": "27-03-2014",
"end date": "27-03-2023",
}
],
"education": [
{
"institution": "Nanjiah lingammal polytechnic college",
"department": "mechanical",
"batch start year": 2008,
"batch end year": 2011,
"study tyepe": "full time",
}
],
"languages": [
{
"languages": "tamil english",
}
],
"awards": [
{
"title": "highest km covered under 24hr in cycle",
"awarder": "india book of records",
}
],
}


2.Difference between window, screen and document in Javascript

Window

    Each browser tab has its own top-level window object. Each element has its own window object too.
    nested within a parent window. each of these windows gets its own separate global object.
    window always refers to window, but window parent and window top might refer to enclosing windows, giving acess to other execution contexts.

Screen

    The window object also has a screen object with properties describing the physical display.
    Screen properties width and height are the full screen
    screen properties availwidth and availheigth omit the toolbar.

Document

    Each window object has a document object to be rendered. These objects get confused in part because HTML elements are addded
    to the global object when assigned a unique id.

3.JSON iterate overall for loops (for, for in, for of, forEach)


var json = [
{
    "id": "thangam", 
    "msg": "hello everyone",
    "task": "daily task",
    "mail": "parvathythangam1402@gmail.com",
},
{
    "id": "gold" 
    "msg": "Welcome to all",
    "task": "day 3 task",
    "mail": "parvathythangam1402@gmail.com",
}
];
//for loop
for(var i = 0; i < json.length; i++) {
    var obj = json[i];

    console.log(obj.id);
    console.log(obj.msg);
    console.log(obj.task);
    console.log(obj.mail);

}


//for Each
json.forEach(function(obj) { console.log(obj.msg)};

//for In
for (var key in json) {
if (json.hasOwnProperty(key)) {
  console.log(json[key].id);
  //console.log(json[key].msg);
}
}


//for Of
let text = "";
for (let x of json[key].id) {
 text += x; 
}
 console.log(text);
