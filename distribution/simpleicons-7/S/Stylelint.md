# Stylelint


```text
simpleicons-7/S/Stylelint
```

```text
include('simpleicons-7/S/Stylelint')
```



| Illustration | Stylelint |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Stylelint.png) | ![illustration for Stylelint](../../simpleicons-7/S/Stylelint.Local.png) |




## Stylelint

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Stylelint
include('simpleicons-7/S/Stylelint')

' renders the element
Stylelint('Stylelint', 'Stylelint', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Stylelint
include('simpleicons-7/S/Stylelint')

' renders the element
Stylelint('Stylelint', 'Stylelint', 'an optional tech label', 'an optional description')
@enduml
```

