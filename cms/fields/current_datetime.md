---
title: Current datetime
description: Field to store the current date time
---

The field of type `current_datetime` is very similar to
[datetime](./datetime.md) with the difference of the value is updated
automatically every time the document is saved. It's useful to store the last
modification time of a post or article.

## Example

```ts
{
  name: "last_modified",
  type: "current_datetime",
}
```

## Available options

This field only has
[the common options](../configuration/fields.md#common-field-options).