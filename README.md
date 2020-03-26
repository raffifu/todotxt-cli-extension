# todotxt cli due,date,and priority add
A todo.txt addons that can add task with due date, creation date, and priority 
## Instalation
1. Make directory `.todo.actions.d` type `~/.todo.actions.d`
2. Enter that directory `cd ~/.todo.actions.d`
3. Copy file `ddp` to your directory `wget "https://raw.githubusercontent.com/raffifu/todotxt_cli_due_date_pri/master/ddp"`
4. Make your file executable `chmod u+x ddp`

## Usage
Type `todo.sh ddp [priority] [duedate]`"Your new task"
- priority format `[a-Z]`
- duedate format `['mon'-'sun'] / [next day number]`
  you can use special format such as `[td]=today, [nw]=next week or [unk]=unknown`
