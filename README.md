# joi-e164

Joi extension to validate E.164 numbering format.

## Installation

```
npm install @puzzleframework/joi-e164 --save
```

## Usage

```js
const JoiBase = require('joi')
const JoiE164 = require('@puzzleframework/joi-e164')

const Joi = JoiBase.extend(JoiE164)

const result = Joi.e164().validate('+14155552671')
```