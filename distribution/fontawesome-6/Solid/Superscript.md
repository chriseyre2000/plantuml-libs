# Superscript


```text
fontawesome-6/Solid/Superscript
```

```text
include('fontawesome-6/Solid/Superscript')
```



| Illustration | Superscript |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Superscript.png) | ![illustration for Superscript](../../fontawesome-6/Solid/Superscript.Local.png) |




## Superscript

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Superscript
include('fontawesome-6/Solid/Superscript')

' renders the element
Superscript('Superscript', 'Superscript', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Superscript
include('fontawesome-6/Solid/Superscript')

' renders the element
Superscript('Superscript', 'Superscript', 'an optional tech label', 'an optional description')
@enduml
```

