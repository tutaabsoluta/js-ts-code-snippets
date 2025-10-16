# JavaScript & QA Automation Snippets

This repository contains **VSCode snippets** to speed up development in JavaScript/TypeScript and testing with frameworks like Jest, Playwright, and Cypress.  

---

## 📦 Import / Export

| Trigger | Snippet | Description |
|---------|---------|-------------|
| `imp` | `import fs from 'fs';` | Imports entire module |
| `imd` | `import { rename } from 'fs';` | Imports only a portion of the module |
| `env` | `export const nameVariable = localVariable;` | Exports a named variable |

---

## 🏗 Class Helpers

| Trigger | Snippet | Description |
|---------|---------|-------------|
| `con` | `constructor() { ... }` | Adds default constructor |
| `met` | `methodName() { ... }` | Creates a method inside the class |
| `pge` | `get propertyName() { return value; }` | Creates a getter |

---

## 🖥 Console Helpers

| Trigger | Snippet | Description |
|---------|---------|-------------|
| `clg` | `console.log(object);` | Simple log |
| `clo` | `console.log('object :>> ', object);` | Log with object name |
| `cer` | `console.error(object);` | Error log |

---

## 🔄 Loops & Functions

| Trigger | Snippet | Description |
|---------|---------|-------------|
| `fre` | `array.forEach(currentItem => { ... });` | forEach in ES6 syntax |
| `fof` | `for(const item of object) { ... }` | for...of loop |
| `fin` | `for(const item in object) { ... }` | for...in loop |
| `anfn` | `(params) => { ... }` | Anonymous function |
| `nfn` | `const add = (params) => { ... };` | Named function |
| `dob` | `const { rename } = object;` | Object destructuring |
| `dar` | `const [first, second] = array;` | Array destructuring |
| `sti` | `setInterval(() => { ... }, 1000);` | Set interval |
| `sto` | `setTimeout(() => { ... }, 1000);` | Set timeout |
| `prom` | `new Promise((resolve, reject) => { ... });` | Create a new Promise |
| `thenc` | `.then(res => { ... }).catch(err => { ... });` | then/catch for a Promise |

---

## 🧪 Jest / Testing Snippets

| Trigger | Snippet | Description |
|---------|---------|-------------|
| `desc` | `describe('description', () => { ... });` | Describe block |
| `test` | `it('should do something', () => { ... });` | Individual test |
| `beforeeach` | `beforeEach(() => { ... });` | Setup before each test |
| `aftereach` | `afterEach(() => { ... });` | Teardown after each test |
| `beforeall` | `beforeAll(() => { ... });` | Setup before all tests |
| `afterall` | `afterAll(() => { ... });` | Teardown after all tests |

---

## 🌐 Playwright Snippets

| Trigger | Snippet | Description |
|---------|---------|-------------|
| `goto` | `await page.goto('https://example.com');` | Navigate to a URL |
| `locator` | `const element = page.locator('selector');` | Select an element using locator |
| `click` | `await page.locator('selector').click();` | Click an element |
| `fill` | `await page.locator('selector').fill('value');` | Fill input with a value |
| `expect` | `await expect(page.locator('selector')).toHaveText('expected');` | Assert element has expected text |
| `tsp` | `test('should do something', async ({ page }) => { });` | Creates a Playwright test with page destructured |

---

## 📌 How to Use

1. Copy the JSON snippets into a `.code-snippets` file on your machine.  
2. In VSCode, go to `File → Preferences → User Snippets → New Global Snippets file` and paste the content.  
3. Type the **trigger** and press **TAB** to insert the snippet.  

---

## 🚀 Contributions

If you want to add more snippets or improve existing ones, create a **pull request** or open an **issue**.