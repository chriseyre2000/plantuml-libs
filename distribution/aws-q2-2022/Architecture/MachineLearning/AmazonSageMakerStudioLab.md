# AmazonSageMakerStudioLab


```text
aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab
```

```text
include('aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab')
```



| Illustration | AmazonSageMakerStudioLab | AmazonSageMakerStudioLabCard | AmazonSageMakerStudioLabGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab.png) | ![illustration for AmazonSageMakerStudioLab](../../../aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab.Local.png) | ![illustration for AmazonSageMakerStudioLabCard](../../../aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLabCard.Local.png) | ![illustration for AmazonSageMakerStudioLabGroup](../../../aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLabGroup.Local.png) |




## AmazonSageMakerStudioLab

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonSageMakerStudioLab
include('aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab')

' renders the element
AmazonSageMakerStudioLab('AmazonSageMakerStudioLab', 'Amazon Sage Maker Studio Lab', 'an optional tech label', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonSageMakerStudioLab
include('aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab')

' renders the element
AmazonSageMakerStudioLab('AmazonSageMakerStudioLab', 'Amazon Sage Maker Studio Lab', 'an optional tech label', 'an optional description')
@enduml
```

## AmazonSageMakerStudioLabCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonSageMakerStudioLabCard
include('aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab')

' renders the element
AmazonSageMakerStudioLabCard('AmazonSageMakerStudioLabCard', 'Amazon Sage Maker Studio Lab Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonSageMakerStudioLabCard
include('aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab')

' renders the element
AmazonSageMakerStudioLabCard('AmazonSageMakerStudioLabCard', 'Amazon Sage Maker Studio Lab Card', 'an optional description')
@enduml
```

## AmazonSageMakerStudioLabGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonSageMakerStudioLabGroup
include('aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab')

' renders the element
AmazonSageMakerStudioLabGroup('AmazonSageMakerStudioLabGroup', 'Amazon Sage Maker Studio Lab Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AmazonSageMakerStudioLabGroup
include('aws-q2-2022/Architecture/MachineLearning/AmazonSageMakerStudioLab')

' renders the element
AmazonSageMakerStudioLabGroup('AmazonSageMakerStudioLabGroup', 'Amazon Sage Maker Studio Lab Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

