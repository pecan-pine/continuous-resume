# Continuous Resume Project

This is my attempt to document a project which has 
become relatively spread-out. The project is a resume
updating system. In it's current form, I have resume
data stored in a MongoDB database. The data gets fed into 
several Jinja templates to produce resumes with slightly different
content and several different file types. 

Here is a brief history of the project:

## Starting Point:

Before I started this project, I had different .tex files
storing different versions of my resume. For example, I had a 
teaching resume, and a software development resume. Each 
resume had slightly different content to emphasize different 
skills of mine, or different points in my career. 

When I made my website, I created JavaScript functions
which would insert an HTML version of my resume into different
parts of the website. To do this, I needed to have an HTML 
resume. So I wrote a Python program to parse the LaTeX code 
and re-write it into HTML. This generally needed a little bit of 
editing afterwards, so updating my website after updating my resume
was tedious. 

Problems:
- Changing format for multiple copies is tedious
- Making python convert .tex to .txt and .html is error-prone
- Many copies of mostly the same file
- Difficult to maintain

![iteration 1](./compile_diagram/iteration_1/diagram1.pdf)