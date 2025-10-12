# Diagram example

## Flowchart

```mermaid
graph TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```

## 高血鉀處置流程

```mermaid
graph TD
    A[發現血鉀 > 5.5 mmol/L] --> B{血鉀 ≥ 6.5 mmol/L<br>或 ECG 異常?}
    B -->|是| C[立即心肌穩定化<br>→ 給 10% Calcium gluconate 10 mL IV over 2–5 min]
    C --> D[評估心電圖變化<br>→ 可每5–10分鐘重複一次（最少間隔30分鐘）]
    B -->|否| E[排除假性高血鉀（溶血、標本問題等）]
    D --> F[促進細胞內移動]
    E --> F

```

## Sequence diagram

??? question "高血鉀處置"

    ```mermaid
    sequenceDiagram
        participant Alice
        participant Bob
        Alice->>John: Hello John, how are you?
        loop Healthcheck
            John->>John: Fight against hypochondria
        end
        Note right of John: Rational thoughts <br/>prevail...
        John-->>Alice: Great!
        John->>Bob: How about you?
        Bob-->>John: Jolly good!
    ```
