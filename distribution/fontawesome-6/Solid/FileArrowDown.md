# FileArrowDown


```text
fontawesome-6/Solid/FileArrowDown
```

```text
include('fontawesome-6/Solid/FileArrowDown')
```



| Illustration | FileArrowDown |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/FileArrowDown.png) | ![illustration for FileArrowDown](../../fontawesome-6/Solid/FileArrowDown.Local.png) |




## FileArrowDown

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element FileArrowDown
include('fontawesome-6/Solid/FileArrowDown')

' renders the element
FileArrowDown('FileArrowDown', 'File Arrow Down', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element FileArrowDown
include('fontawesome-6/Solid/FileArrowDown')

' renders the element
FileArrowDown('FileArrowDown', 'File Arrow Down', 'an optional tech label', 'an optional description')
@enduml
```

