# Pytorchlightning


```text
simpleicons-7/P/Pytorchlightning
```

```text
include('simpleicons-7/P/Pytorchlightning')
```



| Illustration | Pytorchlightning |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Pytorchlightning.png) | ![illustration for Pytorchlightning](../../simpleicons-7/P/Pytorchlightning.Local.png) |




## Pytorchlightning

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Pytorchlightning
include('simpleicons-7/P/Pytorchlightning')

' renders the element
Pytorchlightning('Pytorchlightning', 'Pytorchlightning', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pytorchlightning
include('simpleicons-7/P/Pytorchlightning')

' renders the element
Pytorchlightning('Pytorchlightning', 'Pytorchlightning', 'an optional tech label', 'an optional description')
@enduml
```

