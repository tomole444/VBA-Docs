---
title: Control.Application property (Access)
keywords: vbaac10.chm10132
f1_keywords:
- vbaac10.chm10132
ms.prod: access
api_name:
- Access.Control.Application
ms.assetid: b46574ca-6159-c34a-befd-7d390bdc39f9
ms.date: 03/06/2019
ms.localizationpriority: medium
---


# Control.Application property (Access)

Use the **Application** property to access the active Microsoft Access **[Application](Access.Application.md)** object and its related properties. Read-only **Application** object.


## Syntax

_expression_.**Application**

_expression_ A variable that represents a **[Control](Access.Control.md)** object.


## Remarks

The **Application** property is set by Microsoft Access and is read-only in all views.

Each Microsoft Access object has an **Application** property that returns the current **Application** object. Use this property to access any of the object's properties. For example, you could refer to the menu bar for the **Application** object from the current form by using the following syntax.

```vb
Me.Application.MenuBar 

```



[!include[Support and feedback](~/includes/feedback-boilerplate.md)]