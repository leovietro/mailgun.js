[mailgun.js](../README.md) / [Exports](../modules.md) / [Interfaces](../modules/Interfaces.md) / IMailgunClient

# Interface: IMailgunClient

[Interfaces](../modules/Interfaces.md).IMailgunClient

## Table of contents

### Properties

- [domains](Interfaces.IMailgunClient.md#domains)
- [events](Interfaces.IMailgunClient.md#events)
- [ip\_pools](Interfaces.IMailgunClient.md#ip_pools)
- [ips](Interfaces.IMailgunClient.md#ips)
- [lists](Interfaces.IMailgunClient.md#lists)
- [messages](Interfaces.IMailgunClient.md#messages)
- [routes](Interfaces.IMailgunClient.md#routes)
- [stats](Interfaces.IMailgunClient.md#stats)
- [subaccounts](Interfaces.IMailgunClient.md#subaccounts)
- [suppressions](Interfaces.IMailgunClient.md#suppressions)
- [validate](Interfaces.IMailgunClient.md#validate)
- [webhooks](Interfaces.IMailgunClient.md#webhooks)

### Methods

- [resetSubaccount](Interfaces.IMailgunClient.md#resetsubaccount)
- [setSubaccount](Interfaces.IMailgunClient.md#setsubaccount)

## Properties

### domains

• **domains**: [`IDomainsClient`](Interfaces.IDomainsClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:16](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L16)

___

### events

• **events**: [`IEventClient`](Interfaces.IEventClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:18](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L18)

___

### ip\_pools

• **ip\_pools**: [`IIPPoolsClient`](Interfaces.IIPPoolsClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:25](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L25)

___

### ips

• **ips**: [`IIPsClient`](Interfaces.IIPsClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:24](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L24)

___

### lists

• **lists**: [`IMailingListsClient`](Interfaces.IMailingListsClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:26](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L26)

___

### messages

• **messages**: [`IMessagesClient`](Interfaces.IMessagesClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:21](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L21)

___

### routes

• **routes**: [`IRoutesClient`](Interfaces.IRoutesClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:22](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L22)

___

### stats

• **stats**: [`IStatsClient`](Interfaces.IStatsClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:19](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L19)

___

### subaccounts

• **subaccounts**: [`ISubaccountsClient`](Interfaces.ISubaccountsClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:27](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L27)

___

### suppressions

• **suppressions**: [`ISuppressionClient`](Interfaces.ISuppressionClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:20](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L20)

___

### validate

• **validate**: [`IValidationClient`](Interfaces.IValidationClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:23](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L23)

___

### webhooks

• **webhooks**: [`IWebHooksClient`](Interfaces.IWebHooksClient.md)

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:17](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L17)

## Methods

### resetSubaccount

▸ **resetSubaccount**(): `void`

#### Returns

`void`

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:29](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L29)

___

### setSubaccount

▸ **setSubaccount**(`subaccountId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `subaccountId` | `string` |

#### Returns

`void`

#### Defined in

[Interfaces/MailgunClient/IMailgunClient.ts:28](https://github.com/mailgun/mailgun.js/blob/1615be3/lib/Interfaces/MailgunClient/IMailgunClient.ts#L28)
