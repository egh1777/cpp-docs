---
title: "Resource Compiler Fatal Error RC1020 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "error-reference"
f1_keywords: ["RC1020"]
dev_langs: ["C++"]
helpviewer_keywords: ["RC1020"]
ms.assetid: 3e073ebf-9136-4bf8-ac6a-3c642ed64594
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
ms.workload: ["cplusplus"]
---
# Resource Compiler Fatal Error RC1020
unexpected '#endif'  
  
 An `#endif` directive appeared without a matching `#if`, **#ifdef**, or **#ifndef** directive.  
  
 Make sure that there is a matching `#endif` for each `#if`, **#ifdef**, and **#ifndef** statement.