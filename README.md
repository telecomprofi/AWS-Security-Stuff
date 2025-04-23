graph TD
    A[Policy Document]
    A --> B[Version = 2012-10-17]
    A --> C[Statement List]
    C --> D[Statement 1]
    D --> E[Action = sts:AssumeRole]
    D --> F[Effect = Allow]
    D --> G[Principal]
    G --> H[Service = lambda.amazonaws.com]

```mermaid
  info
```

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
