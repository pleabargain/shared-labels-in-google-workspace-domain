flowchart TD
    A[Email Arrives] -->|Received by| B[User's Inbox]
    B -->|User identifies relevant email| C{Apply projectX Label?}
    C -->|No| D[Email stays in personal inbox]
    C -->|Yes| E[User applies projectX label]
    E -->|System processes| F[Check permissions]
    F -->|Validate access| G[Update email visibility]
    G -->|Make accessible| H[Shared Access]
    H -->|Visible to| I[All users with projectX permissions]
    
    style A fill:#e1f5fe
    style B fill:#e8f5e9
    style C fill:#fff3e0
    style D fill:#ffebee
    style E fill:#f3e5f5
    style F fill:#e8eaf6
    style G fill:#e0f2f1
    style H fill:#f9fbe7
    style I fill:#fce4ec
```

# Email Sharing via Shared Labels in Google Workspace

This flowchart illustrates the process of sharing emails using shared labels in Google Workspace:

1. Initial Email Reception
   - Email arrives in user's inbox
   - Only visible to original recipient

2. Label Application Process
   - User decides whether to apply projectX label
   - If no label is applied, email remains private
   - User applies projectX label to share

3. System Processing
   - System checks user permissions
   - Updates email visibility settings
   - Makes email accessible to authorized users

4. Shared Access
   - Email becomes visible to all users with projectX permissions
   - Maintains organized project-based email sharing
