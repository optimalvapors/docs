---
Order: 200
xref: move-ccmdeploymenttoready
Title: Move-CCMDeploymentToReady
Description: Information about the Move-CCMDeploymentToReady function
RedirectFrom: docs/move-ccmdeployment-to-ready
---

# Move-CCMDeploymentToReady

<!-- This documentation is automatically generated from /Move-CCMDeploymentToReady.ps1 using GenerateDocs.ps1. Contributions are welcome at the original location(s). -->

Moves a  deployment to Ready state

## Syntax

~~~powershell
Move-CCMDeploymentToReady `
  -Deployment <String> [<CommonParameters>]
~~~

## Description

Moves a Deployment to the Ready state so it can start


## Aliases

None

## Examples

 **EXAMPLE 1**

~~~powershell
Move-CCMDeploymentToReady -Deployment 'Upgrade Outdated VLC'

~~~

**EXAMPLE 2**

~~~powershell
Move-CCMDeploymenttoReady -Deployment 'Complex Deployment'

~~~

## Inputs

None

## Outputs

None

## Parameters

###  -Deployment &lt;String&gt;
The deployment  to  move

Property               | Value
---------------------- | -----
Aliases                |
Required?              | true
Position?              | 1
Default Value          |
Accept Pipeline Input? | false

### &lt;CommonParameters&gt;

This cmdlet supports the common parameters: -Verbose, -Debug, -ErrorAction, -ErrorVariable, -OutBuffer, and -OutVariable. For more information, see `about_CommonParameters` https://go.microsoft.com/fwlink/p/?LinkID=113216 .



[Function Reference](xref:chococcm-functions)

> :memo: **NOTE** This documentation has been automatically generated from `Import-Module "ChocoCCM" -Force; Get-Help Move-CCMDeploymentToReady -Full`.
