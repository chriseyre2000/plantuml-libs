# Hellyhansen


```text
simpleicons-7/H/Hellyhansen
```

```text
include('simpleicons-7/H/Hellyhansen')
```



| Illustration | Hellyhansen |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/H/Hellyhansen.png) | ![illustration for Hellyhansen](../../simpleicons-7/H/Hellyhansen.Local.png) |




## Hellyhansen

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Hellyhansen
include('simpleicons-7/H/Hellyhansen')

' renders the element
Hellyhansen('Hellyhansen', 'Hellyhansen', 'an optional tech label', 'an optional description')
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
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Hellyhansen
include('simpleicons-7/H/Hellyhansen')

' renders the element
Hellyhansen('Hellyhansen', 'Hellyhansen', 'an optional tech label', 'an optional description')
@enduml
```

