# Cornucopia Guided Flow (POC)

This is a small proof of concept for my idea to improve OWASP Cornucopia.

While exploring the current website, I noticed that it mainly allows users to browse cards, but it does not clearly guide how to use them for real threat modeling.

So I built a simple flow to demonstrate the idea.

## What this POC shows

- User selects a context (like login system, API, etc.)
- One card is shown at a time
- User thinks about "what can go wrong"
- User marks whether it applies or not
- At the end, user gets a simple list of findings

## Purpose

The goal is to guide the user step by step, similar to how Cornucopia is used in real sessions, but in a simple single-user format.

This is just a basic version to explain the concept, not the final implementation.
