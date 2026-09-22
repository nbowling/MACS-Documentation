# MACS-Guide
Version 0.1 now available in Drafts folder and OneDrive folder

## To Do
- Add two more worked examples
- Maintain and check intra / extra document links
- Fill out references
- Beta review

## Date 22/09/2026
- Version 0.1.1 updated and release for review
- Normalisation subsection expanded
- Fourier Transform subsection expanded
- Installation and configuration section added
- First pass figure(s) numbers and pages rationalised
- Database and Recordings section updated

## Date 13/09/2026
- Version 0.1 released to document beta review
- Database section added
- Text editing and clean up
- Some internal and external links enabled
- Interface section updated

## Date 30/08/2026
- Significant rewrite of section 6 adding electrical motor properties
- Addition of first worked example

## Date 18/08/2026
- Edit #01 of s6 "remove duplicate "What you will learn"
- Correct gear / pinion order
- Clean Repo and remove redundant branches
- Add publish folder to Main

## Date 14/08/2026
- Total rewrite of section 6 as a guide to classifcation/sonar workflow
- Sections 6 and 7 merged

## Date 10/08/2026
- Database branch added

## Date 09/08/2026
- Tools and Examples branches added
- Some useful(?) tools added to Tools folder in tools branch

## Date 07/08/2026
- Develop merged into main
- Worked examples started
- Folder cleanups
- No new version

## Date 01/08/2026
- Proof read sections 1-3 and 5 - 7
- Some explanatory text clarified with examples
- Rewrite Broadband / Narrowband section
- Checked application save directories
- Section links checked and updated
- Appendix C added for mathematical background (may be discarded)
- Classification Workflow tidied up
- Time / Frequency axes corrected on page 15 (tbc)

## Date: 31/07/2026
On Maths branch
- Version 0.0.7 (still called v6) until push to develop
- Proof read and editing started
- Maths reviewed
- Normalisation subsection expanded
- Appendix C - More maths added
- Classification guide re-established preparatory to evolving into a worked example

## Date: 28/07/2026
On Develop branch
- Unified versions 5a and 5b into version 0.0.6
- Per Panel section merged into Application Interface Section
- Workflow section moved up
- Appendix A replaces "Noob's Note"
- Image placement tightened

## Date: 26/07/2026
- Rewrite of Application Interface Section
- Conversion of images to vectors
- Push to branch develop
- App_interface branch deleted

## Date: 24/07/2026
- Rewrite of Sound analysis section
- Reorder Normalisation section to match workflow
- Changes merged with develop branch
- Sonar branch deleted
- LaTeX automation Make file created

## Date: 20/07/2026

- .gitignore file added
- Develop branch added
- improve_overview branch added

## Date: 19/07/2026

Documentation for Mahzel's MNW Acoustic Classification Suite (MACS).

### Current Status

Update 17/07/2026
Sections re-ordered to make more narrative sense

Overview expanded to include more information about what the application does and why an MNW player may need it.

**NEW SECTION --- SONAR and Sound Analysis an Introduction**. Gives background to the key technologies used in-game and in MACS. The purpose of this is to separate the required knowledge to understand MACs, from the mathematical under-pinnings which I think would sit better in an Appendix. The manual may work better if it concentrates on actions and workflow to achieve desired outcomes.

I'm not particularly happy with the screen grabs. Looks okay on screen but when printed the images lose quality and become quite blurry. Most have been converted to vector graphics now to help with scaling. I will investigate whether it's possible to get better images for the final production.

- Document is now fully \LaTeX. Workflow:  Each Section Raw Text (in its own directory) → Imported to VSCode as *.tex file → Aggregated in main.tex as an import → pdfLatex → pdf file. The reason for this is that although Markdown is easy to work with I find it limiting for detailed typesetting.
- Each section can be viewed in Working → \LaTeX folder
- Active pdf draft in Working → Drafts.
- Versions with an (a) suffix are the plain, noobless version (preferred but still open to your opinion) versions with (b) suffix are the "noobed" versions.
- A **Resources** folder has been created → Resources contains the books / papers I'm currently using to build my own knowledge. Feel free to make use of them as you want. Obviously "sources" like SciHub are not strictly "legal" in some jurisdictions!



