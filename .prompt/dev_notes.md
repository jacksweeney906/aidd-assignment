Step 1: Planning

- Purpose: Portfolio + resume + contact hub showcasing projects and skills, with emphasis on accessibility and responsible AI-assisted development.
- Content: Bio, resume (Resume.pdf), projects (2+), Indiana-themed styling, contact form with validation, photo from provided screenshot.
- Design: Indiana palette (crimson, navy, cream), system fonts, responsive two-column -> single-column on mobile. Semantic HTML and focus styles.
- AI Setup: GitHub Copilot enabled. I will log prompts and important outcomes here.

AI prompt log:

- Prompt: "Create an accessible multi-page personal portfolio with an Indiana theme, contact form with validation, and use Resume.pdf and provided screenshot as assets."
	- Outcome: Generated base HTML pages, linked CSS, form and validation scaffold. Reviewed and adjusted markup, labels, and accessibility attributes.

- Prompt: "Add client-side validation that checks required fields, email pattern, password length, and confirm password match. Show inline error messages and prevent submission on invalid input."
	- Outcome: Added small JS validation routine, aria-live error spans, and used HTML5 attributes (required, minlength, type=email).

Reflection:

- Copilot helped scaffold pages and repetitive nav/header/footer, which saved time. I reviewed every generated piece: improved semantics, added aria-live error spans, and ensured images have alt text. I removed dangerous patterns (no auto-submitting scripts, no external network calls). Additionally Copilot got a lot wrong which is natural, all the details etc within the files I needed to go back and change but the structure of the html files and setup were very good and used.
So

Prompt 2 ChatGPT- Using my profile, as well as my resume etc replace eacb of these html files with relevant informaiton about me

Result: Since I have been using ChatGPT almost everyday for a year or so, it has been able to collect lots of data on me and create a profile. Using this I was able to get a baseline of my personal info within my files which I could then go back and edit.

I ended up modifying the suggestions, keeping some with regards to my background and changing parts of it with updated information that chatgpt did not have on me. Overall this was very efficient still instead of typing out each etc.


Where AI helped you save time - Where AI made mistakes - How you balanced AI assistance with your own coding

Overall AI helped me save time with developing the general html structure. This involved the main files needed how they related to one another and some basic headers, sections, footers, stylinh for each. AI was also somewhat useful in coming up with personal details such as background info, contact, resume, which I went back to modify. AI did make some mistakes such as personal details, putting screenshots in the wrong spots, weird formatting or website layout. I balanced AI assistance with my own coding by going back and reviewing each piece in the live website making changes while asking Copilot for assistance. I would then code in personal details, images, projects, etc that I could do better than the AI. AI on the other hand helped me in completing the more rudamentory tasks.
