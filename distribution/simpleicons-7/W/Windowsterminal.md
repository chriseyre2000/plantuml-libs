# Windowsterminal


```text
simpleicons-7/W/Windowsterminal
```

```text
include('simpleicons-7/W/Windowsterminal')
```



| Illustration | Windowsterminal |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/W/Windowsterminal.png) | ![illustration for Windowsterminal](../../simpleicons-7/W/Windowsterminal.Local.png) |




## Windowsterminal

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Windowsterminal
include('simpleicons-7/W/Windowsterminal')

' renders the element
Windowsterminal('Windowsterminal', 'Windowsterminal', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Windowsterminal
include('simpleicons-7/W/Windowsterminal')

' renders the element
Windowsterminal('Windowsterminal', 'Windowsterminal', 'an optional tech label', 'an optional description')
@enduml
```

