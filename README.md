graph TD
    A[Development Dept. initiates process] --> B[Legal creates/reviews/upload Contract template]
    B --> C[SLA=5 WD, 1 WD Reminder]
    C -->|Escalate to Legal VP at 2 WD| D[Legal VP Action]
    C -->|Escalate to Legal VP at 5 WD| D
    B -->|Action Taken| E[Dev. team review & Approval]
    
    E --> F[SLA=1 WD, 1 WD Reminder]
    F -->|Escalate to Dev. Director at 1.5 WD| G[Dev. Director Action]
    
    E -->|Action Taken| H[Finance Sales accounts team review & Approval]
    
    H --> I[SLA=1 WD, 1 WD Reminder]
    I -->|Escalate to Director at 1.5 WD| J[Director Action]
    
    H -->|Action Taken| K[Marketing-Branding create Contract template]
    
    K --> L[SLA=3 WD, Daily Reminder]
    L -->|Escalate to Director at 1.5 WD| M[Director Action]
    
    K -->|Action Taken| N[Dev. team review & Approval]
    
    N --> O[SLA=1 WD, 1 WD Reminder]
    O -->|Escalate to Dev. Director at 1.5 WD| P[Dev. Director Action]
    
    N -->|Action Taken| Q[Finance Sales accounts team review & Approval]
    
    Q --> R[SLA=1 WD, 1 WD Reminder]
    R -->|Escalate to Director at 1.5 WD| S[Director Action]
    
    Q -->|Action Taken| T[Legal review & Approval, Send to IT]
    
    T --> U[SLA=2 WD, 1 WD Reminder]
    U -->|Escalate to Legal VP at 1 WD| V[Legal VP Action]
    U -->|Escalate to Legal VP at 2 WD| V
    
    T -->|Action Taken| W[IT uploads final contract on Salesforce]
    
    W --> X[SLA=1 WD, 1 WD Reminder]
    X -->|Escalate to T&S VP at 1 WD| Y[T&S VP Action]
    
    W -->|Action Taken| Z[All parties review and send final approval]
    
    Z --> AA[SLA=1 WD, 1 WD Reminder]
    AA -->|Escalate to Directors & VPs at 1 WD| AB[Directors & VPs Action]
    
    Z -->|Action Taken| AC[IT posts final approved contract on Salesforce]

