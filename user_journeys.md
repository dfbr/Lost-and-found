# User Journeys: Lost and Found Platform

This document outlines the five most likely user journeys for this app, along with detailed steps for each. Additionally, a list of additional user journeys is provided for future elaboration.

---

## **Detailed User Journeys**

### 1. **Reporting a Lost Item**
#### Steps:
1. User logs into their account or registers for a new one.
2. User navigates to the "Report Lost Item" section.
3. They fill out a form with details such as item type, description, location where the item was lost, and an optional photo.
4. Upon submission, the item is listed on the "Lost Items" feed and potentially matched to relevant found items.
5. User is alerted when relevant matches or updates are found.

```mermaid
graph TD
    A[User logs in or registers] --> B[User navigates to "Report Lost Item"]
    B --> C[User fills out details (item type, description, location, photo)]
    C --> D[Item listed in "Lost Items" feed]
    D --> E[Potential matches identified]
    E --> F[User alerted with relevant matches or updates]
```

### 2. **Reporting a Found Item**
#### Steps:
1. User logs into their account or registers for a new one.
2. User opens the "Report Found Item" section.
3. They complete a form with information such as item type, description, location where the item was found, and an optional photo.
4. The platform lists the found item to the "Found Items" feed and attempts to match it to lost items.
5. User receives notifications if a match or an inquiry is made by the item owner.

```mermaid
graph TD
    A[User logs in or registers] --> B[User navigates to "Report Found Item"]
    B --> C[User fills out details (item type, description, location, photo)]
    C --> D[Item listed in "Found Items" feed]
    D --> E[Automatically matches to lost items]
    E --> F[User notified of matches or inquiries]
```

### 3. **Searching for an Item**
#### Steps:
1. User navigates to the search page without needing to sign in.
2. They input filters like item type, location, date, etc.
3. Platform displays possible matches from lost or found items.
4. User clicks on a result to view its details and contact the poster.
5. If signed in, the user can save their search or subscribe to receive alerts for similar items.

```mermaid
graph TD
    A[User navigates to search page] --> B[Input filters (type, location, date)]
    B --> C[Platform displays possible matches]
    C --> D[View details of a result]
    D --> E[Contact the poster]
    E --> F[Save search or subscribe for alerts (if signed in)]
```

### 4. **Matching Between Lost and Found Items**
#### Steps:
1. The platform automatically scans new postings (lost or found) for possible matches using keywords, location proximity, and image recognition.
2. An automated match notification is sent to both parties.
3. Users can review the match and initiate communication if they recognize their item.
4. Users coordinate to confirm ownership and arrange return logistics.

```mermaid
graph TD
    A[New lost or found post added] --> B[Platform scans for matches (keywords, location, images)]
    B --> C[Automated match notification sent to both parties]
    C --> D[Users review the match]
    D --> E[Users communicate if match is valid]
    E --> F[Coordinate ownership confirmation and return]
```

### 5. **Direct Communication Between Users**
#### Steps:
1. A user locates a listing they believe matches their lost/found item.
2. They click "Contact" to initiate a secure chat within the app.
3. Message notifications are exchanged using in-app alerts or email.
4. Users coordinate details but are encouraged to meet in secure locations for item handoff.

```mermaid
graph TD
    A[User locates a matching listing] --> B[Click "Contact" to initiate chat]
    B --> C[Secure chat opened]
    C --> D[Users exchange messages]
    D --> E[Coordinate handoff at a secure location]
```

---

## **Additional User Journeys for Future Detailing**
1. Registering and managing an account.
2. Subscribing to search result alerts.
3. Integrating social media for item reports (e.g., posting a lost item to Facebook/Instagram).
4. Managing and editing existing listings.
5. Flagging inappropriate or suspicious posts.
6. Notifications and reminders for unresolved reports.
7. Deleting an account and personal data (GDPR compliance).
8. Reporting lost pets specifically (custom workflows for pets).
9. Reporting stolen items to authorities (with police report integration).
10. Claiming an item as resolved (marking lost or found items as completed).

---
This document will be updated as the platform evolves.