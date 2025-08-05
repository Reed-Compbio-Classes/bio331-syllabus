# Convert website to PDF

Requires the [pandoc](https://pandoc.org/installing.html) tool.

Concatenates all the files in the order that they are shown on the left-hand banner on the website. 

```
pandoc ../index.md \
    ../doc/goals.md \
    ../doc/support.md \
    ../doc/policies.md \
    ../doc/assessment.md \ 
    ../doc/schedule.md \ 
    ../doc/environment.md \ 
    ../doc/tips.md \ 
    ../doc/changelog.md \
    -o bio331-F24-syllabus.pdf \
    -M title="Bio331 Fall 2024 Syllabus"
``` 

Then, move the file to `../doc/archive/`.