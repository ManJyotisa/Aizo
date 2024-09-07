```markdown
# Aizo Module

Aizo Module adalah sebuah package Node.js yang dikembangkan untuk mempermudah integrasi dengan berbagai fitur sederhana dalam pengembangan aplikasi. Module ini memberikan berbagai utility yang sering digunakan dalam pengembangan backend maupun frontend, cocok untuk siapa saja yang ingin menggunakan module tanpa biaya.
```

## Thanks To

- Hercai
- Prodia.js
- @google/generative-ai
- g4f

## Features

- Mudah diintegrasikan dengan proyek berbasis Node.js
- Mendukung CommonJS dan ES Modules (ESM)
- Sederhana dan ringan
- CWaifu(TEXT)
- CAnime(TEXT)
- Gpt4(TEXT)
- Gemini(TEXT, LINK IMAGE)
- Question(TEXT, MODEL)
- Draw(TEXT, MODEL)
- DrawV1(TEXT, MODEL)
- DrawV2(TEXT, MODEL)

## Installation
```bash
npm install aizo-module
```

## Usages CJS
```javascript
const { Aizo } = require('aizo-module');

(async () => {
const data = new Aizo();
const result = data.Gemini('Halo');
console.log(result);
})()
```

### Usages ESM
```javascript
import { Aizo } from 'aizo-module';

(async () => {
const data = new Aizo();
const result = data.Gemini('Halo');
console.log(result);
})()
```

## Get Models
```javascript
import { Aizo } from 'aizo-module';

const data = new Aizo();
const result = data.Draw();
console.log(result);
```

