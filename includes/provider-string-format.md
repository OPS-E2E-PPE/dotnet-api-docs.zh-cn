---
ms.openlocfilehash: b8db885234c59f24a88e4117c9c9181004b20bcb
ms.sourcegitcommit: 1bb00d2f4343e73ae8d58668f02297a3cf10a4c1
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/15/2019
ms.locfileid: "63870976"
---
 
但是，在调用 String.Format 方法时，不需要关注需要调用的特定重载  。 相反，可以使用提供区分区域性或自定义格式设置的对象和包含一个或多个格式项的[复合格式字符串](~/docs/standard/base-types/composite-formatting.md)来调用此方法。 为每个格式项分配一个数字索引；第一个索引从 0 开始。 除了初始字符串，方法调用拥有的额外参数数应该与其拥有的索引值数相同。 例如，格式项有 0 和 1 两个索引的字符串应该有 2 个参数；索引为 0 到 5 的字符串应该有 6 个参数。 然后，你的语言编译器将会将方法调用解析为 String.Format 方法的特定重载  。   

有关使用 String.Format 方法的详细文档，请参阅 [String.Format 方法入门](#Starting)和[我调用哪个方法？](#FTaskList)  。   
