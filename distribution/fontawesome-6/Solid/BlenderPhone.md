# BlenderPhone


```text
fontawesome-6/Solid/BlenderPhone
```

```text
include('fontawesome-6/Solid/BlenderPhone')
```



| Illustration | BlenderPhone |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/BlenderPhone.png) | ![illustration for BlenderPhone](../../fontawesome-6/Solid/BlenderPhone.Local.png) |




## BlenderPhone

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element BlenderPhone
include('fontawesome-6/Solid/BlenderPhone')

' renders the element
BlenderPhone('BlenderPhone', 'Blender Phone', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element BlenderPhone
include('fontawesome-6/Solid/BlenderPhone')

' renders the element
BlenderPhone('BlenderPhone', 'Blender Phone', 'an optional tech label', 'an optional description')
@enduml
```

