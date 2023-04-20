# Automatic File Sorter in File Explorer Using python

This code is used to group files in a folder based on their file extensions. First, the code defines the types of file extensions that will be grouped such as audio, video, image, and document. Next, the code prompts the user to input the location of the folder to be organized.

After that, the code creates functions to check the file extension type of a file and move it to the appropriate folder. The code also creates new folders for each file extension type if they do not exist.

Finally, the code moves each file to the appropriate folder based on their file extension. If a file has been moved, a message will be displayed on the console indicating that the file has been moved to the appropriate folder.

## Syntax:

- import os and import shutil are used to import the necessary modules for the code to work.
- input() is used to prompt the user to input the location of the folder to be organized.
- os.listdir() is used to list all files in the directory.
- os.path.splitext() is used to split the filename and its extension.
- os.path.exists() is used to check if a folder exists or not.
- os.makedirs() is used to create a new folder.
- shutil.move() is used to move the file to the appropriate folder.

## Functions:

- is_data(path) is used to check if a file is a data file (.csv).
- is_audio(path) is used to check if a file is an audio file.
- is_video(path) is used to check if a file is a video file.
- is_image(path) is used to check if a file is an image file.
- is_screenshot(path) is used to check if a file is a screenshot image.
- is_document(path) is used to check if a file is a document file.
- The code also uses conditional statements (if, elif, and else) to determine which function to use and which folder to move the file to.
