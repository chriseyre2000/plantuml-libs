# Markdown


```text
simpleicons-7/M/Markdown
```

```text
include('simpleicons-7/M/Markdown')
```



| Illustration | Markdown |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Markdown.png) | ![illustration for Markdown](../../simpleicons-7/M/Markdown.Local.png) |




## Markdown

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Markdown
include('simpleicons-7/M/Markdown')

' renders the element
Markdown('Markdown', 'Markdown', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Markdown
include('simpleicons-7/M/Markdown')

' renders the element
Markdown('Markdown', 'Markdown', 'an optional tech label', 'an optional description')
@enduml
```

