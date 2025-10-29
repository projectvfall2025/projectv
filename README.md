# project Vinimi-ReactJs


Main Components

**1. Dashboard**

Interactive compliance metrics (helmet usage, detection count, zone breakdown).

Real-time status cards and summary graphs.

Navigation links for logs, alerts, reports.

**2. Alerts Center**

Table/list of triggered alerts.

Filter by date, type, zone, camera.

Each alert shows detection snapshot, description, timestamp, and severity.

Alert actions: acknowledge, export, send SMS/email.

**3. Detection Logs**

Paginated, filterable history of all detection events.

Columns for video ID, person, zone, status, timestamp, confidence.

Linked to video/image evidence.

Export options (CSV, PDF).

**4. Video & Image Wall**

Grid view of camera feeds, each tile overlays event markers.

Click to view full feed or detailed event.

Live/Playback toggle.

Snapshots with bounding boxes for detected objects.

**5. Alert Creation (Natural Language)**

Input panel allowing admins to type rule like “Notify when helmet is missing in Zone A for more than 10 seconds.”

Templates for frequently used alerts (helmet missing, entry into restricted zones).

Advanced settings: select object/person, time threshold, zone/camera, notification type.

**6. Person/Asset Management**

List/search persons.

Add/edit contact info and images.

Upload new face embedding.

**7. Analytics**

Charts: helmet compliance over time, per zone/person, incident stats.

Custom reports generator.

**8. Settings**

User roles, access control.

Alert configuration (who receives, how).

Camera management, detection thresholds.

**9. Notification System**
(optional)
Snackbar or modal for real-time event alerts.

Option to push to phone/email/third-party API.

Customizable notification sound/visual level.

