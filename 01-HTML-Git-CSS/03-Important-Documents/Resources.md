# Git/HTML/CSS
## Bash/Terminal  

[Bash Commands Cheatsheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet)

---

## SSH key  

### Generate key  
- First you must generate a key or overwrite your old one

MAC (Will copy key to clipboard!)

    tr -d '\n' < ~/.ssh/id_rsa.pub | pbcopy

WINDOWS (Will copy key to clipboard!)

    cat ~/.ssh/id_rsa.pub | clip

### Copy existing key  

Windows:
    
    clip < ~/.ssh/id_rsa.pub

Mac:

    pbcopy < ~/.ssh/id_rsa.pub


- Then paste the key in both [Github](https://github.com/settings/keys) and [Gitlab](https://smu.bootcampcontent.com/-/profile/keys) and run the commands below to validate both keys work.

Github SSH key validation

    ssh -T git@github.com

Gitlab SSH key validation

    ssh -T git@smu.bootcampcontent.com


---

## Git  

#### [Git Basics](https://www.atlassian.com/git)  

#### [Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)  


#### Essential Git commands:  
 
>     git add <specify via symbol or file name> 
>     Example: git add .
> 
> Adds all of the changes made to the file to a state to be saved. 
> 
>     git commit -m "<message content>" 
>     Example: git commit -m "Updated index.html with new input under the id username"
> 
> Saves all of those changes along with the message to the repository. 
>     
>     git push 
> 
> Sends the changes to be saved in where the url for origin is set to.
>     
>     git status 
> 
> Gives you a message related to where your current branch is related to your last push.
>     
>     git remote -v 
> 
> Tells you the urls that are associated to the repository
>     
>     git clone <url> 
>     Example: git clone git@smu.bootcampcontent.com:SMU-Coding-Bootcamp/smu-dal-fsf-pt-07-2021-u-c
> 
> Clones the repository into a folder on your local machine at the location you run this command. > .git the command for people with ssh keys to clone the class repo!
>     
>     git pull 
> 
> Pulls the changes from the remote url to your local machine (This should be one of the few > commands you have to run with your class repo as it will pull the solutions at the end of the > day!)
>     git stash 
> 
> Hides all your changes since the last commit to help when you do things like git pull. 
> 
>     git stash pop 
>     
> Brings those changes back and tries to merge it back in.
> 
### Grace's Analogy for git: 

    Pretend you're writing a letter to someone via "snail mail".  You write your letter.  When you put the letter in the envelope? git add .  When you seal the envelope and address it? git commit -m "messageGoesHere".  When you actually mail the envelope? git push 


---

## Markdown

[Markdown Syntax](https://www.markdownguide.org/basic-syntax/)

[Guide for a professional README.md](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide)


---

## HTML

[HTML Basics](https://www.w3schools.com/html/html_intro.asp)

[A list of every standard HTML tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

[Emmet Cheatsheet (for ease of writing html in vscode)](https://docs.emmet.io/cheat-sheet/)

[Best practices for website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

[Semantic HTML](https://html.spec.whatwg.org/multipage/sections.html#the-h1-h2-h3-h4-h5-and-h6-elements)

[Why use Semantic HTML?](https://medium.com/adalab/the-importance-of-semantic-html-78e74fb75ff0)

[Semantic HTML Example](https://gist.github.com/thomd/9220049)


---

## CSS 

[CSS Basics](https://www.w3schools.com/css/css_intro.asp)

[CSS Selectors](https://www.w3schools.com/css/css_selectors.asp)

[CSS Rule reference](https://www.w3schools.com/cssref/default.asp)
