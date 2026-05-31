# youtube-n8n-automation
Automated YouTube posting workflow using n8n

# 🎬 YouTube Auto-Post Automation (n8n)

Automatically upload and schedule YouTube videos 
without manual posting.

## How it Works
1. Add video details to Google Sheet queue
2. Upload video file to Google Drive
3. n8n automatically uploads to YouTube on schedule
4. Get email notification when live

## Tools Used
- n8n (automation)
- Google Sheets (video queue)
- Google Drive (video storage)
- YouTube Data API v3
- Gmail (notifications)

## Setup
1. Import `workflow.json` into n8n
2. Connect Google & YouTube credentials
3. Fill in your Google Sheet with video details
4. Activate the workflow

## Google Sheet Columns
| Column | Description |
|--------|-------------|
| video_title | Title of the video |
| description | Video description |
| tags | Comma separated tags |
| drive_file_id | Google Drive video URL |
| status | pending or posted |
| scheduled_date | YYYY-MM-DD format |
