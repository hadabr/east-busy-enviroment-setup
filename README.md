# Easy frontend framework setup
small teams and open source projects
##### Сontents:
[Task management](#Task management)
[Time management](#Time management])
## Project and time management
### Task management
```Tool:``` [*Trello, quire, Asana or Jira etc.*]  
```Pattern:``` **Kanban-based pattern**  
- main workflow is split into ```ideas```, ```tasks```, ```issues``` and ```blocked``` boards by default; also, ```common``` list 
 
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_102.png?raw=true)
  
- boards follow columns template: 
TO-DOs &nbsp;⇒&nbsp; In process &nbsp;⇒&nbsp; Completed &nbsp;*or*&nbsp; Postponed   
![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams.png?raw=true)  
> As here is a simpler approach than Scrum - we have a *non-iterative* one-dimensional straightforward flow. Anyway, tasks still can be _postponed_ or *blocked* for a time and reopen later.  

- tasks are moved between boards and inside a board, changing their status

<img src="https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams2.png?raw=true" width="420"/><img src="https://github.com/hadabr/assets/blob/master/working-enviroment-setup/sams1.png?raw=true" width="420"/>  
__  
*be sure, that **blocked** will not appear on your Calendar; it can be set as non-tracking board or i.e. board with only *completed* column, which will not appear in the calendar

- sublists
> in case of a complexed macrotask with a lot of subtasks and details, notes or repetitive processes - **when to unfold a task is more important than its terms**, better to use **sublists**

![image](https://github.com/hadabr/assets/blob/master/working-enviroment-setup/Screenshot_105.png?raw=true)  

```Pattern:``` **Context-based tags and filters**
> as known, Kanban used system of colorful priority cards to control the flow; fo the same approach we are using colorful tags
> 1) to give more information about a task from first sight  
> 2) allows to apply filters and make a search through tasks simpler  
> it is suggested to use so few tags how possible    
- (optional) **categories** tags:  
if you don't have on task manager categories, you can set it through tags ```PM```, ```development```, ```design```, ```deployment``` etc.; by default it can be sections from this setup
- **priority** tags:  
in the next order:  

non-tagged tasks - you can consider it like "general"  
```main``` - highest, tasks on which depend a lot of other  
```other``` - vice versa to *main*; you can consider them as "in project, but something additional"  
```extra``` - lowest, *postponed* or non-cored tasks, some features can be added later  
- **special** tags: 

```urgent``` - of course, you can set directly priority; plus, there is easy to observe overdue tasks, but sometimes it just needs more attention   
```discussion``` - something on a task needs live text/talk conversation  
- not tags, but **deadlines**:  

| routine       | weekly/monthly | overall  |
| ------------- |---------------| -----  |
| repetitive, "never-ending" tasks     | deadline by a date and hours | no fixed deadline    |

- good task has only 2-3 tags  
- at the end set the same **filters**, based on your tags, for every board/list you have  
```Concept:``` **Notified and Cross-conected**
🔗
#### Time management
```Tool:``` **Toggl**  
```Pattern:``` **Pomodoro** 
  
## Development 
Toolset:    
Patterns and core concepts:  
SASS:  
JS:
## UI/UX design and prototyping

## Deployment
```Disclaymer:``` [*...*]  
```License:``` [*...*]  
```Credist:``` [*...*]  


> оо

###### before start:
```
before start 
- check if in .gitignore contains next lines:
dist/
src/styles/
node_modules/
- install node modules:
~$ npm install
- run liveserver:
~$ npm start
you should see opened index.html and sass watching for changes
```
