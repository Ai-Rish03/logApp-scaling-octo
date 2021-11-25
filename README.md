# Fornal Work: Documentation


> **Name**  

- Use of Markdown Language  
___  

***  

> **Description**  

-  Markdown can be used for everything. People use it to create websites, documents, notes, books, presentations, email messages, and technical documentation. Markdown is portable.  
 -  Files containing Markdown-formatted text can be opened using virtually any application.    

 ___  

 ***  

 [**References**]  
 (https://www.markdownguide.org/getting-started/)  

 > **Visuals**  
 
 ![Markdown](https://user-images.githubusercontent.com/57039079/67622173-2b835e80-f807-11e9-821d-bfbb688bc329.gif)  

 ___  

 ***
> **Installation**  

{  
      
    Step 1: Install a Markdown compiler  
    For this walkthrough, let's use the popular Node.js module, marked.  
    
    Example:  
    npm install -g marked
}  

{  
    
    Step 2: Create a simple MD file  
    Open VS Code on an empty folder and create a sample.md file.  

    Example:  
    Hello Markdown in VS Code!  
    This is a simple introduction to compiling Markdown in VS Code. 

    Things you'll need:  
    * [node](https://nodejs.org)  
    * [marked](https://www.npmjs.com/package/marked)  
    * [tasks.json](/docs/editor/tasks.md)  
    
    ## Section Title  
    > This block quote is here for your information.
}

{  
    
    Step 3: Create tasks.json  
    The next step is to set up the task configuration. To do this open the Command Palette with kb(workbench.action.showCommands) and type in Configure Task Runner, press kbstyle(Enter) to select it.  
    
    This will create a sample tasks.json file in the .vscode folder. The initial file has a large number of examples within it.  

    Example:  
    {
    "version": "0.1.0",
    "command": "marked",
    "isShellCommand": true,
    "args": ["sample.md", "-o", "sample.html"]
}  

{  
    
    Step 4: Run the Build Task  
    As this is the only task in the file you can execute it by simply pressing kb(workbench.action.tasks.build) (Run Build Task). At this point you will see an additional file show up in the file list sample.html.  
    
    The sample Markdown file did not have any compile problems, so by running the task all that happened was a corresponding sample.html file was created
}  

___  

***
> **Authors**  

**IRISH F. FORNAL**  
![Me IMG](IMG_20200922180839.jpg)
