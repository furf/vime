---
title: Lite Player
sidebar_label: Install
---

[![version-badge]][package]
[![size-badge]][size]
[![license-badge]][license]
[![github-badge]][github]
[![tweet-badge]][tweet]

The Lite Player is used to embed media content. If you'd like to know what features it includes and how it
compares to other options then see the [getting started](../welcome/getting-started.md) page.

[package]: https://www.npmjs.com/package/@vime-js/lite
[version-badge]: https://img.shields.io/npm/v/@vime-js/lite?style=flat-square
[size]: https://bundlephobia.com/result?p=@vime-js/lite
[size-badge]: https://img.shields.io/bundlephobia/minzip/@vime-js/lite?label=min%2Bgzip&style=flat-square
[license]: https://github.com/vime-js/vime/blob/master/LICENSE
[license-badge]: https://img.shields.io/github/license/vime-js/vime?color=blue&style=flat-square
[tweet]: https://twitter.com/intent/tweet?text=Check%20out%20Vime%20%28https%3A%2F%2Fgithub.com%2Fvime-js%2Fvime%29%2C%20it%20makes%20embedding%20and%20using%20media%20players%20for%20the%20web%20simple.%20It%20supports%20Html5%2C%20YouTube%2C%20Dailymotion%2C%20Vimeo%20and%20more%20to%20come%21
[tweet-badge]: https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fvime-js%2Fvime
[github]: https://github.com/vime-js/vime
[github-badge]: https://img.shields.io/github/stars/vime-js/vime?style=social

## Installation

import Tabs from '@theme/Tabs'
import TabItem from '@theme/TabItem'

<Tabs
  groupId="packageManager"
  defaultValue="npm"
  values={[
  { label: 'NPM', value: 'npm' },
  { label: 'Yarn', value: 'yarn' },
  { label: 'JSDELIVR', value: 'jsdelivr' },
]}>

<TabItem value="npm">

```
npm install @vime-js/lite
```

</TabItem>

<TabItem value="yarn">

```
yarn add @vime-js/lite
```

</TabItem>

<TabItem value="jsdelivr">

```html
<script src="https://cdn.jsdelivr.net/npm/@vime-js/lite"></script>
```

</TabItem>

</Tabs>

The `dist` folder inside the package contains multiple exports:

- `lite.js` is a UMD development build that can be used directly in the browser via the `<script>` tag.
- `lite.esm.js` is intended for use with modern bundlers like [Webpack][webpack] or [Rollup][rollup].
- `lite.min.js` is a UMD production build that can be used directly in the browser via the `<script>` tag.
- `lite.esm.min.js` is an ESM production build that can be used directly in modern browsers via the `<script type="module">` tag.

:::info
* UMD builds are exported under the `Vime` namespace.
* If you're using a bundler then it will automatically pull in the correct files.
* If you're using [svelte-loader][svelte-loader] or [rollup-plugin-svelte][svelte-rollup] then you'll receive the uncompiled components.
:::

[webpack]: https://webpack.js.org
[rollup]: http://rollupjs.org/guide/en
[svelte-loader]: https://github.com/sveltejs/svelte-loader
[svelte-rollup]: https://github.com/sveltejs/rollup-plugin-svelte

## Setup

<Tabs
  groupId="framework"
  defaultValue="js"
  values={[
  { label: 'JavaScript', value: 'js' },
  { label: 'Svelte', value: 'svelte' },
]}>

<TabItem value="js">

```js
import { Player } from '@vime-js/lite';

const target = document.getElementById('player-target');

// Mount
const player = new Player({
  target,
  // If you'd like to initialize any props on setup, you can do so here.
  props: {
  }
});

// ...

// Destroy
player.$destroy();
```

:::info
See the [client-side component API][svelte-client-api] for the complete set of component initialization options.
:::

[svelte-client-api]: https://svelte.dev/docs#Client-side_component_API

</TabItem>

<TabItem value="svelte">

```html
<Player bind:this={player} />

<script>
  import { onMount } from 'svelte';
  import { Player } from '@vime-js/lite';

  let player;

  onMount(() => {
    /**
     * If you need to call any methods, you have access 
     * to the player instance here.
     **/
  });
</script>
```

</TabItem>

</Tabs>

## Where to next?

The [usage](./usage.md) page will guide you on how to get started with any provider, after that go to the 
[API](./api/player.md) page to see what props/methods/events are exposed and how you can interact with them.
