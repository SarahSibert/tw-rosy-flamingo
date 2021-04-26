# Tailwind CSS Rosy Flamingo Palette

This plugin adds the Rosy Flamingo colour palette (from https://www.canva.com/colors/color-palettes/rosy-flamingo/) to the Tailwind colour palette.

## Installation

```bash
yarn add sarahsibert/tw-rosy-flamingo#main
```

**tailwind.config.js**
```javascript
module.exports = {
  plugins: [
      require('tw-rosy-flamingo'),
  ],
};
```

## Usage

```html
<div class="space-y-6">
    <button class="bg-rf-wenge px-4 py-2 rounded text-white">
        Wenge
    </button>
    <button class="bg-rf-spanishGray px-4 py-2 rounded text-white">
        Spanish Gray
    </button>
    <button class="bg-r-champagnePink px-4 py-2 rounded text-white">
        Champagne Pink
    </button>
    <button class="bg-rf-paleChestnut px-4 py-2 rounded text-white">
        Pale Chestnut
    </button>
</div>
```

Will result in something similar to this:

