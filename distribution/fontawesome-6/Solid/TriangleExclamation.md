# TriangleExclamation


```text
fontawesome-6/Solid/TriangleExclamation
```

```text
include('fontawesome-6/Solid/TriangleExclamation')
```



| Illustration | TriangleExclamation |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/TriangleExclamation.png) | ![illustration for TriangleExclamation](../../fontawesome-6/Solid/TriangleExclamation.Local.png) |




## TriangleExclamation

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element TriangleExclamation
include('fontawesome-6/Solid/TriangleExclamation')

' renders the element
TriangleExclamation('TriangleExclamation', 'Triangle Exclamation', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element TriangleExclamation
include('fontawesome-6/Solid/TriangleExclamation')

' renders the element
TriangleExclamation('TriangleExclamation', 'Triangle Exclamation', 'an optional tech label', 'an optional description')
@enduml
```

