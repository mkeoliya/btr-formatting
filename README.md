# BTR Formatting

We want our essays to get feedback. Let's make that happen. 

## Instructions for use
1. Ensure you have a working installation of `python`
1. Download this repository -- click on "code" and then "Download ZIP". 
1. Extract the ZIP file to a folder, and call it `btr-formatting`. 
1. Run `cd btr-formatting && pip install -r requirements.txt` on the command-line
1. Fill in the `config.json` file with your details. 
1. Save your essay as `essay.docx` and move it to the same folder as in Step 3. Your essay need not contain any headers, footers, page number, word count, or matric number. Those will be filled in for you. See `essay.docx` here for an example. 
1. Run `python btr.py`. Your formatted essay will be saved in a new file, `formatted-essay.docx`. 
1. ??
1. Enjoy the feedback!

WARNING: Currently, the formatter does not check for free-floating pointer words __within__ sentences. You must check manually for them, because it is extremely hard to detect incorrect usage of these words (free-float intended).  

Here are BTR's feedback diktats:

- 12pt header of the format
```
Critical Reflection
Sem 2, AY 2022/2023
Learning In- and Outside the Classroom
```
- 14pt text, double-spaced
- 1.25" margins, all sides
- Wordcount and matric # at bottom of document
- No free floating pointer words (`this`, `that`, `these`, `those`)
- No use of `as such`
- Page numbers on each page
