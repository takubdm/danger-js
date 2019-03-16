[danger-js](../README.md) > ["serviceWorker"](../modules/_serviceworker_.md)

# External module: "serviceWorker"

## Index

### Type aliases

* [Config](_serviceworker_.md#config)

### Variables

* [isLocalhost](_serviceworker_.md#islocalhost)

### Functions

* [checkValidServiceWorker](_serviceworker_.md#checkvalidserviceworker)
* [register](_serviceworker_.md#register)
* [registerValidSW](_serviceworker_.md#registervalidsw)
* [unregister](_serviceworker_.md#unregister)

---

## Type aliases

<a id="config"></a>

###  Config

**Ƭ Config**: *`object`*

*Defined in serviceWorker.ts:23*

#### Type declaration

`Optional`  onSuccess: `undefined` \| `function`

`Optional`  onUpdate: `undefined` \| `function`

___

## Variables

<a id="islocalhost"></a>

### `<Const>` isLocalhost

**● isLocalhost**: *`boolean`* =  Boolean(
  window.location.hostname === 'localhost' ||
    // [::1] is the IPv6 localhost address.
    window.location.hostname === '[::1]' ||
    // 127.0.0.1/8 is considered localhost for IPv4.
    window.location.hostname.match(
      /^127(?:\.(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)){3}$/
    )
)

*Defined in serviceWorker.ts:13*

___

## Functions

<a id="checkvalidserviceworker"></a>

###  checkValidServiceWorker

▸ **checkValidServiceWorker**(swUrl: *`string`*, config?: *[Config](_serviceworker_.md#config)*): `void`

*Defined in serviceWorker.ts:109*

**Parameters:**

| Name | Type |
| ------ | ------ |
| swUrl | `string` |
| `Optional` config | [Config](_serviceworker_.md#config) |

**Returns:** `void`

___
<a id="register"></a>

###  register

▸ **register**(config?: *[Config](_serviceworker_.md#config)*): `void`

*Defined in serviceWorker.ts:28*

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` config | [Config](_serviceworker_.md#config) |

**Returns:** `void`

___
<a id="registervalidsw"></a>

###  registerValidSW

▸ **registerValidSW**(swUrl: *`string`*, config?: *[Config](_serviceworker_.md#config)*): `void`

*Defined in serviceWorker.ts:65*

**Parameters:**

| Name | Type |
| ------ | ------ |
| swUrl | `string` |
| `Optional` config | [Config](_serviceworker_.md#config) |

**Returns:** `void`

___
<a id="unregister"></a>

###  unregister

▸ **unregister**(): `void`

*Defined in serviceWorker.ts:137*

**Returns:** `void`

___

