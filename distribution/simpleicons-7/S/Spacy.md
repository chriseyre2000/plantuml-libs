# Spacy


```text
simpleicons-7/S/Spacy
```

```text
include('simpleicons-7/S/Spacy')
```



| Illustration | Spacy |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Spacy.png) | ![illustration for Spacy](../../simpleicons-7/S/Spacy.Local.png) |




## Spacy

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Spacy
include('simpleicons-7/S/Spacy')

' renders the element
Spacy('Spacy', 'Spacy', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Spacy
include('simpleicons-7/S/Spacy')

' renders the element
Spacy('Spacy', 'Spacy', 'an optional tech label', 'an optional description')
@enduml
```

