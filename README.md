Here’s a clean and professional `README.md` for your **"The Last Transmission"** API clue extractor project:

---

````markdown
# 🕵️‍♀️ The Last Transmission

A suspense-filled JavaScript project where you must uncover the final clue to a mystery by intercepting hidden API response headers. Neha, a missing student, left behind one last digital footprint—and it's your mission to decode it.

---

## 📌 Problem Statement

Neha's emergency safety app transmitted a final distress signal before going dark. Investigators found a suspicious API endpoint. However, the clue isn't in the response body—it's hidden in the **response headers**.

Your job is to fetch the secret message from the `X-Secret-Message` header and print it.

---

## 🔧 Function Signature

```js
async function fetchSecretKey() {
  // Logic to retrieve and print the secret message
}
````

---

## 🎯 Requirements

* Make an HTTP GET request to:

  ```
  https://run.mocky.io/v3/b7dd2779-9ca7-4525-8174-29ad162b298d
  ```
* Extract only the response **headers** (not the body).
* If `X-Secret-Message` exists, print:

  ```
  Secret Key: <message>
  ```
* If not found, print:

  ```
  No key found! Keep searching.
  ```
* If API call fails, print:

  ```
  System error! Unable to retrieve the key.
  ```

---

## ⚙️ Tech Stack

* ✅ JavaScript (ES6+)
* ✅ Native `fetch` API
* ❌ No external libraries (e.g., Axios)

---

## 🧪 Example

### ✅ Header present:

```http
X-Secret-Message: "Look for a red car."
```

**Output:**

```
Secret Key: Look for a red car.
```

### ❌ Header missing:

```
No key found! Keep searching.
```

### ⚠️ Request fails:

```
System error! Unable to retrieve the key.
```

---

## 🚀 How to Run

Simply run the JavaScript file using Node.js or in a browser console.

```bash
node index.js
```

---

## 💡 Notes

* The project uses async/await for clean asynchronous flow.
* Fully self-contained and auto-executing.
* Great practice for working with HTTP headers and handling errors.

---

## 👁️ Are You Ready to Crack the Code?

Time is ticking. Neha’s safety may depend on you.
Run the script, intercept the message, and unveil the final clue.

🕵️‍♂️ Good luck, agent.

```

---

Let me know if you want the above packed into a ZIP with `index.js`, or if you need a fancy animated landing page for this project!
```
