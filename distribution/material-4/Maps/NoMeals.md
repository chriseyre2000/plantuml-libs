# NoMeals


```text
material-4/Maps/NoMeals
```

```text
include('material-4/Maps/NoMeals')
```



| Illustration | NoMeals |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/NoMeals.png) | ![illustration for NoMeals](../../material-4/Maps/NoMeals.Local.png) |




## NoMeals

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element NoMeals
include('material-4/Maps/NoMeals')

' renders the element
NoMeals('NoMeals', 'No Meals', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element NoMeals
include('material-4/Maps/NoMeals')

' renders the element
NoMeals('NoMeals', 'No Meals', 'an optional tech label', 'an optional description')
@enduml
```

