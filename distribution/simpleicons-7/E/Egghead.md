# Egghead


```text
simpleicons-7/E/Egghead
```

```text
include('simpleicons-7/E/Egghead')
```



| Illustration | Egghead |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/E/Egghead.png) | ![illustration for Egghead](../../simpleicons-7/E/Egghead.Local.png) |




## Egghead

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Egghead
include('simpleicons-7/E/Egghead')

' renders the element
Egghead('Egghead', 'Egghead', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Egghead
include('simpleicons-7/E/Egghead')

' renders the element
Egghead('Egghead', 'Egghead', 'an optional tech label', 'an optional description')
@enduml
```

