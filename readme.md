# CLI Tool  fld-str

## Usage
Creating Folders and Files

## Overview
This CLI tool simplifies the creation of folder structures and files for React projects, providing a seamless approach to automate repetitive processes.

## Installation
To globally install the CLI tool, use the following npm command:

# sudo npm install -g fld-str


### Command Structure
To create a folder and file structure, use the following command format:

#### For multiple folder and file creation:
## mld --f /user/home/
![pic1](https://github.com/minhaz1010/folder-template-shortcut-jsx/assets/66476980/a6467246-6a3e-446b-b6f1-7bfae0b0da62)


When you run the command "fld --p /user/home/", it will create a folder named "user" in the main directory, then inside that, a folder named "home", and within the "home" folder, a file named "home.jsx" will be created. The file will contain a simple React component template.

You can chain multiple folder creation commands in a similar manner to create nested folder structures by using 
# ( / * / * / * /..... so on)

### For multiple folder and file creation:

## mld --dir /components+context/home+signup+login/
![pic2](https://github.com/minhaz1010/folder-template-shortcut-jsx/assets/66476980/50971c75-1187-43f0-8fe8-d8c42fe7a846)


Running this command will create the "components" and "context" folders in the root directory. Each of these folders will contain subfolders "home", "signup", and "login", each with a corresponding ".jsx" file and template.
### [this works on only two level i mean (/* + * + * ../* + * + */)]




