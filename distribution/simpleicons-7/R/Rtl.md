# Rtl


```text
simpleicons-7/R/Rtl
```

```text
include('simpleicons-7/R/Rtl')
```



| Illustration | Rtl |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/R/Rtl.png) | ![illustration for Rtl](../../simpleicons-7/R/Rtl.Local.png) |




## Rtl

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Rtl
include('simpleicons-7/R/Rtl')

' renders the element
Rtl('Rtl', 'Rtl', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Rtl
include('simpleicons-7/R/Rtl')

' renders the element
Rtl('Rtl', 'Rtl', 'an optional tech label', 'an optional description')
@enduml
```

