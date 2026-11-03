# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Players of Arena Breakout Infinite, a mixed audience in equal weight:

- **Casual players** who arrive from a recommendation, Discord, or a video and just want to download and start using it fast.
- **Experienced players** who already use sites that compare mystery-cargo sounds one by one and want that comparison automated.

The job: when they drag the merchant's mystery cargo, find out which items it might contain before deciding what to do with it.

## Product Purpose

Som Scanner is a free Windows program (10/11, 64-bit) that listens to the PC's audio output, recognizes the sound group of the merchant's mystery cargo, and lists the possible items from rarest to most common. This repository is its download landing page. Success means a visitor understands what it does, trusts it enough to install it, and gets through the download and Windows SmartScreen warning.

## Positioning

- **Automatic and instant:** it listens on its own and gives a guess in under a second, with no manual comparison on a website.
- **Learns from the user:** the "Errou, era outro" button teaches it the right sound, so it gets more accurate with use.
- **Free and hands-off:** it only listens to the audio that already plays on the PC, and it neither reads nor changes any game file.

## Operating Context

The program runs next to the game, optionally always on top. Flow: install with `SomScanner-Setup.exe`, click "Iniciar escuta", then drag the cargo at the merchant. The user can filter by cargo size (1x1 to 3x2) and cargo type, and adjust sensitivity. Item rarity uses the game's six tiers: Common, Uncommon, Rare, Epic, Legendary, Mythic. Captures from the default output device (headphones or speakers).

## Capabilities and Constraints

- The landing page is a single static `index.html` with no build step. The installer comes from GitHub Releases (`releases/latest/download/SomScanner-Setup.exe`).
- **The page must be bilingual: Portuguese (pt-BR) and English, with a visible control for switching language.**
- Unsigned installer: the page must explain the "O Windows protegeu o computador" warning and how to get past it.
- Open: whether the program itself also ships in English.

## Brand Commitments

- Name: Som Scanner (written "SOM SCANNER" in the current header). App icon: `icone.png`.
- Voice: informal, direct Brazilian Portuguese that speaks to the player as "você".
- Visual reference chosen by the user (2026-11-03): the category-standard game-companion page, with the tactical style of the official Arena Breakout Infinite site as the quality bar. Style only: no marks, logos, or game art.
- Independent fan project: the page currently states it has no affiliation with the game's developer or publisher, that all trademarks belong to their owners, and that the program includes no game files. Use is at the player's own risk.

## Evidence on Hand

- `print-recorte.png`: a screenshot of the program (v1.1.0) recognizing a sound.
- `icone.png`, `favicon.png`.
- Version 1.1.0 (latest GitHub release, 2026-11-03).
- No testimonials, download counts, videos, or accuracy metrics exist. Do not make them up.

## Product Principles

1. Get from arrival to download fast. The casual player shouldn't have to read much to act.
2. Earn trust honestly: be explicit that it doesn't touch the game, explain the SmartScreen warning, and keep the fan disclaimer.
3. Show the real product (the screenshot, the rarity tiers) rather than describing it abstractly.
4. Speak the player's language, both literally (PT/EN) and in the game's own terms.
