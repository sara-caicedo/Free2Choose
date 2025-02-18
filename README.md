# Free2Choose
This repository contains the scripts and dofiles I employ to extract, clean and analyze data for my master thesis. This is by no means a Replication Package.

**_00a.Download_CRedocrds.ipynb_**: Uses Selenium to get the US Congressional Record pdf url for every day at the Senate that held a debate. Stores the pdf url and downloads and renames the pdf.

**_00b.OCR_CRecords.ipynb_**: Uses PyTesseract to extract the text from each column in the Congressional Record pdf. Stores each day's text as a txt.

**_00c.Clean_data.ipynb_**: Cleans the txt file looking for regular expressions. Transforms the data into a csv where each row is a speech made by a senator.

**00d.Match_charactr.ipynb**: Merges the speech data with information about each senator: Party, State, Political index.

**_29-11-1979.txt_**: This is an example of my raw txt data after being extracted with PyTesseract.


