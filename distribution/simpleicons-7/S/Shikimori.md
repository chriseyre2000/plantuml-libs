# Shikimori


```text
simpleicons-7/S/Shikimori
```

```text
include('simpleicons-7/S/Shikimori')
```



| Illustration | Shikimori |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Shikimori.png) | ![illustration for Shikimori](../../simpleicons-7/S/Shikimori.Local.png) |




## Shikimori

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Shikimori
include('simpleicons-7/S/Shikimori')

' renders the element
Shikimori('Shikimori', 'Shikimori', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Shikimori
include('simpleicons-7/S/Shikimori')

' renders the element
Shikimori('Shikimori', 'Shikimori', 'an optional tech label', 'an optional description')
@enduml
```

