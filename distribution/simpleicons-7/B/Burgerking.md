# Burgerking


```text
simpleicons-7/B/Burgerking
```

```text
include('simpleicons-7/B/Burgerking')
```



| Illustration | Burgerking |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/B/Burgerking.png) | ![illustration for Burgerking](../../simpleicons-7/B/Burgerking.Local.png) |




## Burgerking

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Burgerking
include('simpleicons-7/B/Burgerking')

' renders the element
Burgerking('Burgerking', 'Burgerking', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Burgerking
include('simpleicons-7/B/Burgerking')

' renders the element
Burgerking('Burgerking', 'Burgerking', 'an optional tech label', 'an optional description')
@enduml
```

