---
name: airbnb-listing-optimizer
description: Use this skill to audit, rewrite, and optimize Airbnb and short-term-rental listings, including titles, descriptions, amenity positioning, photo guidance, guest-fit messaging, and conversion-focused improvement plans. Trigger when the user asks for Airbnb listing optimization, rental listing copy, STR listing audits, host conversion improvements, or guest-facing listing rewrites. Do not use it for booking management, scraping competitor listings, evading platform rules, discriminatory targeting, fake reviews, or legal, tax, or regulatory advice.
---

# Airbnb Listing Optimizer

## Purpose

Help an agent improve Airbnb and short-term-rental listing performance through truthful, guest-centered, conversion-aware copy and recommendations based on user-provided property details, listing text, photos, amenities, reviews, and constraints.

This skill should produce practical listing improvements without claiming guaranteed ranking gains, inventing property features, or giving legal, tax, regulatory, or platform-policy advice as fact. For current platform rules, local regulations, or recently changed requirements, verify with current authoritative sources before making specific claims.

## When to use

Use this skill when the user asks to:

- Rewrite or improve an Airbnb listing title, subtitle, summary, description, house rules, or amenity copy.
- Audit a short-term-rental listing for clarity, trust, conversion friction, search relevance, and guest experience fit.
- Create title options, first-paragraph hooks, feature bullets, room-by-room descriptions, or photo caption guidance.
- Translate property facts into guest-centered benefits while keeping claims accurate and supportable.
- Improve listing positioning for trip contexts such as remote-work stays, romantic weekends, group trips, pet-friendly stays, event travel, outdoor recreation, or longer stays.
- Turn reviews, guest questions, amenity lists, or photo notes into listing improvements.
- Build a listing optimization plan with quick wins, experiments, and information gaps.

## Do not use

Do not use this skill when:

- The user wants automated booking management, guest messaging at scale, dynamic pricing automation, calendar syncing, or property-management operations beyond listing content and recommendations.
- The task requires scraping, copying, or closely imitating competitor listings without permission.
- The user asks for fake reviews, fake scarcity, misleading amenities, hidden fees, manipulated ratings, or unsupported claims.
- The user asks to evade Airbnb rules, local regulations, taxes, permits, safety requirements, identity checks, or guest protections.
- The user asks for discriminatory targeting, exclusion, or discouragement based on protected characteristics. Keep guest-fit language based on trip needs, amenities, accessibility facts, and property suitability.
- The user needs legal, tax, insurance, zoning, permitting, HOA, lease, or regulatory advice. Provide general issue-spotting only and recommend qualified local guidance.
- The request depends on current platform policy, marketplace conditions, or algorithm details and no current source has been checked.

## Required inputs

Use information already provided. Ask only for missing essentials that materially affect accuracy. Helpful inputs include:

- Property type, general location, setting, and neighborhood context.
- Number of bedrooms, bathrooms, beds, maximum guests, and notable layout details.
- Top amenities, standout features, design style, outdoor areas, workspace, parking, kitchen, laundry, climate control, accessibility facts, pet policy, and family-friendly facts if applicable.
- Nearby attractions, transit, drive times, walkability, seasonal draws, and known tradeoffs such as stairs, noise, parking limits, shared spaces, or remote roads.
- Current listing title, description, amenity list, house rules, fees, cancellation context, and host goals.
- Photo list or screenshots described by the user, including current order and what each image shows.
- Review excerpts, frequent guest questions, complaints, conversion concerns, occupancy goals, target stay length, and target trip contexts.
- Required tone, language, marketplace, and output format.

Minimum viable input: property facts plus the user's optimization goal. If details are incomplete, proceed with clearly labeled assumptions and a short list of high-impact questions.

## Workflow

1. Confirm the task is listing optimization, listing copy, or listing audit work within this skill's boundaries.
2. Extract a listing brief from the user's materials: property facts, ideal trip contexts, proof points, constraints, tradeoffs, and missing information.
3. Separate facts from assumptions. Do not invent amenities, views, locations, accessibility, parking, safety features, local distances, or policy details.
4. Identify the primary guest value proposition using needs-based trip contexts rather than protected-characteristic targeting.
5. Audit the existing listing, if provided, across these dimensions:
   - Clarity: what the place is, where it is, who it comfortably suits, and what is included.
   - Trust: specificity, accuracy, transparent tradeoffs, rules, fees, and expectation-setting.
   - Conversion: opening hook, scannability, benefit-led features, photo-story alignment, and call-to-action strength.
   - Search relevance: natural use of likely guest search terms without keyword stuffing or unsupported platform-ranking claims.
   - Guest experience: check-in, parking, sleep quality, work setup, cooking, pets, accessibility facts, noise, climate, and local logistics.
6. Draft optimized copy using a truth-first structure:
   - Lead with the strongest guest benefit and property differentiator.
   - Use concrete details before adjectives.
   - Turn amenities into guest outcomes.
   - Mention important limitations or tradeoffs in neutral language.
   - Keep copy scannable with short paragraphs and labeled sections when useful.
7. Produce multiple title or opening-hook options when requested. Vary positioning rather than minor word swaps.
8. Provide photo guidance only from user-provided image descriptions or screenshots. Recommend order, missing shots, and captions without claiming to see details that were not supplied.
9. Include compliance and accuracy notes for anything that must be verified, such as local rules, platform policies, safety claims, accessibility language, or exact distances.
10. End with prioritized next steps: quick wins, content experiments, missing proof points, photo improvements, and questions that would improve the next revision.
11. Run the quality checklist before finalizing.

## Output format

Match the user's requested format. When no format is specified, use:

1. Assumptions and missing inputs
2. Listing position in one sentence
3. Optimization audit or rationale
4. Optimized title options
5. Optimized opening summary
6. Full listing description or revised sections
7. Amenity and feature bullets
8. Photo order and caption recommendations, if photo information is available
9. Accuracy, policy, and compliance notes
10. Prioritized next-step checklist

For shorter requests, provide only the requested copy plus concise notes. For audits, provide a scorecard with severity and fixes.

## Quality checklist

Before finalizing:

- The output directly improves the user's listing goal.
- All property claims are based on user-provided facts or clearly labeled assumptions.
- The copy is specific, scannable, benefit-led, and free of keyword stuffing.
- The title options are meaningfully different and guest-facing.
- Tradeoffs are presented honestly without over-apologizing.
- No fake reviews, fake scarcity, misleading location claims, or unsupported ranking guarantees are included.
- Guest-fit language avoids discriminatory targeting and exclusion.
- Current platform rules, legal requirements, tax issues, permits, and local regulations are not presented as verified unless current authoritative sources were checked.
- Sensitive details such as exact address, lock codes, security camera placement beyond necessary disclosure, owner schedules, or private guest information are not exposed.
- The final answer includes clear assumptions, verification needs, and next steps when relevant.

## Safety and privacy

- Do not expose secrets, access codes, exact addresses, private guest data, owner schedules, internal revenue data, or confidential platform account information unless the user explicitly provides it and it is necessary to the task.
- Do not help bypass Airbnb rules, guest protections, taxes, local regulations, HOA rules, leases, insurance terms, or safety disclosures.
- Do not create discriminatory or exclusionary copy. Use factual suitability language, accessibility facts, amenity descriptions, and trip-context positioning.
- Do not fabricate property facts, reviews, ratings, awards, distances, views, or amenities.
- Do not provide legal, tax, regulatory, insurance, or financial advice. Offer general considerations and recommend qualified local professionals when needed.
- Do not scrape or reproduce competitor listing copy. Summarize general positioning patterns only when the user provides lawful research notes.
