---
title: StylePropertyMap.clear()
slug: Web/API/StylePropertyMap/clear
page-type: web-api-instance-method
status:
  - experimental
browser-compat: api.StylePropertyMap.clear
---

{{APIRef("CSS Typed Object Model API")}}{{SeeCompatTable}}

The **`clear()`** method of the {{domxref("StylePropertyMap")}}
interface removes all declarations in the `StylePropertyMap`.

## Syntax

```js-nolint
clear()
```

### Parameters

None.

### Return value

None ({{jsxref("undefined")}}).

## Examples

The following example removes all styles within the elements [style attribute](/en-US/docs/Web/HTML/Global_attributes/style).

```js
// get the button element
const buttonEl = document.querySelector(".example");

// remove all styles from the style attribute
buttonEl.attributeStyleMap.clear();
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
