# Bata


```text
simpleicons-7/B/Bata
```

```text
include('simpleicons-7/B/Bata')
```



| Illustration | Bata |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/B/Bata.png) | ![illustration for Bata](../../simpleicons-7/B/Bata.Local.png) |




## Bata

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Bata
include('simpleicons-7/B/Bata')

' renders the element
Bata('Bata', 'Bata', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bata
include('simpleicons-7/B/Bata')

' renders the element
Bata('Bata', 'Bata', 'an optional tech label', 'an optional description')
@enduml
```

