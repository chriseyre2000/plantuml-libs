# AwsCloudFormationTemplate


```text
aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate
```

```text
include('aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate')
```



| Illustration | AwsCloudFormationTemplate | AwsCloudFormationTemplateCard | AwsCloudFormationTemplateGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate.png) | ![illustration for AwsCloudFormationTemplate](../../../aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate.Local.png) | ![illustration for AwsCloudFormationTemplateCard](../../../aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplateCard.Local.png) | ![illustration for AwsCloudFormationTemplateGroup](../../../aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplateGroup.Local.png) |




## AwsCloudFormationTemplate

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsCloudFormationTemplate
include('aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate')

' renders the element
AwsCloudFormationTemplate('AwsCloudFormationTemplate', 'Aws Cloud Formation Template', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element AwsCloudFormationTemplate
include('aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate')

' renders the element
AwsCloudFormationTemplate('AwsCloudFormationTemplate', 'Aws Cloud Formation Template', 'an optional tech label', 'an optional description')
@enduml
```

## AwsCloudFormationTemplateCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsCloudFormationTemplateCard
include('aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate')

' renders the element
AwsCloudFormationTemplateCard('AwsCloudFormationTemplateCard', 'Aws Cloud Formation Template Card', 'an optional description')
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

' loads the Item which embeds the element AwsCloudFormationTemplateCard
include('aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate')

' renders the element
AwsCloudFormationTemplateCard('AwsCloudFormationTemplateCard', 'Aws Cloud Formation Template Card', 'an optional description')
@enduml
```

## AwsCloudFormationTemplateGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q2-2022/bootstrap')

' loads the Item which embeds the element AwsCloudFormationTemplateGroup
include('aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate')

' renders the element
AwsCloudFormationTemplateGroup('AwsCloudFormationTemplateGroup', 'Aws Cloud Formation Template Group', 'an optional tech label') {
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

' loads the Item which embeds the element AwsCloudFormationTemplateGroup
include('aws-q2-2022/Resource/ManagementGovernance/AwsCloudFormationTemplate')

' renders the element
AwsCloudFormationTemplateGroup('AwsCloudFormationTemplateGroup', 'Aws Cloud Formation Template Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

