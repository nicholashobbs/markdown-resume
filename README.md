```
git clone https://github.com/sdsawtelle/markdown-resume.git
cd markdown-resume
pandoc -o resume.html -c style.css resume.md -s
wkhtmltopdf resume.html resume.pdf 
pandoc -o resume.docx --reference-docx=resume-docx-reference.docx resume.md
```
