# 02 — Language Identification

Filtering Tamazight text from multilingual datasets using language ID models.

## Contents

| File | Description |
|------|-------------|
| `glotlid_filter_tamazight.ipynb` | Filters Tamazight sentences using GlotLID (300-language ID model) |
| `meta_mms_lid_tamazight.ipynb` | Filters Tamazight using Meta's MMS (Massively Multilingual Speech) LID |

## Method

Both notebooks apply a two-step approach:
1. Run a language identification model over raw/crawled text
2. Keep only sentences classified as Tamazight (`kab`) with high confidence

## Models

- **GlotLID**: Open-source LID covering 300+ languages
- **MMS LID**: Meta's MMS model, strong for African/under-represented languages
