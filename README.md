# MISpal demo

A self-contained, front-end-only demo of the MISpal school management platform.

## What is in here

- `index.html`: the whole demo (HTML, CSS and vanilla JavaScript in one file).
- `videoloadtest2.MP4`: the custom loading screen video. It plays on first visit and between screens.
- `vercel.json`: static hosting config with basic security headers.

## Portals

- Admin and teacher portals (attendance, timetable builder, classes, assessments, enrolment, permissions, behaviour, substitutions and more).
- Parent onboarding and parent portal.
- Student portal for both demo schools.

## Important limits

This is a demo. All data lives in memory in the browser and resets on refresh.
There is no real authentication, no server and no database. Do not enter real personal data.
A production build needs a real backend with authentication, role based access control, tenant isolation, encryption and audit logging, plus a DPIA before real pupil data is used.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server, for example `npx serve .`.
