# Bigcartel


```text
simpleicons-7/B/Bigcartel
```

```text
include('simpleicons-7/B/Bigcartel')
```



| Illustration | Bigcartel |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/B/Bigcartel.png) | ![illustration for Bigcartel](../../simpleicons-7/B/Bigcartel.Local.png) |




## Bigcartel

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Bigcartel
include('simpleicons-7/B/Bigcartel')

' renders the element
Bigcartel('Bigcartel', 'Bigcartel', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Bigcartel
include('simpleicons-7/B/Bigcartel')

' renders the element
Bigcartel('Bigcartel', 'Bigcartel', 'an optional tech label', 'an optional description')
@enduml
```

