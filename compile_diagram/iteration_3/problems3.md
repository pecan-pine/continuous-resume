Solution:
- Refactor components into Python dictionaries storing plaintext (now 
this is a MongoDB database storing plaintext).
- Dictionaries are fed into Jinja templates to produce resumes (one
template for each file type).
- From the specifications, templates, and components, the program
produces .tex, .txt, .html, and .md versions of resume for each resume specification.
- Easy to change data / format. 
- Easy to fix typos.

Problem:
- There are still 4 templates to maintain, with similar information in each. 
- Updating website is still tedious.
- Need to have website repository downloaded on the same computer as 
my resume in order to update the website. 