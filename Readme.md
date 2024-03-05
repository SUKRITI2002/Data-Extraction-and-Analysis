1. *Save Files in a Folder:*
   - Save all the Python files (dataextraction.py, textanalysis.py) in a folder on your computer.

2. *Create Folders for Text Files and Dictionaries:*
   - Create a folder to store all the extracted text files from the URLs.
   - Create a folder named masterdictionary to store the positive and negative word dictionaries.
   - Inside the masterdictionary folder, place the positive and negative word text files.
   - Create a folder named stopwords to store the stopwords text file.

3. *Prepare Output Excel File:*
   - Create an output Excel file (output.xlsx) in the same folder where you have saved the Python files.
   - Ensure that the Excel file has the required structure for storing the relevant output data.

4. *Open Folder in VSCode:*
   - Open Visual Studio Code (VSCode) and navigate to the folder where you have saved all the files.

5. *Install Required Libraries:*
   - Open the terminal in VSCode.
   - Use the following commands to install the required libraries:
     
     pip install requests
     pip install beautifulsoup4
     pip install nltk
     pip install pandas
     
   - These commands will install the necessary libraries (requests, beautifulsoup4, nltk, pandas) for your project.

6. *Replace File Paths:*
   - Open the Python files (dataextraction.py, textanalysis.py) in VSCode.
   - Replace the file paths with the correct paths to the extracted URLs, master dictionary, stopwords, and output Excel file.
   - Ensure that the paths are correctly specified to access the required files.

7. *Run the Program:*
   - After updating the file paths, run the dataextraction.py file first to extract the data from the URLs and save the text files.
   - Then, run the textanalysis.py file to perform text analysis and generate the output data.
   - Make sure to check the output Excel file to verify that the relevant output data has been stored correctly.
