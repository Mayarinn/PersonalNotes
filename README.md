## *NotaBene*

1. Do not forget `git pull` changes
1. **Think twice before using `--force` !!!**

# To Do

1. [**Done**] Move To Do list from Storyboards repo here
2. [*To Do*] Move here Studies plans from Notion and other notes
3. [*In process*] Add Markdown Notes
4. [*In process*] Add Git Notes
5. [*To Do*] Think about naming convention

## Further studies

1. Scroll View
2. Constraints. Priorities and conflicts
3. [**Done**] Storyboards [video](https://www.youtube.com/watch?v=EYx3Hxs88zE&ab_channel=%D0%92%D0%BE%D0%B9%D1%82%D0%B8%D0%B2IT)
4. UIKit [video](https://www.youtube.com/watch?v=oGubB_dYoVA&ab_channel=%D0%92%D0%BE%D0%B9%D1%82%D0%B8%D0%B2IT)
5. SwiftUI [video](https://www.youtube.com/watch?v=iQk4DV1ki3k&ab_channel=%D0%92%D0%BE%D0%B9%D1%82%D0%B8%D0%B2IT)


## Workflow with a new repo

>> **_Important Notes_**:
>> 1. Use `git init` inside the inner project folder
>> 2. Do not commit the `project.xcodeproj` and `.DS_Store`

```
> cd your/project/directory
>
> git init
>
> git config --show-scope --get user.email
my-work@email.com
>
> git config user.email "my-github@email.com"
>
> git config --show-scope --get user.email
my-github@email.com
>
> git remote -v
>
> git remote add PersonalNotes https://github.com/Mayarinn/PersonalNotes.git
>
> git remote -v
PersonalNotes	https://github.com/Mayarinn/PersonalNotes.git (fetch)
PersonalNotes	https://github.com/Mayarinn/PersonalNotes.git (push)
>
> git stage (something)
>
> git commit -m "Initial commit"

/* You need to commit smth before using push set-upstream */

> git push --set-upstream PersonalNotes master
```

## Starting with a new device

> Accessing GitHub from CLI requires logging in. You need to use your Google (try; if not -- sammy) email and GitHub Personal Access Token (CLI calls it password!). You store it in PassHub.
