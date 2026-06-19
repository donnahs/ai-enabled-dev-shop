# NOVA Dev Shop OS

Internal AI-enabled software build system for Matt and NOVA.

This is not primarily a client agency website. It is the shared command centre where Matt and NOVA capture software ideas, scope the smallest useful version, generate build prompts, track the queue, and package finished builds.

## Files

- `site/index.html` - internal Dev Shop OS dashboard
- `site/dev-shop-os.html` - same internal dashboard source copy
- `site/client-offer.html` - optional external/client-facing Perth Lead Rescue System offer page
- `site/intake.html` - optional static client/project brief generator
- `reports/build-check.txt` - latest verification output
- `ai-enabled-dev-shop.zip` - hosting package

## What the internal dashboard does

- Capture software build ideas
- Assign bucket, type, status and next action
- Store builds in browser localStorage
- Generate a NOVA build prompt for each project
- Track Cards / Kanban / Definition of Done
- Export/import JSON backup
- Download build prompt as text

## Build lanes

- Apps and SaaS MVPs
- Static sites and product pages
- AI automations and agents
- Dashboards and internal tools
- Game prototypes
- Pokemon / TCG tools
- Hydroponics and electronics tools
- Embedded / CAN bus / MCU firmware tools
- Career / portfolio assets

## Hosting

Upload the contents of `site/` to any static HTML host:

- Netlify drag and drop
- Vercel static project
- GitHub Pages
- cPanel public_html

No build step required.

## Internal rule

Every build should answer:

```text
What can Matt and NOVA finish, launch, sell, or test this week?
```

Definition of done:

1. Project has a clear user and pain.
2. Smallest useful version is scoped.
3. Files are created in a project folder.
4. Code or page runs locally.
5. HTTP/test/smoke check passes.
6. README or handover notes exist.
7. ZIP/package or public URL is ready.
8. Portfolio/project tracker updated.
