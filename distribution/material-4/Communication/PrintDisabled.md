# PrintDisabled


```text
material-4/Communication/PrintDisabled
```

```text
include('material-4/Communication/PrintDisabled')
```



| Illustration | PrintDisabled |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/PrintDisabled.png) | ![illustration for PrintDisabled](../../material-4/Communication/PrintDisabled.Local.png) |




## PrintDisabled

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PrintDisabled
include('material-4/Communication/PrintDisabled')

' renders the element
PrintDisabled('PrintDisabled', 'Print Disabled', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PrintDisabled
include('material-4/Communication/PrintDisabled')

' renders the element
PrintDisabled('PrintDisabled', 'Print Disabled', 'an optional tech label', 'an optional description')
@enduml
```

