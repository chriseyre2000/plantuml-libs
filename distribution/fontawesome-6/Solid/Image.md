# Image


```text
fontawesome-6/Solid/Image
```

```text
include('fontawesome-6/Solid/Image')
```



| Illustration | Image |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Solid/Image.png) | ![illustration for Image](../../fontawesome-6/Solid/Image.Local.png) |




## Image

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element Image
include('fontawesome-6/Solid/Image')

' renders the element
Image('Image', 'Image', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Image
include('fontawesome-6/Solid/Image')

' renders the element
Image('Image', 'Image', 'an optional tech label', 'an optional description')
@enduml
```

