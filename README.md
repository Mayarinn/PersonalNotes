## *NotaBene*

1. Do not forget `git pull` changes
1. **Think twice before using `--force` !!!**
1. Command + Option + Esc ~ Ctrl + Alt + Del 

## Further studies

1. Constraints. Priorities and conflicts
2. [**Done**] Storyboards [video](https://www.youtube.com/watch?v=EYx3Hxs88zE&ab_channel=%D0%92%D0%BE%D0%B9%D1%82%D0%B8%D0%B2IT)
3. [**Done**] UIKit [video](https://www.youtube.com/watch?v=oGubB_dYoVA&ab_channel=%D0%92%D0%BE%D0%B9%D1%82%D0%B8%D0%B2IT)
4. SwiftUI [video](https://www.youtube.com/watch?v=iQk4DV1ki3k&ab_channel=%D0%92%D0%BE%D0%B9%D1%82%D0%B8%D0%B2IT)
5. XCode Crash Course
6. [Swiftbook Swift for Beginers](https://www.youtube.com/playlist?list=PLtovLaW_R9-N-KECYTUWqQaVtBXhufJfw) 

### Coursera courses

1. [LearnQuest iOS Specialization](Specialization)
- 1. [Introduction to Programming in Swift 5](https://www.coursera.org/learn/swift-5-programming-introduction?specialization=swift-5-ios-app-developer)
- 2. [Introduction to iOS App Development with Swift 5](https://www.coursera.org/learn/ios-app-development-swift-5?specialization=swift-5-ios-app-developer)
- 3. [Tables, Data & Networking in iOS](https://www.coursera.org/learn/swift-ios-tables-networking?specialization=swift-5-ios-app-developer)
2. [MFTI Introduction to iOS Development](https://www.coursera.org/learn/ios-razrabotka-na-swift/)
3. [Meta Programming Fundamentals in Swift](https://www.coursera.org/learn/programming-fundamentals-swift)
- 1. from spezialization [Meta iOS Developer](https://www.coursera.org/professional-certificates/meta-ios-developer)
- 2. spezialization [first course](https://www.coursera.org/learn/introduction-to-ios-mobile-application-development)

### Unsorted studies

1. Unix (Linux)
2. Algorithms (MIT lectures)
3. Cryptography
4. Git, GitLab
5. MVC
6. Frameworks, CocoaPods
7. Objective-C
8. Python


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
