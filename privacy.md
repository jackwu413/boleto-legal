---
title: Privacy Policy
description: How Boleto collects, uses, and protects your data.
---

# Privacy Policy

**Effective date:** May 23, 2026

Boleto is a personal concert tracker — a place to keep a list of shows you've bought tickets to, get a day-of earplug reminder, and look back on shows you've been to. This page explains what data Boleto collects, why, and what you can do about it.

The plain summary: Boleto only collects what's needed to make the app useful for you. Nothing is sold. Nothing is shared with advertisers. There are no third-party trackers.

## What we collect

### When you sign up
- **Email address** — for signing in
- **Password** — never visible to us; stored as a hashed value by Supabase (our auth and database provider)

### During onboarding
- **Home city** — used to surface shows near you. You enter this manually; we don't read your device location.
- **Approximate coordinates** of your home city — computed locally on your device from the city name (via Apple MapKit) and stored so server-side jobs (e.g., wishlist notifications) can use them later without re-geocoding.

### As you use the app
- **Shows you add** — artist, venue, date, time, ticket holder, ticket platform (Ticketmaster / AXS / Dice / etc.), seat info if any, and any notes you write
- **Wishlist items** — artists or specific shows you've flagged to follow
- **Notification preferences** — whether you want the earplug reminder and how many hours before each show it should fire
- **Past show attendance** — whether you attended, missed, sold, or had a show cancelled, plus your privacy choice for that record (private or visible to friends, when that feature exists)

### When you send beta feedback
- **The text of your message**
- **App version, device model (e.g., `iPhone17,1`), and iOS version** — so we can correlate reports to specific builds and devices

### Automatic
- **Account creation timestamp** and timestamps on records you create

## What we don't collect

- Your device location (we only know your manually-entered home city)
- Your contacts, photos, or files
- Any data from other apps on your device
- Analytics about how you use the app
- Crash reports (planned for a future version; will be added to this policy if so)
- Identifiers used for ad tracking

## How we use it

- To run the app: show you your upcoming shows, deliver the earplug reminder, sync changes across your devices when you sign in
- To search for shows and artists: when you search for an artist, your query is sent to Spotify (for artist autocomplete) and to Ticketmaster (for show lookup); the results are cached so future lookups don't repeat the request
- To respond to your feedback if needed

## Notifications

Earplug reminders are scheduled on your device using Apple's standard local notification system. The notifications themselves never leave your phone — they're not pushed from a server. If you uninstall the app or sign out, all pending reminders are removed.

## Who we share data with

Boleto uses a small number of third-party services to operate. Each has its own privacy policy.

- **Supabase** — stores your account, shows, wishlist, and feedback. [Supabase privacy policy](https://supabase.com/privacy)
- **Spotify Web API** — receives your artist search queries to power autocomplete. We don't send your account, email, or any personal identifier. [Spotify privacy policy](https://www.spotify.com/legal/privacy-policy/)
- **Ticketmaster Discovery API** — receives artist names you've selected so we can fetch upcoming shows. [Ticketmaster privacy policy](https://www.ticketmaster.com/privacy)
- **Apple** — handles authentication, app distribution, and (when you tap an address) launches Maps. [Apple privacy policy](https://www.apple.com/legal/privacy/)

We do not sell or rent your data. We do not share it with advertisers.

## Where data is stored

Your account and app data are stored in a Supabase project hosted in the United States. Search caches (artists, venues, shows) are shared across users to reduce duplicate API calls.

## Your rights

You can:
- **See your data** — most of it is visible to you directly in the app
- **Change your data** — edit your home city, your shows, your notification preferences in-app
- **Delete your data** — email the contact below to request account and data deletion. Deletion cascades to all rows you own (shows, wishlist, feedback, preferences) and cannot be undone. We'll act on the request within 30 days.

If you live somewhere with stronger data rights (EU/UK/California/etc.), the rights above are how we operationalize them. Reach out and we'll work it out.

## Children

Boleto is not directed at children under 13. If you believe a child has signed up, contact us and we'll delete the account.

## Retention

Data is retained until you delete your account. Backups may persist for a short period after deletion as part of Supabase's standard backup cycle.

## Changes to this policy

If we change what we collect or how we use it, we'll update this page and bump the effective date at the top. For meaningful changes, we'll also notify you in the app or by email.

## Contact

Questions, deletion requests, or anything else:

**Jack Wu** — getboleto@gmail.com
