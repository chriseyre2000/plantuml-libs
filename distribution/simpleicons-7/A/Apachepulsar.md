# Apachepulsar


```text
simpleicons-7/A/Apachepulsar
```

```text
include('simpleicons-7/A/Apachepulsar')
```



| Illustration | Apachepulsar |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Apachepulsar.png) | ![illustration for Apachepulsar](../../simpleicons-7/A/Apachepulsar.Local.png) |




## Apachepulsar

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Apachepulsar
include('simpleicons-7/A/Apachepulsar')

' renders the element
Apachepulsar('Apachepulsar', 'Apachepulsar', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Apachepulsar
include('simpleicons-7/A/Apachepulsar')

' renders the element
Apachepulsar('Apachepulsar', 'Apachepulsar', 'an optional tech label', 'an optional description')
@enduml
```

