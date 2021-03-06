---
title: "make_unsigned Class | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-standard-libraries"]
ms.tgt_pltfrm: ""
ms.topic: "reference"
f1_keywords: ["type_traits/std::make_unsigned"]
dev_langs: ["C++"]
helpviewer_keywords: ["make_unsigned class", "make_unsigned"]
ms.assetid: 7a6a3c4f-1a4c-47e8-9ee2-ac1f7b669353
caps.latest.revision: 18
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
ms.workload: ["cplusplus"]
---
# make_unsigned Class
Makes type or the smallest unsigned type greater than or equal in size to type.  
  
## Syntax  
  
```
template <class T>
struct make_unsigned;

template <class T>
using make_unsigned_t = typename make_unsigned<T>::type;
```  
  
#### Parameters  
  
|Parameter|Description|  
|---------------|-----------------|  
|`T`|The type to modify.|  
  
## Remarks  
 An instance of the type modifier holds a modified-type that is `T` if `is_unsigned<T>` holds true. Otherwise it is the smallest signed type `ST` for which `sizeof (T) <= sizeof (ST)`.  
  
## Requirements  
 **Header:** \<type_traits>  
  
 **Namespace:** std  
  
## See Also  
 [<type_traits>](../standard-library/type-traits.md)



