---
permalink: /privacy/
---

# Balance Test Privacy Policy

**Effective date: 16 October 2026**

Balance Test is an offline postural-sway measurement app for Android. It measures how a
person's balance board tilts while they stand on it, stores the results, and exports
them. It works entirely without a network: there are **no accounts, no analytics, no
advertising and no servers** — the app declares **zero Android permissions** and contains
no network code at all. Everything it records stays on your device.

_"The developer" means the individual who publishes Balance Test on Google Play
([contact](#7-contact-and-data-protection-requests))._

## 1. The short version

- Balance Test has **no permissions, no accounts, no analytics, no ads and no tracking**.
  The developer operates no backend and cannot see anything you measure.
- The people you measure (first and last name, optional email and note), every session,
  the raw sway samples, the computed metrics and your settings are stored **only on your
  device**.
- Exports (CSV, TSV or JSON files) go **only where you send them** — the app hands the
  file to the system share sheet or file picker you choose.
- You can delete everything at any time: delete a person (which deletes their
  measurements), delete individual sessions, or uninstall the app.

## 2. Data stored only on your device

The app's local database holds:

- **Persons** ("subjects"): first name, last name, an optional email address and note,
  and whether they are archived.
- **Sessions**: who was measured, with which protocol (preset or custom), the plane of
  the board, eyes open/closed, duration, completion, an optional note, and the computed
  sway metrics (means, standard deviations, path lengths, velocities, ellipse area).
- **Raw samples**: the tilt angles recorded during each measurement, thousands per
  session.

The app's local settings store hold your measurement defaults (sound, countdown length,
default duration and plane), language, appearance choice, and a one-time flag that the
placement guide was shown.

None of this is ever transmitted by the app. Two platform caveats:

- **Android backup:** the app allows Android's automatic device backup. If you use it,
  Android may include the database described above — which contains names and
  health-adjacent measurement data — in the backup of your Google account, or copy it in
  a direct phone-to-phone transfer. Backup is a device feature you control in Android
  settings; the developer cannot access, read or restore it. If you do not want this
  data in cloud backups, disable Android backup for this app (Settings › Apps › Balance
  Test › Back up) or turn off Android backup entirely.
- **Exported files:** exporting creates a file (CSV, TSV or JSON) that contains person
  names and the full measurement data. It travels only where you send it through the
  system share sheet or the file picker. The developer never receives a copy.

## 3. Permissions

| Permission | Why |
|---|---|
| — none — | The app is fully offline by design. It requests no permissions at install and none at runtime: no location, no storage, no network, no phone state. |

Movement is read from the phone's own motion sensors, which require no permission, and
sound plays through the media volume you control. That is the entire hardware surface.

## 4. Data retention and deletion

- **On your device:** data is kept until you delete it. Deleting a person deletes all of
  their sessions and samples with them; individual sessions or a selected batch can be
  deleted from the session history. Uninstalling the app removes all app data — except
  copies that exist in exports you made or in Android backups (see section 2).
- **Exported files** are yours: they live wherever you saved or shared them and are not
  affected by deleting data in the app.
- **The developer keeps no user data**, because none is ever sent to the developer.

## 5. Children

Balance Test is not directed at children under 13, and no personal information is
collected from anyone — child or adult — because nothing leaves the device. If you
measure a minor, do so as a parent or guardian, or under the supervision of a
professional who is authorised to work with them.

## 6. Changes to this policy

If the policy changes, the new version will be published at this URL with a new
effective date. Material changes will additionally be noted in app update notes.

## 7. Contact and data-protection requests

Balance Test stores your data only on your own device, so in almost every case you can
exercise your data rights directly in the app or by uninstalling it. For anything else,
contact:

- Email: <usdevplay@gmail.com>
- Developer: Uroš Slana

Terms of use (liability, not a medical device):
<https://lobicode.github.io/balancetest-privacy/terms/>
