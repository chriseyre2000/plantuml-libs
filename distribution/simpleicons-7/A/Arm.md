# Arm


```text
simpleicons-7/A/Arm
```

```text
include('simpleicons-7/A/Arm')
```



| Illustration | Arm |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Arm.png) | ![illustration for Arm](../../simpleicons-7/A/Arm.Local.png) |




## Arm

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Arm
include('simpleicons-7/A/Arm')

' renders the element
Arm('Arm', 'Arm', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Arm
include('simpleicons-7/A/Arm')

' renders the element
Arm('Arm', 'Arm', 'an optional tech label', 'an optional description')
@enduml
```

