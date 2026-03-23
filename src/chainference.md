---
layout: base.njk
title: Chainference - Electron Workshop
description: A collaborative layer of community activities that strengthen conferences — before, during, and after.
permalink: "/chainference/"
---

<h1 class="mb-3">Chainference</h1>
<p class="lead mb-2">A collaborative layer that strengthens conferences.</p>
<p class="text-secondary mb-5">Chainference is a set of community activities that wrap around conferences — helping people prepare better proposals before the event, connect more meaningfully during it, and continue learning together after it. It sits alongside conferences, never replacing or directing them.</p>

<div class="row g-3 mb-3">
  <div class="col-12 col-md-4">
    <div class="p-3 border border-primary border-opacity-25 rounded-3 h-100">
      <div class="fw-semibold mb-1"><i class="bi bi-arrow-left-circle me-2 text-primary"></i>Before</div>
      <p class="small text-secondary mb-0">Ideation sessions, CFP readiness, speaker development</p>
    </div>
  </div>
  <div class="col-12 col-md-4">
    <div class="p-3 border border-primary border-opacity-25 rounded-3 h-100">
      <div class="fw-semibold mb-1"><i class="bi bi-broadcast me-2 text-primary"></i>During</div>
      <p class="small text-secondary mb-0">Fringe events, local meetups, cross-community connections</p>
    </div>
  </div>
  <div class="col-12 col-md-4">
    <div class="p-3 border border-primary border-opacity-25 rounded-3 h-100">
      <div class="fw-semibold mb-1"><i class="bi bi-arrow-right-circle me-2 text-primary"></i>After</div>
      <p class="small text-secondary mb-0">Watch parties, reflection sessions, continued engagement</p>
    </div>
  </div>
</div>

<hr class="my-5">

<h2 class="mb-4">Conferences</h2>

<div class="row g-4 mb-5">
  {% for conf in chainferences %}
  <div class="col-12 col-md-6 col-lg-4">
    <div class="card h-100 border-primary border-opacity-25 shadow-sm">
      <div class="card-body d-flex flex-column">
        <h3 class="h5 mb-1">{{ conf.title }}</h3>
        <p class="small text-secondary mb-1">{{ conf.tagline }}</p>
        <p class="flex-grow-1 small">{{ conf.description }}</p>
        <a href="/chainferences/{{ conf.slug }}/" class="btn btn-primary stretched-link">View activities</a>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div class="p-4 border border-primary border-opacity-25 rounded-3 text-center">
  <h3 class="h5 mb-2">Organising an activity around a conference?</h3>
  <p class="text-secondary mb-3 small">If you're running a workshop, meetup, watch party, or ideation session around any conference, submit it for listing on the relevant chainference page.</p>
  <a href="https://github.com/electron-workshop/ew-website/issues/new?template=chainference-activity.yml" class="btn btn-outline-primary">Propose an activity</a>
</div>
