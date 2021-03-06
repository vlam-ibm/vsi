---

copyright:
  years: 2018
lastupdated: "2018-10-05"

subcollection: virtual-servers

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}
{:pre: .pre}
{:table: .aria-labeledby="caption"}

# 供应预留容量和实例
{: #provisioning-reserved-capacity-and-instances}

## 开始之前

您可以通过 {{site.data.keyword.cloud}} 目录来供应预留容量和实例。必须先供应预留容量，然后才能供应虚拟服务器实例。

**注**：如果您不是帐户管理员，那么您的用户帐户必须包含**管理预留容量**许可权。帐户管理员可以在控制台中的**门户网站许可权**选项卡中授予用户许可权。有关更新许可权的更多信息，请参阅[管理基础架构访问权](/docs/iam?topic=iam-mngclassicinfra)。

## 登录到 IBM Cloud 目录

使用以下步骤登录到 {{site.data.keyword.cloud_notm}} 目录以开始供应预留容量和实例。

  1. 使用您的唯一凭证来登录到 [{{site.data.keyword.cloud_notm}} 目录 ![外部链接图标](../icons/launch-glyph.svg "外部链接图标")](https://console.bluemix.net/catalog/){: new_window}。

## 供应预留容量

在 {{site.data.keyword.cloud_notm}} 目录中，完成以下步骤来供应预留容量。

  1. 在**计算基础架构**部分中，单击**虚拟服务器**磁贴。
  2. 选择**预留虚拟服务器**选项。
  3. 单击**创建**。
  4. 要创建新的预留容量，请选择**新建容量 +**。在**预留容量**页面中，输入或选择以下信息：

|字段|值|                                                                                                                                                                                                                                                                                                                                 
| ----------------------- | ------------------- |
|名称|需要为预留容量提供名称。|                                                                                                                                                                                                                                                                                                       
|虚拟服务器容量|选择要分配给此预留容量的实例数（限制为 20 个实例）。|                                                                                                                                                                                                                                                
|位置|选择工作负载所需的特定位置。位置由区域组成；每个区域是一个独立的地理区域。**注：**您无法为在此预留容量内供应的每个虚拟服务器实例选择不同的位置。您选择的位置将用于在此预留容量内供应的所有虚拟服务器实例。|
|POD|选择特定于位置的 POD。|
|套餐期限|选择一年或三年合同期限。|                                                                                                                                                                                                                                                                                            
|概要文件|从常用概要文件或 SAN 支持的存储器（均衡、内存或计算）的所有可用 vCPU 和 RAM 组合中进行选择。**注：**不能在分配给此容量的一组虚拟服务器实例内组合使用不同的概要文件大小，也不能在日后对其进行更改。预留的一组虚拟服务器实例的大小必须相同。|
{: caption="表 1. 预留容量供应选项" caption-side="top"}


## 供应预留实例

供应了预留容量后，就可以供应预留虚拟服务器实例了。在合同期限内，可以随时供应预留虚拟服务器实例，因为您的容量是有保证的。要供应预留实例，请完成以下步骤：

1. 在 {{site.data.keyword.cloud_notm}} 目录中，选择**计算基础架构**部分中的**虚拟服务器**磁贴。
2. 选择**预留虚拟服务器**选项。
3. 单击**创建**。
4. 要供应预留虚拟服务器实例，请输入或选择以下信息：

|字段|值|                                                                                                                                                                                                                                                                                                                                 
| ------------------------- | ------------------- |
|名称|需要为预留虚拟服务器实例提供名称。|                                                                                                                                                                                                                                                                                                       
|计费|选择按小时或按月计费。|                                                                                                                                                                                                                                                
|预留容量|选择您的预留容量，或选择**新建容量 +** 以供应更多预留容量。|                                                                                                                                                                                                     
|附加组件|选择其他任何存储器、网络或软件。|                                                                                                                                                                                                                                                                                            
{: caption="表 1. 预留容量供应选项" caption-side="top"}

## 后续步骤

供应了预留虚拟服务器容量和实例后，即可以开始对其进行管理。有关更多信息，请参阅[管理虚拟服务器](/docs/vsi?topic=virtual-servers-managing-virtual-servers)。如果有预留容量和实例方面的问题，请参阅[常见问题：预留容量和实例](/docs/vsi?topic=virtual-servers-faqs-reserved-capacity-and-instances)。
