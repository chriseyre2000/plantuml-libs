# Pug


```text
simpleicons-7/P/Pug
```

```text
include('simpleicons-7/P/Pug')
```



| Illustration | Pug |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Pug.png) | ![illustration for Pug](../../simpleicons-7/P/Pug.Local.png) |




## Pug

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Pug
include('simpleicons-7/P/Pug')

' renders the element
Pug('Pug', 'Pug', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pug
include('simpleicons-7/P/Pug')

' renders the element
Pug('Pug', 'Pug', 'an optional tech label', 'an optional description')
@enduml
```

