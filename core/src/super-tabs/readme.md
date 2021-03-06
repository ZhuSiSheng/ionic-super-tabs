# super-tabs



<!-- Auto Generated Below -->


## Properties

| Property         | Attribute          | Description                     | Type                           | Default     |
| ---------------- | ------------------ | ------------------------------- | ------------------------------ | ----------- |
| `activeTabIndex` | `active-tab-index` | Initial active tab index        | `number`                       | `0`         |
| `config`         | --                 | Global Super Tabs configuration | `SuperTabsConfig \| undefined` | `undefined` |


## Events

| Event       | Description | Type                                     |
| ----------- | ----------- | ---------------------------------------- |
| `tabChange` |             | `CustomEvent<SuperTabChangeEventDetail>` |


## Methods

### `selectTab(index: number, animate?: boolean) => void`

Set the selected tab.
This will move the container and the toolbar to the selected tab.

#### Parameters

| Name      | Type      | Description                                |
| --------- | --------- | ------------------------------------------ |
| `index`   | `number`  | the index of the tab you want to select    |
| `animate` | `boolean` | whether you want to animate the transition |

#### Returns

Type: `void`



### `setConfig(config: SuperTabsConfig) => void`



#### Parameters

| Name     | Type              | Description |
| -------- | ----------------- | ----------- |
| `config` | `SuperTabsConfig` |             |

#### Returns

Type: `void`




----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
