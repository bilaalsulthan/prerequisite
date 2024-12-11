# osTicket Post-Installation Configuration

## Step 1: Secure osTicket Installation
1. Remove the `setup/` directory to prevent unauthorized access:
   ```bash
   sudo rm -rf /var/www/html/osticket/setup
   ```
2. Set appropriate permissions on the `ost-config.php` file:
   ```bash
   sudo chmod 0644 /var/www/html/osticket/include/ost-config.php
   ```

![Step 1: Secure Installation](https://via.placeholder.com/800x400.png)

---

## Step 2: Configure System Settings
1. Log into the **Admin Panel** as an administrator.
2. Navigate to **Admin Panel > Settings**:
   - Set your organization name and default system email.
   - Configure timezone and language preferences.
3. Set up additional email addresses for ticket creation and response notifications.

![Step 2: Configure System Settings](https://via.placeholder.com/800x400.png)

---

## Step 3: Customize User Roles and Departments
1. Go to **Admin Panel > Agents > Roles**:
   - Create and assign custom roles to staff members.
   - Define permissions for each role.
2. Navigate to **Admin Panel > Departments**:
   - Create departments such as IT Support, Customer Service, etc.
   - Assign staff to specific departments.

![Step 3: Customize Roles and Departments](https://via.placeholder.com/800x400.png)

---

# osTicket Ticket Lifecycle Examples

## Step 1: Create a Ticket
1. Visit the **Client Portal**.
2. Fill out the ticket submission form:
   - Enter details like subject, description, and priority.
   - Attach any relevant files if necessary.
3. Submit the ticket to generate a unique ticket ID.

![Step 1: Create a Ticket](https://via.placeholder.com/800x400.png)

---

## Step 2: Manage Tickets
1. Log into the **Admin Panel** as a staff member.
2. Navigate to **Tickets > Open Tickets**:
   - View ticket details.
   - Assign tickets to agents or departments.
3. Respond to tickets using the built-in reply system or canned responses.

![Step 2: Manage Tickets](https://via.placeholder.com/800x400.png)

---

## Step 3: Close or Escalate Tickets
1. Close resolved tickets by selecting **Close** in the ticket view.
2. Escalate unresolved tickets to higher departments or roles.
3. Use **SLA Plans** to automate escalation rules based on time thresholds.

![Step 3: Close or Escalate Tickets](https://via.placeholder.com/800x400.png)

---

## Instructions for GitHub

- Save this content in a `README.md` file.
- Replace placeholder image URLs (e.g., `https://via.placeholder.com/...`) with actual screenshots.
- Push the file to your GitHub repository.

**Example Commands**:
```bash
git init
git add README.md
git commit -m "Add osTicket Post-Installation Configuration and Lifecycle Examples"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin main
```
# prerequisite
