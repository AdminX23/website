---
title: Flexvolume
id: flexvolume
date: 2018-06-25
full_link: https://kubernetes.io/docs/concepts/storage/volumes/#flexvolume
short_description: >
    Flexvolume 是创建 out-of-tree 卷插件的一种接口。 {{< glossary_tooltip text="容器存储接口（CSI）" term_id="csi" >}} 是比 Flexvolume 更新的接口，它解决了 Flexvolumes 的一些问题。


aka: 
tags:
- storage 
---

<!--
---
title: Flexvolume
id: flexvolume
date: 2018-06-25
full_link: https://kubernetes.io/docs/concepts/storage/volumes/#flexvolume
short_description: >
    Flexvolume is an interface for creating out-of-tree volume plugins. The {{< glossary_tooltip text="Container Storage Interface" term_id="csi" >}} is a newer interface which addresses several problems with Flexvolumes.


aka: 
tags:
- storage 
---
-->

 Flexvolume 是创建 out-of-tree 卷插件的一种接口。 {{< glossary_tooltip text="容器存储接口（CSI）" term_id="csi" >}} 是比 Flexvolume 更新的接口，它解决了 Flexvolume 的一些问题。

<!--more--> 

<!--
Flexvolumes enable users to write their own drivers and add support for their volumes in Kubernetes. FlexVolume driver binaries and dependencies must be installed on host machines. This requires root access. The Storage SIG suggests implementing a {{< glossary_tooltip text="CSI" term_id="csi" >}} driver if possible since it addresses the limitations with Flexvolumes.
-->

Flexvolume 允许用户编写自己的驱动程序，并在 Kubernetes 中加入对用户自己的数据卷的支持。
FlexVolume 驱动程序的二进制文件和依赖项必须安装在主机上。这需要 root 权限。
如果可能的话，SIG Storage 建议实现 {{< glossary_tooltip text="CSI" term_id="csi" >}} 驱动程序，因为它解决了 Flexvolumes 的限制。

<!--
* [Flexvolume in the Kubernetes documentation](https://kubernetes.io/docs/concepts/storage/volumes/#flexvolume)
* [More information on Flexvolumes](https://github.com/kubernetes/community/blob/master/contributors/devel/flexvolume.md)
* [Volume Plugin FAQ for Storage Vendors](https://github.com/kubernetes/community/blob/master/sig-storage/volume-plugin-faq.md)
-->

* [Kubernetes 文档中的 Flexvolume](https://kubernetes.io/docs/concepts/storage/volumes/#flexvolume)
* [更多关于 Flexvolumes 的信息](https://github.com/kubernetes/community/blob/master/contributors/devel/flexvolume.md)
* [存储供应商的卷插件 FAQ](https://github.com/kubernetes/community/blob/master/sig-storage/volume-plugin-faq.md)