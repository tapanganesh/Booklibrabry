# Booklibrary
Developed by Gautham Mallipeddi, Kommineni Srinivasa Deepesh, Kottakota Akhilesh Kumandan and Naram Tapan Ganesh

This prototype stood first in the Software Hackathon which was held during Convergence 2k21 (The technical fest of VNR Vignana Jyothi Institute of Engineering & Technology)

About the project:
For this prototype, the syllabus sheet of VNR VJIET for B.Tech 1st year was taken. The syllabus sheet is downloaded in the directory where the file "Final Code.ipynb" is saved.
On running the file - "Final Code.ipynb", the user will be asked to input a pdf file that the user wants to organize into a file.
After uploading the file, the file will be stored in a folder in the specified directory. Here the parent directory was taken as '/Users/gauthammallipeddi/Docs/College/'. Therefore, all the folders created will be created in this directory only.

The code first converts the pdf uploaded to images and extracts all the words from the images removing all the stop words and tokenizing the important words. The tokenized words are then mapped to the words that appear in the syllabus sheet. The unit that matches with most words in the pdf is identified as the appropriate unit and moved to a folder of the subject containing that particular unit.