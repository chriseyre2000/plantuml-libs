# Sparkasse


```text
simpleicons-7/S/Sparkasse
```

```text
include('simpleicons-7/S/Sparkasse')
```



| Illustration | Sparkasse |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Sparkasse.png) | ![illustration for Sparkasse](../../simpleicons-7/S/Sparkasse.Local.png) |




## Sparkasse

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Sparkasse
include('simpleicons-7/S/Sparkasse')

' renders the element
Sparkasse('Sparkasse', 'Sparkasse', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sparkasse
include('simpleicons-7/S/Sparkasse')

' renders the element
Sparkasse('Sparkasse', 'Sparkasse', 'an optional tech label', 'an optional description')
@enduml
```

