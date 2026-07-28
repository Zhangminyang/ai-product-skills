# Mermaid pattern

Use Mermaid when the structure is simple and should live alongside Markdown documentation.

```mermaid
flowchart TB
  subgraph Foundation[Shared foundation]
    Identity[Identity and access]
    Data[Core data]
  end
  subgraph Operations[Operations]
    Manage[Manage work]
    Analyze[Operational analysis]
  end
  subgraph Experience[User experience]
    Portal[Self-service portal]
  end
  External[External system]

  Identity --> Manage
  Data --> Manage
  Manage --> Analyze
  Manage --> Portal
  External -. integration .-> Manage
```

Keep layers small. If a diagram needs many crossing lines, separate the capability map from the system relationship diagram.
