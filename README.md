# Cover Letter Generator and Job Organizer (.exe edition)

## Description

A desktop app that serves as a spreadsheet that generates pdf files based on information of each record. The original purpose is to serve as a centralized hub for job applications and to generate cover letters using template. It was originally written in 2018 for myself. I find the letters generated still more logically consistent than Large Language Models (I did not learn the customer services skills when teaching at a college!). This app is written in Python and processed using pyinstaller, and contains all files needed to run on windows.

## Help! My AntiVirus Software Claims that It's a Virus!

Unfortunately, this could happen to Python projects processed by pyinstaller. If you do not wish to white list the program in your AntiVirus Software, and if you are comfortable installing Python and potentially a few packages, check out [the pyw version of this app](https://github.com/fanmagnus/CoverGen_pyw).

## How to Use?

Excute the RUN.vbs in the top folder. You can add a shortcut to your desktop for quick access.

## Features

- You can store job information in the main menu, including the %x, %y, %z (see below), the hiring manager's name, address, URL and notes. You can color label each job for quick sorting.
- You can use text placeholders %x, %y and %z when generating cover letters. For example, you can use %x as the job title, %y as company name, and %z as the referral.
- You have formating options such as text font, text size, and choice of whether certain variables such as dates will show in the letter.
- You can store your own info like name and address, so no need to type them in again.
- You must select a folder to store the generated letters. You can choose to open the pdf letter upon generation to review.
- You can write up to 10 different sections for use in your letter. Use placeholders (%x, %y and %z) at will in the sections.
- You can preset 3 different profiles, each profile specifies which sections to show up in the letter and in what order.
- You are allowed 3 save files, for more flexibility.

## Contact

Need help? shoot me an email at [fanmagnus@gmail.com](mailto:fanmagnus@gmail.com).

## License

[MIT](https://choosealicense.com/licenses/mit/)

