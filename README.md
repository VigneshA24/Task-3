# Task-3
Day-3 Task
# Day-3-task

1. Own resume Data in JSON Format

{
"Resume": {
"name": "VIGNESH A",
"email": "avickyvignesh2001@gmail.com",
"phone": "9597913275",
"Qualification": "Diploma in Mechanical Engineering",
"Location": {
"address": "dinnur",
"Postal code": 635109,
"city": "Hosur",
"State": "Tamilnadu",
"Country": "India",
},

"Profiles": [
{
"network": "https://www.linkedin.com/in/vignesh-a-741a67216",
"github": "https://github.com/VigneshA24",
}
]
},
"Work": [
{
"Company": "Titan Engineering and Automation Limited",
"Position": "Senior Production Engineer",
"start year": "2019",
"end year": "still working",
}
],
"education": [
{
"institution": "Tamilnadu polytechnic college",
"department": "mechanical",
"batch start year": 2016,
"batch end year": 2019,
"study type": "full time",
}
],
"languages": [
{
"languages": "tamil english",
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
