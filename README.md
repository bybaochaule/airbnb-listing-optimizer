# Airbnb Listing Optimizer

## Overview

The Airbnb Listing Optimizer skill helps an agent audit, rewrite, and improve Airbnb and short-term-rental listings using truthful, guest-centered, conversion-aware copy. It is designed for listing titles, descriptions, amenity positioning, photo-story guidance, guest-fit messaging, and prioritized improvement plans.

The skill avoids unsafe shortcuts: it does not create fake reviews, fabricate amenities, guarantee search rankings, scrape competitors, evade platform rules, or provide legal, tax, permit, or regulatory advice.

## When to use

Use this skill when a host, property manager, copywriter, or marketplace operator asks for:

- Airbnb listing optimization
- Short-term-rental listing audits
- Title and description rewrites
- Guest-facing benefit copy
- Photo sequencing and caption recommendations
- Amenity and differentiator positioning
- Review-informed listing improvements
- Conversion-focused listing checklists

## Contents

- `SKILL.md`: Agent-facing instructions, trigger description, boundaries, workflow, output format, and safety rules.
- `README.md`: Human-readable package overview.
- `agents/openai.yaml`: OpenAI metadata and invocation policy.
- `references/style-guide.md`: Copywriting rules, audit framework, examples, and edge cases.
- `assets/listing-brief-template.md`: Reusable intake template for property details and listing goals.
- `assets/.gitkeep`: Retains the assets directory.
- `scripts/example_helper.py`: Safe deterministic helper that checks listing text for basic copy-quality signals.

## Package structure

```text
airbnb-listing-optimizer/
|-- SKILL.md
|-- README.md
|-- agents/
|   `-- openai.yaml
|-- assets/
|   |-- .gitkeep
|   `-- listing-brief-template.md
|-- references/
|   `-- style-guide.md
`-- scripts/
    `-- example_helper.py
```

## Example prompts

```text
Optimize my Airbnb listing. Here are the property details, current title, description, amenities, and the guest complaints I want to address.
```

```text
Audit this short-term-rental listing for clarity, trust, conversion, photo order, and missing proof points. Give me a prioritized fix list.
```

```text
Write 10 Airbnb title options and a stronger first paragraph for a two-bedroom cabin near hiking trails with a hot tub and pet-friendly policy.
```

## Recommended inputs

Provide as many as are available:

- Property type, general location, layout, bedrooms, bathrooms, beds, and maximum guests.
- Standout amenities and proof points.
- Nearby attractions and logistics.
- Current listing copy, title, house rules, and photo list.
- Guest reviews, common questions, or conversion concerns.
- Desired tone and target trip contexts.

## Output style

The skill defaults to a structured response with assumptions, positioning, audit notes, title options, revised copy, amenity bullets, photo guidance, accuracy notes, and next steps. It can also produce only the requested copy when the user asks for a narrow deliverable.
