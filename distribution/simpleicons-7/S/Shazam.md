# Shazam


```text
simpleicons-7/S/Shazam
```

```text
include('simpleicons-7/S/Shazam')
```



| Illustration | Shazam |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Shazam.png) | ![illustration for Shazam](../../simpleicons-7/S/Shazam.Local.png) |




## Shazam

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Shazam
include('simpleicons-7/S/Shazam')

' renders the element
Shazam('Shazam', 'Shazam', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Shazam
include('simpleicons-7/S/Shazam')

' renders the element
Shazam('Shazam', 'Shazam', 'an optional tech label', 'an optional description')
@enduml
```

