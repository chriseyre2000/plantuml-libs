# Subaru


```text
simpleicons-7/S/Subaru
```

```text
include('simpleicons-7/S/Subaru')
```



| Illustration | Subaru |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Subaru.png) | ![illustration for Subaru](../../simpleicons-7/S/Subaru.Local.png) |




## Subaru

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Subaru
include('simpleicons-7/S/Subaru')

' renders the element
Subaru('Subaru', 'Subaru', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Subaru
include('simpleicons-7/S/Subaru')

' renders the element
Subaru('Subaru', 'Subaru', 'an optional tech label', 'an optional description')
@enduml
```

