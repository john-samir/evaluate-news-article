## MyReads Web Tool

This web tool allows users to manage their books reading by specifying which books are they currently reading, want to read, and have already read.
Also allows users to search for new book and to add to those 3 categories.

This tool is implemented using React. 
the backend of this tools is provided by Udacity team.

## Notes

1. to be able to use this tool, you have to run below commands that will install all project dependencies and will open the server
```
npm install
npm start
```

2. This web tool is simply consists of 2 pages as follows: 
- **Main Page:** Contains books categoried as ("Currently Reading", "Want to Read", "Read")
- **Search Page:** Where you can search for new books and add it to any of the 3 categories

3. An **additional functionality** has been added to give you more details about each book. What you have to do is to click on the **circle green button** attached at the **Bottom Left** of each book.

4. Only books title, authors, and image are displayed for each book. If you need more details you can press on the button that is mentioned in the previous point.

## React Components
```
- BooksPage
- BookShelfList
- BookShelf
- BooksList
- Book
- BookShelfChanger
- SearchPage
```

## React Components hierarchy
```bash
├── App.js
    ├── BooksPage.js
    │   └── BookShelfList.js
    │       └── BookShelf.js
    │           └── BooksList.js
    │               └── Book.js
    │                   └── BookShelfChanger.js
    └── SearchPage.js
```


## Copyrights

This tool is implemented by **John Ghabrial** using template and API that have been given by Udacity team as part of a project  for **"Front End Web Development Advanced Nanodegree Program"** course
