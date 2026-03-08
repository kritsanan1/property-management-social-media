---
name: property-management-social-media-assistant
description: >
  Specialized workflow for managing Facebook Page content and LINE notifications for property management businesses.
  Use for: creating text/photo/video posts, scheduling content, analyzing post performance, and sending LINE notifications.
---

# Property Management Social Media Assistant

This skill provides a comprehensive solution for property management businesses to streamline their social media presence on Facebook and communicate effectively via LINE.

## Core Features

### 1. Automated Content Planner (Z-01)

**Objective:** Plan and publish content according to a calendar-based schedule.

**Features:**
*   **Content Templates:** Pre-defined templates for common property management communications:
    *   **ประกาศนิติฯ (Announcement):**
        -   `[หัวข้อ]` (Topic)
        -   `[รายละเอียด]` (Details)
        -   `[วัน/เวลา]` (Date/Time)
        -   `[สถานที่/ area]` (Location/Area)
        -   `[Action/ the action]` (Call to Action)
    *   **เกร็ดความรู้/Promotion (Tips/Promotion):** Templates for informative or promotional content.
*   **Scheduling Reminders:** System-generated reminders to ensure timely content publication.

### 2. Multi-Channel Broadcaster (Z-02)

**Objective:** Distribute content simultaneously to Facebook Page and LINE Group.

**Features:**
*   **Facebook Group Poster:** Automatically shares posts from the Facebook Page to designated village/condo groups.
*   **LINE Notify Integration:** Sends summary notifications of important posts to LINE groups for residents or committees.

### 3. Insight & Engagement Tracker (Z-03)

**Objective:** Analyze the performance of posts across different categories.

**Features:**
*   **Engagement Summary:** Provides a summary of likes, comments, and shares for each post.
*   **Optimal Posting Time Analysis:** Identifies peak activity times of residents to recommend the best posting schedules.

## Workflow

1.  **Content Creation:** Utilize predefined templates to draft posts.
2.  **Scheduling:** Assign posts to the content calendar.
3.  **Publication:** Posts are automatically published to Facebook and notifications sent to LINE.
4.  **Performance Review:** Analyze post-performance and adjust strategies as needed.

## Bundled Resources

*   `scripts/`: Contains automation scripts for Facebook API integration, LINE Notify API calls, and data analysis.
*   `references/`: Includes documentation for Facebook Graph API, LINE Notify API, and content best practices for property management.
*   `templates/`: Stores JSON or Markdown templates for various post types.

## Next Steps

I will now proceed to create the necessary scripts and templates to support these features. This will involve:

1.  **Structured Data (JSON):** For managing content schedules and post data.
2.  **Automation Scripts:** To connect with Facebook and LINE APIs (potentially via a service like Zapier/Make or direct API calls).

[TODO: Add content here. See examples in existing skills:
- Code samples for technical skills
- Decision trees for complex workflows
- Concrete examples with realistic user requests
- References to scripts/templates/references as needed]

## Resources

This skill includes example resource directories that demonstrate how to organize different types of bundled resources:

### scripts/
Executable code (Python/Bash/etc.) that can be run directly to perform specific operations.

**Examples from other skills:**
- PDF skill: `fill_fillable_fields.py`, `extract_form_field_info.py` - utilities for PDF manipulation
- DOCX skill: `document.py`, `utilities.py` - Python modules for document processing

**Appropriate for:** Python scripts, shell scripts, or any executable code that performs automation, data processing, or specific operations.

**Note:** Scripts may be executed without loading into context, but can still be read by Manus for patching or environment adjustments.

### references/
Documentation and reference material intended to be loaded into context to inform Manus's process and thinking.

**Examples from other skills:**
- Product management: `communication.md`, `context_building.md` - detailed workflow guides
- BigQuery: API reference documentation and query examples
- Finance: Schema documentation, company policies

**Appropriate for:** In-depth documentation, API references, database schemas, comprehensive guides, or any detailed information that Manus should reference while working.

### templates/
Files not intended to be loaded into context, but rather used within the output Manus produces.

**Examples from other skills:**
- Brand styling: PowerPoint template files (.pptx), logo files
- Frontend builder: HTML/React boilerplate project directories
- Typography: Font files (.ttf, .woff2)

**Appropriate for:** Templates, boilerplate code, document templates, images, icons, fonts, or any files meant to be copied or used in the final output.

---

**Any unneeded directories can be deleted.** Not every skill requires all three types of resources.
