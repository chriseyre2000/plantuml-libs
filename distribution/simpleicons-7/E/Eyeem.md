# Eyeem


```text
simpleicons-7/E/Eyeem
```

```text
include('simpleicons-7/E/Eyeem')
```



| Illustration | Eyeem |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/E/Eyeem.png) | ![illustration for Eyeem](../../simpleicons-7/E/Eyeem.Local.png) |




## Eyeem

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Eyeem
include('simpleicons-7/E/Eyeem')

' renders the element
Eyeem('Eyeem', 'Eyeem', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Eyeem
include('simpleicons-7/E/Eyeem')

' renders the element
Eyeem('Eyeem', 'Eyeem', 'an optional tech label', 'an optional description')
@enduml
```

