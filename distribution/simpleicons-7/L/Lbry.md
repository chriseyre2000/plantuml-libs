# Lbry


```text
simpleicons-7/L/Lbry
```

```text
include('simpleicons-7/L/Lbry')
```



| Illustration | Lbry |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/L/Lbry.png) | ![illustration for Lbry](../../simpleicons-7/L/Lbry.Local.png) |




## Lbry

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Lbry
include('simpleicons-7/L/Lbry')

' renders the element
Lbry('Lbry', 'Lbry', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Lbry
include('simpleicons-7/L/Lbry')

' renders the element
Lbry('Lbry', 'Lbry', 'an optional tech label', 'an optional description')
@enduml
```

