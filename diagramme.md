**Key Points**:
- Use triple backticks (```` ``` ````) followed by `mermaid`
- Works natively in:
  - **GitHub/GitLab** (viewable in PRs/READMEs)
  - **VS Code** (with [Mermaid extension](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid))
  - **Docs sites** (Docusaurus, MkDocs with [plugins](https://mermaid-js.github.io/mermaid/#/./Setup))

---

### **2. Advanced Control**
#### **A. Styling (CSS-like)**
```markdown
```mermaid
flowchart LR
    A[Angular] -->|ESM| B{PWA-OS}
    style A fill:#dd0031,color:white
    style B fill:#64748b,color:white