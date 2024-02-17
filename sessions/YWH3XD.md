---
voc: https://media.ccc.de/v/sotm2022-18524-inferring-default-speed-limits
recordings: [{'size': 124, 'length': 1843, 'mime_type': 'video/webm', 'language': 'eng', 'filename': 'sotm2022-18524-eng-Inferring_default_speed_limits_webm-hd.webm', 'state': 'new', 'folder': 'webm-hd', 'high_quality': True, 'width': 1920, 'height': 1080, 'updated_at': '2022-09-19T11:41:34.383+02:00', 'recording_url': 'https://cdn.media.ccc.de/events/sotm/2022/webm-hd/sotm2022-18524-eng-Inferring_default_speed_limits_webm-hd.webm', 'url': 'https://api.media.ccc.de/public/recordings/61816', 'event_url': 'https://api.media.ccc.de/public/events/14990654-5de1-5f83-b792-a7bd7bd1abab', 'conference_url': 'https://api.media.ccc.de/public/conferences/sotm2022'}, {'size': 60, 'length': 1843, 'mime_type': 'video/webm', 'language': 'eng', 'filename': 'sotm2022-18524-eng-Inferring_default_speed_limits_webm-sd.webm', 'state': 'new', 'folder': 'webm-sd', 'high_quality': False, 'width': 720, 'height': 576, 'updated_at': '2022-09-19T11:22:04.793+02:00', 'recording_url': 'https://cdn.media.ccc.de/events/sotm/2022/webm-sd/sotm2022-18524-eng-Inferring_default_speed_limits_webm-sd.webm', 'url': 'https://api.media.ccc.de/public/recordings/61809', 'event_url': 'https://api.media.ccc.de/public/events/14990654-5de1-5f83-b792-a7bd7bd1abab', 'conference_url': 'https://api.media.ccc.de/public/conferences/sotm2022'}, {'size': 43, 'length': 1843, 'mime_type': 'video/mp4', 'language': 'eng', 'filename': 'sotm2022-18524-eng-Inferring_default_speed_limits_sd.mp4', 'state': 'new', 'folder': 'h264-sd', 'high_quality': False, 'width': 720, 'height': 576, 'updated_at': '2022-09-19T11:04:16.514+02:00', 'recording_url': 'https://cdn.media.ccc.de/events/sotm/2022/h264-sd/sotm2022-18524-eng-Inferring_default_speed_limits_sd.mp4', 'url': 'https://api.media.ccc.de/public/recordings/61800', 'event_url': 'https://api.media.ccc.de/public/events/14990654-5de1-5f83-b792-a7bd7bd1abab', 'conference_url': 'https://api.media.ccc.de/public/conferences/sotm2022'}, {'size': 28, 'length': 1843, 'mime_type': 'audio/mpeg', 'language': 'eng', 'filename': 'sotm2022-18524-eng-Inferring_default_speed_limits_mp3.mp3', 'state': 'new', 'folder': 'mp3', 'high_quality': False, 'width': 0, 'height': 0, 'updated_at': '2022-09-19T11:03:57.488+02:00', 'recording_url': 'https://cdn.media.ccc.de/events/sotm/2022/mp3/sotm2022-18524-eng-Inferring_default_speed_limits_mp3.mp3', 'url': 'https://api.media.ccc.de/public/recordings/61799', 'event_url': 'https://api.media.ccc.de/public/events/14990654-5de1-5f83-b792-a7bd7bd1abab', 'conference_url': 'https://api.media.ccc.de/public/conferences/sotm2022'}, {'size': 90, 'length': 1843, 'mime_type': 'video/mp4', 'language': 'eng', 'filename': 'sotm2022-18524-eng-Inferring_default_speed_limits_hd.mp4', 'state': 'new', 'folder': 'h264-hd', 'high_quality': True, 'width': 1920, 'height': 1080, 'updated_at': '2022-09-19T10:56:25.719+02:00', 'recording_url': 'https://cdn.media.ccc.de/events/sotm/2022/h264-hd/sotm2022-18524-eng-Inferring_default_speed_limits_hd.mp4', 'url': 'https://api.media.ccc.de/public/recordings/61794', 'event_url': 'https://api.media.ccc.de/public/events/14990654-5de1-5f83-b792-a7bd7bd1abab', 'conference_url': 'https://api.media.ccc.de/public/conferences/sotm2022'}]
layout: session
title: "Inferring default speed limits"
code: "YWH3XD"
speaker_names: ['Tobias Zwick']
affiliations: None
room: "Auditorium A"
length: "20"
time: "Friday, 17:30"
time_iso: "2022-08-19T15:30:00Z"
resources: [{ description: "Presentation as PDF", url: "/attachments/YWH3XD_Inferring_Default_Speed_Limits_-_Tobias_Zwick_3YzEqob.pdf" },{ description: "Presentation as PPTX", url: "/attachments/YWH3XD_Inferring_Default_Speed_Limits_-_Tobias_Zwick_dx4AAi2.pptx" },{ description: "Presentation as ODP", url: "/attachments/YWH3XD_Inferring_Default_Speed_Limits_-_Tobias_Zwick_pR77kSk.odp" },{ description: "If no internet: France", url: "/attachments/YWH3XD_plan_b_france_pcaQpyx.png" },{ description: "If  no internet: Germany", url: "/attachments/YWH3XD_plan_b_germany_8BSg9Yr.png" },{ description: "If no internet: Vietnam", url: "/attachments/YWH3XD_plan_b_vietnam_rkF4gSK.png" }]
recording: True
---

Coverage of `maxspeed` data in OpenStreetMap is very sketchy (about 12%). This situation is unlikely to change because the limits are often not signed explicitly. So, data consumers such as router software need to compensate huge holes in the data with more or less rough estimates based on other data.

This talk shall explore a method how to infer default speed limits for different vehicle and road types more precisely for each country.
