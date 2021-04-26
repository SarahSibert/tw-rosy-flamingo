
# Tailwind CSS Rosy Flamingo Palette

This plugin adds the Rosy Flamingo colour palette (from https://www.canva.com/colors/color-palettes/rosy-flamingo/) to the Tailwind colour palette.

## Installation

```bash
npm install sarahsibert/tw-rosy-flamingo
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
      <button class="bg-rf-champagnePink px-4 py-2 rounded text-rf-wenge">
          Champagne Pink
      </button>
      <button class="bg-rf-paleChestnut px-4 py-2 rounded text-rf-wenge">
          Pale Chestnut
      </button>
  </div>
```

Will result in something similar to this:


<img width="502" alt="rosyFlamingo" src="https://user-images.githubusercontent.com/38976391/116097553-27592b00-a6a2-11eb-98c5-3946b6a41918.png">


