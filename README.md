# Free2Choose
This repository contains the scripts and dofiles I employ to extract, clean and analyze data for my master thesis. This is by no means a Replication Package.

00a.Download_CRedocrds.ipynb: Uses Selenium to get the US Congressional Record pdf url for every day at the Senate that held a debate. Stores the pdf url and downloads and renames the pdf.

00b.OCR_CRecords.ipynb: Uses Pytesseract to extract the text from each column in the Congressional Record pdf. Stores each day's text as a txt.

00c.Clean_data.ipynb: Cleans the txt file looking for regular expressions. Transforms the data into a csv where each row is a speech made by a senator.

00d.Match_charactr.ipynb: Merges the speech data with information about each senator: Party, State, Political index.

29-11-1979.txt: This is an example of my raw txt data after being extracted with PyTesseract.


