# Verizon


```text
simpleicons-7/V/Verizon
```

```text
include('simpleicons-7/V/Verizon')
```



| Illustration | Verizon |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/V/Verizon.png) | ![illustration for Verizon](../../simpleicons-7/V/Verizon.Local.png) |




## Verizon

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Verizon
include('simpleicons-7/V/Verizon')

' renders the element
Verizon('Verizon', 'Verizon', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Verizon
include('simpleicons-7/V/Verizon')

' renders the element
Verizon('Verizon', 'Verizon', 'an optional tech label', 'an optional description')
@enduml
```

