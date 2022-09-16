# Static site Generator (ag-ssg)

DSP909 - Static stite generator whichcoverts the.txt file to static .html page. In this version of project we need to create the command line tool which will help to process the .txt file to .html files

## Outline

In this release version user can do the following

1. User can use the command line tool to specify the particular .txt file to convert it into .html file type.
2. User can specify the folder which contains multiple .txt files to convert all of them in seperate .html file type.

## Requirements

- This tool is built using the [Node.js](https://nodejs.org/en/)

# Getting started

- Clone the repository into your local drive

```
git clone  <repository url> <project_name>
```

- Install all the dependencies

```
cd <project_name>
npm install
```

- Run the npm link module

```
npm link
```

- Build and run the project

```
 node app.js - <command line arguments>
```

## Command line options

Command line option available for User in this tool

| Option               | Detailed Inforamtion                      |
| -------------------- | ----------------------------------------- |
| **-v,--version**     | Print the tool's name and current version |
| **-i, --input file** | Allow users to specify the file           |
| **-h, --help**       | Prints information about usage of tool    |

##.txt file for testing
Folder in directory named **textFile** contains all the text file which i have used to test my code.

## Running the Tool with different commands

| Command type                 | Description                                                         |
| ---------------------------- | ------------------------------------------------------------------- |
| `node app.js -i <.txt file>` | Create single .html file                                            |
| `node app.js -i <folder>`    | Create all the .txt file to .html which are available in the folder |
