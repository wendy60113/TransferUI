# tag_transfer

Hope everyone enjoys it!

> This example depends on BootstrapVue. Before using this example, please install BootstrapVue.

## Demo

[Demo Website](https://wendy60113.github.io/Transfer_UI/)

## Installation

```sh
npm i tag_transfer
```

```sh
npm install vue bootstrap bootstrap-vue
```

## Usage

#### Import BootstrapVue

```sh
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
Vue.use(BootstrapVue)
Vue.use(IconsPlugin)
```

#### Import Component

```sh
import vueTransfer from 'tag_transfer'
import 'tag_transfer/dist/vue-TransferApp.css';
Vue.component('vueTransfer', vueTransfer);
```

#### Set Style

You can set the container with div to control the component's size. Here is an example:

```sh
<template>
    <div class="container">
      <vueTransfer/>
    </div>
</template>
<style>
    .container{
        width: 700px;
        height: 400px;
    }
</style>
```
