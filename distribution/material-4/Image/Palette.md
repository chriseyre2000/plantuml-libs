# Palette


```text
material-4/Image/Palette
```

```text
include('material-4/Image/Palette')
```



| Illustration | Palette |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Image/Palette.png) | ![illustration for Palette](../../material-4/Image/Palette.Local.png) |




## Palette

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element Palette
include('material-4/Image/Palette')

' renders the element
Palette('Palette', 'Palette', 'an optional tech label', 'an optional description')
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
include('material-4/bootstrap')

' loads the Item which embeds the element Palette
include('material-4/Image/Palette')

' renders the element
Palette('Palette', 'Palette', 'an optional tech label', 'an optional description')
@enduml
```

