# Number Utilities (Persian / English)

A small set of helper functions for **converting between Persian and English digits** and **formatting numbers with thousand separators** in JavaScript projects.

## ✨ Features

* Convert English digits to Persian
* Convert Persian digits to English
* Format numbers with commas and return Persian digits

---

## 📦 Functions

### `e2p`

Converts English digits to Persian digits.

```js
e2p("12345");
// Output: "۱۲۳۴۵"
```

---

### `p2e`

Converts Persian digits to English digits.

```js
p2e("۱۲۳۴۵");
// Output: "12345"
```

---

### `sp`

Adds thousand separators (`,`) to a number and converts the result to Persian digits.

```js
sp(1234567);
// Output: "۱,۲۳۴,۵۶۷"
```

---

## 🧩 Usage

```js
import { e2p, p2e, sp } from "@/utils/number";
```

---

## 📌 Use Cases

* Displaying prices in Persian format
* Handling numeric form inputs
* Persian-language web applications
* Compatible with React and Next.js projects
