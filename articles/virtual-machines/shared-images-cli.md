---
title: Azure CLI を使用して共有イメージ ギャラリーを作成する
description: この記事では、Azure CLI を使用して Azure で VM の共有イメージを作成する方法について説明します。
author: cynthn
ms.service: virtual-machines
ms.subservice: imaging
ms.topic: how-to
ms.workload: infrastructure
ms.date: 05/04/2020
ms.author: cynthn
ms.reviewer: akjosh
ms.openlocfilehash: d64b5f94dae7ad0213fa231b5603064ad3647da1
ms.sourcegitcommit: e0330ef620103256d39ca1426f09dd5bb39cd075
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2020
ms.locfileid: "82793871"
---
# <a name="create-a-shared-image-gallery-with-the-azure-cli"></a>Azure CLI を使用して共有イメージ ギャラリーを作成する

[共有イメージ ギャラリー](./linux/shared-image-galleries.md)により、組織全体でのカスタム イメージの共有が簡素化されます。 カスタム イメージは Marketplace のイメージに似ていますが、カスタム イメージは自分で作成します。 カスタム イメージは、アプリケーションのプリロード、アプリケーションの構成、その他の OS 構成などの構成のブートストラップを実行するために使用できます。 

共有イメージ ギャラリーを使用すると、カスタム VM イメージを他のユーザーと共有できます。 どのイメージを共有するか、どのリージョンでそのイメージを使用できるようにするか、および、だれと共有するかを選択することができます。 

[!INCLUDE [virtual-machines-common-shared-images-cli](../../includes/virtual-machines-common-shared-images-cli.md)]


## <a name="next-steps"></a>次のステップ

Azure CLI を使用して、[VM](image-version-vm-cli.md) または[マネージド イメージ](image-version-managed-image-cli.md)からイメージ バージョンを作成します。

共有イメージ ギャラリーの詳細については、[概要](./linux/shared-image-galleries.md)のページをご覧ください。 問題が生じた場合は、「[共有イメージ ギャラリーのトラブルシューティング](troubleshooting-shared-images.md)」を参照してください。
