# Ufc


```text
simpleicons-7/U/Ufc
```

```text
include('simpleicons-7/U/Ufc')
```



| Illustration | Ufc |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/U/Ufc.png) | ![illustration for Ufc](../../simpleicons-7/U/Ufc.Local.png) |




## Ufc

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Ufc
include('simpleicons-7/U/Ufc')

' renders the element
Ufc('Ufc', 'Ufc', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Ufc
include('simpleicons-7/U/Ufc')

' renders the element
Ufc('Ufc', 'Ufc', 'an optional tech label', 'an optional description')
@enduml
```

