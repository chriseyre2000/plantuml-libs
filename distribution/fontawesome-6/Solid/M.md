# M


```text
fontawesome-6/Solid/M
```

```text
include('fontawesome-6/Solid/M')
```



| Illustration | M |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/M.png) | ![illustration for M](../../fontawesome-6/Solid/M.Local.png) |




## M

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element M
include('fontawesome-6/Solid/M')

' renders the element
M('M', 'M', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element M
include('fontawesome-6/Solid/M')

' renders the element
M('M', 'M', 'an optional tech label', 'an optional description')
@enduml
```

