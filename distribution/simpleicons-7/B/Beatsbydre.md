# Beatsbydre


```text
simpleicons-7/B/Beatsbydre
```

```text
include('simpleicons-7/B/Beatsbydre')
```



| Illustration | Beatsbydre |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/B/Beatsbydre.png) | ![illustration for Beatsbydre](../../simpleicons-7/B/Beatsbydre.Local.png) |




## Beatsbydre

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Beatsbydre
include('simpleicons-7/B/Beatsbydre')

' renders the element
Beatsbydre('Beatsbydre', 'Beatsbydre', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Beatsbydre
include('simpleicons-7/B/Beatsbydre')

' renders the element
Beatsbydre('Beatsbydre', 'Beatsbydre', 'an optional tech label', 'an optional description')
@enduml
```

