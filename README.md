# Hiplet 2027-28 Tour Dashboard

A single-page booking dashboard for the **Chicago Multi-Cultural Dance
Center / Hiplet Ballerinas** 2027-28 tour: season goals, pipeline counts,
confirmed dates, and the state of each active venue conversation.

**[Open the dashboard →](https://jovanayc.github.io/hiplet-dashboard/)**

## What's in it

- **Season goals** — target tour shape for Fall 2027 and Spring 2028
- **At a glance** — inquiry, conversation, hold, and booking counts
- **Booked** — confirmed dates
- **Active conversations** — who replied, what they said, what's next
- **Pipeline** — password-protected

## The protected section

The Pipeline section is encrypted in the page itself. Nothing in it is readable
from the page source without the password, and the password is never
stored in the repo & must be shared by owner of repo.

Requires a current browser — Chrome, Safari, Edge, or Firefox — over
HTTPS. The unlock will not work on a page opened from the filesystem.

## Running it

No build step and no dependencies. `index.html` is the whole thing:
open it directly, or serve the folder.
