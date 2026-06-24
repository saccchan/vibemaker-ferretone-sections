# AI Context

## Purpose

This repository contains static HTML section fragments for a VibeMaker landing page intended to be pasted into ferret one CMS. Each section is a standalone HTML fragment with inline CSS.

The preview page, `preview_all_sections.html`, loads each fragment in order by iframe so reviewers can check the full page flow without a CMS environment.

## Audience

The landing page is for non-engineers who want to use AI tools through text, Markdown, prompts, and Cursor. The tone should be professional, energetic, and accessible.

## Design Direction

- Brand base: TANREN red, dark backgrounds, strong contrast, clean Japanese typography.
- Primary font: `Noto Sans JP`, with Japanese fallback fonts.
- Avoid generic purple AI gradients, overly decorative layouts, and copy that targets expert engineers.
- Keep each section CMS-friendly: inline CSS, no build pipeline, no framework dependency.

## File Roles

- `index.html`: GitHub Pages entry point. Redirects to the full preview.
- `preview_all_sections.html`: Review page that loads all section fragments.
- `01_hero.html`: Hero section with generated AI director image.
- `02_challenges.html`: Problem and challenge framing.
- `03_what_is_vibe.html`: "TEXT is KING" explanation and AI-readable text/Markdown/context/chain concept.
- `04_outcomes.html`: Outcome image section.
- `05_curriculum.html`: Curriculum content.
- `06_target_audience.html`: Target audience section.
- `07_level_check.html`: Level check section.
- `08_plans.html`: Individual and corporate plan details.
- `09_continuity.html`: Continuity/support section.
- `10_instructor.html`: Instructor profile.
- `11_faq.html`: FAQ.
- `12_final_cta.html`: Final call to action.
- `assets/hero-ai-director.png`: Generated raster hero visual for `01_hero.html`.

## Editing Notes

- Preserve inline CSS because the final target is CMS paste-in.
- Keep fragments independent; do not rely on global CSS from another section.
- When adding images, prefer stable relative paths under `assets/` for GitHub Pages previews.
- If a section uses external ferret-one image URLs, verify they return `200 OK`.
- After edits, open `preview_all_sections.html` and verify desktop and mobile layouts.

## Current Share Workflow

Use GitHub Pages for a stable visual preview and the GitHub repository URL for code review or AI-assisted review.
