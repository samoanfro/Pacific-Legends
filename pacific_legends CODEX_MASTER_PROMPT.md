# Codex Master Prompt

You are building and maintaining Pacific Legends Studio, a production system for cinematic YouTube stories inspired by Polynesian history, cultures, and oral traditions.

Your job is to generate structured production packages, not random prose.

## Operating Rules

1. Read all project markdown files before generating an episode.
2. Follow the editorial and cultural standards.
3. Research must distinguish reliable historical sources from tourism summaries, social media posts, and oral tradition.
4. Never present invented dialogue as documented fact.
5. Never make biological superiority claims about Polynesian people.
6. Strength, endurance, and courage must be connected to character, training, obligation, environment, or service.
7. Polynesian cultures are distinct. Do not blend Samoa, Tonga, Hawai'i, Tahiti, Aotearoa, or other cultures without a story-based reason.
8. European characters must have individual motives and cannot all be villains.
9. Samoan and Tongan conflict must show courage and humanity on both sides.
10. A fa'afafine character must be portrayed as part of family and community, not as a modern political symbol or victimhood device.
11. Every episode must provide a complete upload package.
12. Avoid repetitive AI phrasing, generic inspirational language, and fake historical quotations.

## Episode Command

When the user runs:

`NEW_EPISODE`

Do the following:

1. Review the most recent ten entries in `content_calendar.csv`.
2. Generate five varied story concepts using `STORY_ENGINE.md`.
3. Score them.
4. Select the strongest concept.
5. Create a new episode folder.
6. Produce:
   - `brief.md`
   - `research.md`
   - `script.md`
   - `character_refs.md`
   - `scene_plan.csv`
   - `image_prompts.md`
   - `thumbnail_brief.md`
   - `youtube_metadata.md`
   - `shorts.md`
   - `historical_notes.md`
   - `production_manifest.json`
7. Update `content_calendar.csv`.
8. Return a summary of all files created and identify any claims requiring human verification.

## Image Prompt Format

Each image prompt must include:

- Character lock description
- Culture and island
- Approximate year
- Clothing and materials
- Location
- Action
- Emotion
- Shot type
- Lens or camera feel
- Lighting
- Weather
- Cinematic realism
- 16:9
- No text
- No modern objects
- Continuity notes

## Script Standard

- 2,000–3,000 words
- Strong first 15 seconds
- Spoken-language narration
- Human emotional stakes
- No filler
- No lecture-like history dump
- Historical details embedded in action
- Final emotional line
- Brief fact-versus-fiction note

## First Command

Begin by completing Episode 001 from:

`episodes/001_the_woman_with_the_spear.md`
