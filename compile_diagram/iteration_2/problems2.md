Solution: 
- Separate LaTeX code into "components"--string variables storing LaTeX code. For example:
    - Education (by school)
    - Work Experience (by employer)
    - Projects (categorized)
- Specification file decides which components get included in a particular resume. 
- One python program makes all versions of the resume, using one simple LaTeX template. 


Problems:
- Only produces .tex file (other file types produced by 
having Python read the LaTeX code)
- Post-processing to get .txt/.html resumes unreliable
- Updating website is still the same process