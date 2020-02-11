# A01185666quiz
   
    Q2: Is the keyword "fixes" the only way to auto-close an issue from a PR 
    (pull request). Is there other keywords that can accomplish the same thing?
    
    There are other keywords to auto-close an issue including:
    close
    closes
    closed
    fix
    fixes
    fixed
    resolve
    resolves
    resolved

    
    
    Q3: Do you have to create a new PR EVERYTIME you want to close an issue,
    or is it possible to close multiple issues within a single PR? If so, 
    how?
    
    You can mention several issues in one PR comment.  For example, in the comments of a PR you can say: fixes #1, fixes #2, fixes #3. 
    
    
    Q4: Provide an example of using map that is different from the one I have done.
    Your example must use map both as a named function declaration and with an
    anonymous function. 
    
    let numbers = [4, 9, 16, 25];

    // named transformation function:
    function squareRoot() {
      Math.sqrt
    }
    numbers.map(squareRoot());

    // anonymous function:
    numbers.map(Math.sqrt);
    
    
    Within comments, explain exactly what map is doing. Finally, why is the
    "transformation function" we discussed in class sometimes referred to 
    as a callback function.
    
    refer to app.js
