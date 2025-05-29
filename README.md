# ContactManagerApp (SwiftUI + Trie)
A fast and efficient **Contact Manager iOS app** built using **SwiftUI** and a custom **Trie (Prefix Tree)** data structure for lightning-fast contact search and autocomplete functionality.

## 📌 Features

- 📖 Add, edit, and delete contacts.
- 🔍 Real-time search suggestions using a **Trie-based prefix search**.
- 📱 Clean, modern SwiftUI interface.
- 🗂️ Efficient data storage in-memory using custom data structures.
- ✅ Unit-tested Trie implementation with XCTest.

## 🧠 Why Use a Trie?

A **Trie** is a highly efficient tree-based data structure for storing and searching strings — especially useful for prefix-based search. In this app:
- Contacts are stored in a **Trie**
- Search suggestions appear instantly as the user types
- Outperforms array-based `.filter { $0.hasPrefix() }` in large datasets

**Trie Advantages:**
- Faster lookup for prefix searches
- Optimized for autocomplete and dictionary apps
- Reduces time complexity from O(n) to O(k) where k = length of prefix

## 📦 Tech Stack

- **Language:** Swift 5
- **Framework:** SwiftUI, Combine
- **Data Structure:** Custom Trie
- **Testing:** XCTest
- **Version Control:** Git & GitHub

## 📂 Project Structure
