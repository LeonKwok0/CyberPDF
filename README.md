# CyberPDF
CyberPDF is a  smart coordinate-based automatic PDF data batch extraction tool. 


We used Java-inspired technology to implement this application with the help of two Java based well-known APIs, Apache PDFBox and Apache POI. The developed prototype is a desktop application that can run in server platform, Windows/MacOS/Linux. Its GUI is straightforward and the look and feel is Microsoft office style.    
 
### Workflow

The first step is to either create a new project or resume an existing project. then choose one PDF from a series of PDFs with the same layout and extraction requirements (simply, choose one from the batch). This PDF is considered as the sample to help the user determine the data they wish to extract. In other words, this sample PDF will be shown on the screen and the user selects PoIs on it. 
 
The second step is to select PoIs. Just click the Start Button and use the mouse pointer to select the data you want, a dialog prompts the user to enter the aim position (AP) in the Excel file. After selecting the desired PoIs, the user can click the Save button to save those PoIs and AP in the description file. This step is simple enough that the user just needs, selecting and entering a tiny information (as shown in Figure 5). 
 
After the user saved the information in the description file, the tool asks whether he/she wants to go to the next step, extracting data through a series of PDFs (a.k.a the batch). If user decides to extract them now he/she will click OK. If he/she decides to go back at another time, he/she can click the Exit Project button on welcome panel 
 
The third step is to extract data from the series of PDFs. At first, the user needs to choose the description file, meanwhile, the model of storing data is also chosen. As of now, CyberPDF offers two data store models. One is extracting data from multi-PDFs and store them all in one excel file, row after row (i.e. N-One). Another one is extracting data from one PDF and store the data in one excel file, repeating this process until all the PDFs are processed (i.e. N-N). Then the user needs to assign the path of existing excel file or assign path and name to a new excel file. 
	In the process of extracting, a dialog pops up if the tool detects there are existing data on the selected destination in the excel file, giving the user options of either overwriting the existed data or use a next row to land the data. 

