# KALORA | Children's Health & Care 🌸

A simple Arabic-first web app that helps parents keep track of their children's vaccination schedule and understand why it matters.


## Problem
Some parents find it hard to keep track of their children's vaccination appointments.

## Aim
Develop an app that helps parents follow the child vaccination schedule and raises their awareness of its importance.

## Objectives
- Display the vaccination schedule.
- Remind parents of vaccination appointments.
- Provide educational information about each vaccine.
- Explain why sticking to the schedule matters.

## Final Product
An app containing the vaccination schedule, reminders, and awareness information.

## Features
- **Automatic schedule:** calculated from the child's date of birth (birth to school entry), with a status for each appointment (done / soon / overdue / upcoming) and a progress bar.
- **Reminders:** a next-appointment banner, a browser notification when the app is opened, and a calendar (.ics) file with a reminder one day before the appointment.
- **Vaccine information:** for each vaccine, what it protects against, why it matters, and expected side effects.
- **Why it matters:** an awareness card on the vaccines page.
- **Education library:** sections on dehydration, asthma, type 1 diabetes, newborn danger signs, and child safety.
- **Admin panel:** add articles and sections, with JSON backup export and import.
- **8 languages:** Arabic, English, Français, Español, Deutsch, Türkçe, Italiano, Urdu.

## Files
| File | Description |
|---|---|
| `kalora.html` | The whole app (HTML + CSS + JavaScript in one file) |
| `index.html` | A tiny page that redirects to `kalora.html`, so the site opens from the base link |
| `README.md` / `README.ar.md` | This file (English / Arabic) |

## Run locally
Open `index.html` or `kalora.html` in any browser. No installation or internet connection is needed.
 
## Important notes
- **Medical content:** the schedule is general and indicative. It is not an exact copy of the Jordanian Ministry of Health schedule and must be checked against the official one before use. Edit vaccines and ages in the `SCHED` and `VAX` arrays inside `kalora.html`.
- **This app does not replace the official vaccination card or a doctor's advice.**
- **Local storage:** child data, vaccination progress, and content added in the admin panel are saved only in each user's browser (localStorage). There is no server or database in this version.
- **Notifications** appear only when the app is opened. For reminders while the app is closed, use the calendar file.
- **The admin panel** is not password-protected in this version.

## Future improvements
- A server, database, and secure admin login.
- Real push notifications that work when the app is closed.
- `manifest.webmanifest` and `sw.js` so the app can be installed on the home screen.
- Match the schedule to the official Ministry of Health schedule and support multiple children.
  ## you can open in there :
kalora0.netlify.app
