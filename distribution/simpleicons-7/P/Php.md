# Php


```text
simpleicons-7/P/Php
```

```text
include('simpleicons-7/P/Php')
```



| Illustration | Php |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/P/Php.png) | ![illustration for Php](../../simpleicons-7/P/Php.Local.png) |




## Php

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Php
include('simpleicons-7/P/Php')

' renders the element
Php('Php', 'Php', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Php
include('simpleicons-7/P/Php')

' renders the element
Php('Php', 'Php', 'an optional tech label', 'an optional description')
@enduml
```

