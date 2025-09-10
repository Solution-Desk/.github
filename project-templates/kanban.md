# Delivery Board

This repo uses a classic Kanban board:

- **Backlog** – triage + ready ideas  
- **In Progress** – actively being built  
- **In Review** – open PRs awaiting review  
- **Next Release** – merged items queued for the next tag  
- **Done** – released/closed

**Automation:**
- New issues → Backlog  
- PRs → In Progress; when “Ready for review” → In Review  
- Closed items → Done  
- Labels: `priority: high` → In Progress, `triage` → Backlog

Open board: **Repo → Projects → Delivery Board**
