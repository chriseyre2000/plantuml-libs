# Github


```text
simpleicons-7/G/Github
```

```text
include('simpleicons-7/G/Github')
```



| Illustration | Github |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/G/Github.png) | ![illustration for Github](../../simpleicons-7/G/Github.Local.png) |




## Github

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Github
include('simpleicons-7/G/Github')

' renders the element
Github('Github', 'Github', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Github
include('simpleicons-7/G/Github')

' renders the element
Github('Github', 'Github', 'an optional tech label', 'an optional description')
@enduml
```

