# Heroku


```text
simpleicons-7/H/Heroku
```

```text
include('simpleicons-7/H/Heroku')
```



| Illustration | Heroku |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/H/Heroku.png) | ![illustration for Heroku](../../simpleicons-7/H/Heroku.Local.png) |




## Heroku

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Heroku
include('simpleicons-7/H/Heroku')

' renders the element
Heroku('Heroku', 'Heroku', 'an optional tech label', 'an optional description')
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
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Heroku
include('simpleicons-7/H/Heroku')

' renders the element
Heroku('Heroku', 'Heroku', 'an optional tech label', 'an optional description')
@enduml
```

