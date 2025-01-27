

```mermaid
flowchart TD
    A[Email Arrives] -->|Received by| B[User's Inbox]
    B -->|User identifies relevant email| C{Apply projectX Label?}
    C -->|No| D[Email stays in personal inbox]
    C -->|Yes| E[User applies projectX label]
    E -->|System processes| F[Check permissions]
    F -->|Validate access| G[Update email visibility]
    G -->|Make accessible| H[Shared Access]
    H -->|Visible to| I[All users with projectX permissions]
    
    style A fill:#2196f3,color:#ffffff
    style B fill:#2196f3,color:#ffffff
    style C fill:#ff9800,color:#ffffff
    style D fill:#f44336,color:#ffffff
    style E fill:#3f51b5,color:#ffffff
    style F fill:#3f51b5,color:#ffffff
    style G fill:#3f51b5,color:#ffffff
    style H fill:#2196f3,color:#ffffff
    style I fill:#2196f3,color:#ffffff
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
