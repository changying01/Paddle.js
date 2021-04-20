[中文版](./README_cn.md)

# gesture

gesture is a gesture recognition module, including two models: gesture_detect and gesture_rec.gesture_detect model is used to identify the palm area of the person in the image. gesture_rec model is used to recognize human gesture. The interface provided by the module is simple, users only need to pass in gesture images to get the results.

# Usage

```js

import * as gesture from '@paddlejs-models/gesture';

// Model load
await gesture.load();

// Get the image recognition results. The results include: palm frame coordinates and recognition results
const res = await gesture.classify(img);

```
