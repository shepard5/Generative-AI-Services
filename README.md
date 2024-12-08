AI Generated Document Drafting 

Download the latest version of Python: https://www.python.org/downloads/

1) Mac: open Terminal and type in the following commands:


chmod +x 'path/to/py_script.py' #Enter the unique file location of the python script

chmod +x 'path/to/Cover Letter Generator.sh' #Enter the unique file location of the shell script


Mac & Windows:

pip install openai

pip install PyPDF2

pip install requests

pip install bs4

pip install docx

2) Edit the py script to include your OpenAI API Key.

3) Open ‘Cover Letter Generator.’

4) A file window will open, select context. Must be PDF format.

5) Enter the LinkedIn job URL, if for job application related files – Make sure to copy the link following this screenshot. Sometimes won’t work if using the URL at the top of the browser.

![Picture1](https://github.com/shepard5/You-re-Covered/assets/108085853/7db44e5b-4e2f-46b2-8b33-48f6a5cae4f9)

6) Give it a few seconds then enter your name etc (for added context) - Once those details are entered the cover letter will appear in the working directory i.e. the same folder the script is run from.

7) (Optional) Rename or move cover letters to a different folder after they’re made if you want them for later - otherwise when the script runs again it’ll be overwritten with whatever new cover letter you’re trying to make.

Note: This tool is known to work for all LinkedIn job postings, other website formats haven't been tested, but may work for some. The cover letter provided is a draft and should be used as such, many companies use GPT recognition software.


