# Pytest


```text
simpleicons-7/P/Pytest
```

```text
include('simpleicons-7/P/Pytest')
```



| Illustration | Pytest |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Pytest.png) | ![illustration for Pytest](../../simpleicons-7/P/Pytest.Local.png) |




## Pytest

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Pytest
include('simpleicons-7/P/Pytest')

' renders the element
Pytest('Pytest', 'Pytest', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Pytest
include('simpleicons-7/P/Pytest')

' renders the element
Pytest('Pytest', 'Pytest', 'an optional tech label', 'an optional description')
@enduml
```

