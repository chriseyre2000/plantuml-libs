# CodeFork


```text
fontawesome-6/Solid/CodeFork
```

```text
include('fontawesome-6/Solid/CodeFork')
```



| Illustration | CodeFork |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/CodeFork.png) | ![illustration for CodeFork](../../fontawesome-6/Solid/CodeFork.Local.png) |




## CodeFork

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CodeFork
include('fontawesome-6/Solid/CodeFork')

' renders the element
CodeFork('CodeFork', 'Code Fork', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element CodeFork
include('fontawesome-6/Solid/CodeFork')

' renders the element
CodeFork('CodeFork', 'Code Fork', 'an optional tech label', 'an optional description')
@enduml
```

