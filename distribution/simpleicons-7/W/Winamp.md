# Winamp


```text
simpleicons-7/W/Winamp
```

```text
include('simpleicons-7/W/Winamp')
```



| Illustration | Winamp |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/W/Winamp.png) | ![illustration for Winamp](../../simpleicons-7/W/Winamp.Local.png) |




## Winamp

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Winamp
include('simpleicons-7/W/Winamp')

' renders the element
Winamp('Winamp', 'Winamp', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Winamp
include('simpleicons-7/W/Winamp')

' renders the element
Winamp('Winamp', 'Winamp', 'an optional tech label', 'an optional description')
@enduml
```

