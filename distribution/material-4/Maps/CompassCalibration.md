# CompassCalibration


```text
material-4/Maps/CompassCalibration
```

```text
include('material-4/Maps/CompassCalibration')
```



| Illustration | CompassCalibration |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Maps/CompassCalibration.png) | ![illustration for CompassCalibration](../../material-4/Maps/CompassCalibration.Local.png) |




## CompassCalibration

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element CompassCalibration
include('material-4/Maps/CompassCalibration')

' renders the element
CompassCalibration('CompassCalibration', 'Compass Calibration', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element CompassCalibration
include('material-4/Maps/CompassCalibration')

' renders the element
CompassCalibration('CompassCalibration', 'Compass Calibration', 'an optional tech label', 'an optional description')
@enduml
```

