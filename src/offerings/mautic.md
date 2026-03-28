---
layout: base.njk
title: Mautic — Email & Journeys
permalink: "/offering/mautic/"
---

{% set offering = offerings | selectattr("slug", "equalto", "mautic") | first %}

<div class="d-flex align-items-center gap-3 mb-4">
  <img src="/assets/images/logos/mautic.svg" alt="Mautic logo" style="max-height:48px;">
  <h1 class="mb-0">Mautic — Email &amp; Journeys</h1>
</div>

<p class="lead text-secondary mb-4">Manage subscribers, templates, segments, and automations. Your group gets its own login and can run newsletters and campaigns — no SaaS lock-in, no data handed to third parties.</p>

**What your group gets:**
- A dedicated Mautic login with isolated data
- Full control over subscriber lists, segments, email templates, and automations
- GDPR-friendly setup configured out of the box
- Onboarding support to migrate existing lists and send your first campaign

**Facilitated by Electron Workshop. Delivered by:**

<div class="d-flex flex-wrap gap-3 align-items-center my-3">
  <div class="p-3 rounded border border-primary border-opacity-25 text-center">
    <img src="/assets/images/logos/TalkingSites_Logo_Horizontal_Rounded.png" alt="Talking Sites" style="max-height:36px; width:auto;">
    <p class="text-muted mb-0 mt-1" style="font-size:.75rem;">Service Provider</p>
  </div>
  <div class="p-3 rounded border border-primary border-opacity-25 text-center">
    <img src="/assets/images/logos/serversaurus_logo.png" alt="Serversaurus" style="max-height:36px; width:auto;">
    <p class="text-muted mb-0 mt-1" style="font-size:.75rem;">Hosting Provider</p>
  </div>
</div>

<p class="text-secondary">Electron Workshop coordinates access and onboarding — the service is run by <strong>Talking Sites</strong> (specialist email and marketing support) on infrastructure provided by <strong>Serversaurus</strong>. Groups engage directly with these providers under terms they set.</p>

<p class="mt-4">
  <a href="/offering/" class="me-3">← All offerings</a>
  <a href="/initiatives/electron-network/" class="text-primary">How the network works →</a>
</p>
