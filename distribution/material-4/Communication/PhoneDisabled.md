# PhoneDisabled


```text
material-4/Communication/PhoneDisabled
```

```text
include('material-4/Communication/PhoneDisabled')
```



| Illustration | PhoneDisabled |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Communication/PhoneDisabled.png) | ![illustration for PhoneDisabled](../../material-4/Communication/PhoneDisabled.Local.png) |




## PhoneDisabled

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element PhoneDisabled
include('material-4/Communication/PhoneDisabled')

' renders the element
PhoneDisabled('PhoneDisabled', 'Phone Disabled', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element PhoneDisabled
include('material-4/Communication/PhoneDisabled')

' renders the element
PhoneDisabled('PhoneDisabled', 'Phone Disabled', 'an optional tech label', 'an optional description')
@enduml
```

