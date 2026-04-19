# Translation Guidelines

Welcome to The Clearing Codes translation project! This guide will help you translate the documentation to make this clearing modality accessible to speakers of other languages.

---

## Table of Contents

- [Why Translation Matters](#why-translation-matters)
- [Before You Begin](#before-you-begin)
- [Translation Priorities](#translation-priorities)
- [Translation Guidelines](#translation-guidelines)
- [File Organization](#file-organization)
- [Submitting Translations](#submitting-translations)
- [Ongoing Maintenance](#ongoing-maintenance)
- [Translation Tools & Resources](#translation-tools--resources)

---

## Why Translation Matters

Energy knows no language barriers. By translating The Clearing Codes, you help people worldwide access this powerful clearing modality in their native language. Translation makes healing accessible.

---

## Before You Begin

### 1. Language Proficiency
You should be:
- **Fluent** in both English and the target language
- Comfortable with **specialized terminology** (spiritual/energetic concepts)
- Able to **write clearly** in the target language

### 2. Understanding the Content
Before translating:
- Read [AboutTheClearingCodes.md](AboutTheClearingCodes.md)
- Read the Getting Started guide (available at [TheClearingCodes.com](https://theclearingcodes.com))
- Understand [ClearingAndActivationProtocol.md](ClearingAndActivationProtocol.md)
- Try using the clearing process yourself

### 3. Check for Existing Translations
Check if your language already has translations in progress to avoid duplication.

### 4. Contact Us
Before starting a major translation project, reach out to coordinate:
- GitHub: Open an issue labeled "Translation: [Language]"
- Email: info@theclearingcodes.com

---

## Translation Priorities

Translate in this order for maximum impact:

### Priority 1: Core Documents (Start Here)
1. **AboutTheClearingCodes.md** — Introduction
2. **TheClearingCommand.md** — The command reference
3. **QuickReferenceCard.md** — Quick reference
4. **TheClearingCodesProcess.md** — Complete process

### Priority 2: Essential Guides
5. **ClearingAndActivationProtocol.md** — Technical protocol
7. **Glossary.md** — Term definitions

### Priority 3: Programs
8. **Programs/** directory — 10 issue-specific programs
    - Start with AnxietyAndOverwhelmProgram.md
    - Then RelationshipHealingProgram.md
    - Continue as needed

### Priority 4: Reference & Activations
9. **ActivationScripts.md** — Activation library
10. **ActivationsAndPositiveFrequencies.md** — Positive frequencies

### Priority 5: Charts & Categories
15. **Charts/** directory — 23 category files
    - Translate category names first
    - Then translate individual items

### Priority 6: Website
16. Website at [theclearingcodes.com](https://theclearingcodes.com) — contact for website translation coordination

---

## Translation Guidelines

### Preserve Meaning, Not Words

Translate for **meaning and cultural appropriateness**, not word-for-word:

**Good:** Adapt idioms and metaphors to the target culture
**Bad:** Literal translation that sounds unnatural

**Example:**
- English: "Clear the deck"
- Spanish: "Hacer borrón y cuenta nueva" (cultural equivalent)
- Not: "Limpiar la cubierta" (literal, awkward)

### Maintain Tone & Voice

The Clearing Codes uses:
- **Simple, accessible language** — Avoid unnecessary complexity
- **Respectful, empowering tone** — Honor the user's sovereignty
- **Neutral spiritual language** — Inclusive, non-denominational
- **Direct, actionable guidance** — Practical, not theoretical

Match this tone in your translation.

### The Clearing Command

**Special consideration**: The core clearing command uses specific paired words:

> "Loops & Lines, Blocks & Binds, Vows & Verdicts, Notions & Nines.
> Patterns & Programs, Breaks & Bytes, Roots & Remnants, Ridges & Rites.
> Release, restore, reclaim, refine; all levels and layers, all space and all time."

#### Translation Approaches:

**Option 1: Translate for Meaning**
Translate each word to its closest equivalent in the target language, preserving the general meaning even if alliteration or rhythm is lost.

**Option 2: Adapt for Cultural Resonance**
Find culturally appropriate terms that carry similar meaning and, if possible, similar phonetic qualities (alliteration, rhythm).

**Option 3: Hybrid Approach (Recommended)**
- Translate the **action words** ("Release, restore, reclaim, refine") clearly for meaning
- Translate the **16 clearing words** for meaning, adapting where cultural equivalents exist
- Translate the **closing phrase** ("all levels and layers, all space and all time") directly

**Important Notes:**
- The Protocol responds to **intention**, not specific words
- Translation doesn't diminish effectiveness
- Include a translator's note explaining your approach
- Consider consulting native speakers for cultural appropriateness

### Specialized Terms

#### Key Terms to Translate Consistently

Create a **glossary** for your language and use terms consistently:

| English Term | Translation Approach |
|--------------|---------------------|
| Clearing | Direct equivalent for "cleansing/purifying" |
| Activation | Direct equivalent for "activating/initiating" |
| Protocol | Technical term may stay as "protocol" or translate to "procedure/system" |
| Field | Energetic field — may need explanation |
| Layer | Level/layer of being |
| Sovereign/Sovereignty | Individual authority over one's own field |
| Life-Affirming Blueprint | Original optimal design/template |
| Integration | The process of absorbing/incorporating changes |

#### Terms That May Stay English
Some terms might stay in English if no good equivalent exists:
- Technical abbreviations
- Trademarked terms
- Terms widely understood internationally

#### Terms to Explain
Some concepts may need brief explanation if unfamiliar in target culture:
- Chakras
- Frequency
- Multidimensional
- Energetic field

### Formatting

#### Preserve Structure
- Keep all markdown formatting (`# ## ###` for headers, `**bold**`, `*italic*`, etc.)
- Maintain bullet points and numbering
- Keep table structures intact
- Preserve line breaks and spacing

#### Links
- Keep all internal links in English (they reference English filenames)
- Add a note in your language: "(English document)" or equivalent
- Example: `[TheClearingCommand.md](TheClearingCommand.md) *(documento en inglés)*`

#### File Names
- Translated files get a language code: `AboutTheClearingCodes_ES.md` (Spanish)
- Use ISO 639-1 codes: `_ES`, `_FR`, `_DE`, `_PT`, `_IT`, `_JA`, `_ZH`, etc.
- Keep original English filename, add code before `.md`

### Scripts & Commands

When translating clearing scripts:

1. **Preserve the structure** — Step 1, Step 2, etc.
2. **Translate instructions** clearly
3. **Adapt the spoken commands** for natural flow in target language
4. **Include optional variations** if culturally appropriate
5. **Test readability** — Read it aloud to ensure it sounds natural

### Cultural Sensitivity

#### Religious/Spiritual Terms
The Clearing Codes intentionally uses neutral language. Maintain this:
- Avoid denominational terms unless offering them as options
- Use culturally appropriate equivalents for concepts like "highest good," "divine," "universal"
- Respect that different cultures relate to spirituality differently

#### Gender & Pronouns
- Follow target language grammar for gendered terms
- Use inclusive language where possible
- Be mindful of cultural norms around gender in spiritual contexts

#### Examples & Metaphors
- Adapt examples to target culture when needed
- If an example is culturally specific (e.g., American holidays), consider finding an equivalent or using a more universal example

---

## File Organization

### Directory Structure

Create language-specific subdirectories:

```
/Clearing Codes/
├── AboutTheClearingCodes.md (English)
├── AboutTheClearingCodes_ES.md (Spanish)
├── AboutTheClearingCodes_FR.md (French)
├── Translations/
│   ├── ES/
│   │   ├── AboutTheClearingCodes_ES.md
│   │   ├── TheClearingCommand_ES.md
│   │   ├── Glossary_ES.md
│   │   └── ...
│   ├── FR/
│   │   └── ...
│   └── [Other languages]/
```

**OR** (if preferred):
Keep translated files in root with language codes.

### README in Your Language

Create a `README_[CODE].md` in your language explaining:
- What The Clearing Codes are
- Which files are translated
- Translation status
- How to use the translated materials

---

## Submitting Translations

### Via GitHub (Preferred)

1. **Fork the repository**
2. **Create a translation branch**: `git checkout -b translation/[language-code]`
3. **Add translated files** with proper naming
4. **Include a translation note** at the top of each file:
   ```markdown
   # [Document Title in Target Language]
   
   *Translated into [Language] by [Your Name]
   Original: [English filename]
   Last updated: [Date]*
   
   ---
   ```
5. **Submit a Pull Request** with:
   - Title: "Translation: [Language Name] - [Files Included]"
   - Description of what was translated
   - Your translation approach for the clearing command
   - Any cultural adaptations made

### Via Email

Send translated files to: info@theclearingcodes.com

Include:
- Language and language code
- Your name (for attribution)
- Which files are included
- Translation notes

---

## Ongoing Maintenance

### As Content Updates

The English content will continue to evolve. To maintain translations:

1. **Watch for changes** — Star the GitHub repo for notifications
2. **Check VERSION.md** — See what changed in each version
3. **Update translations** accordingly
4. **Mark translation version** — Note which English version your translation matches

### Translation Versioning

At the top of each translated file, note:
```markdown
*Translation of English version 1.0 (March 2026)
Translated by [Name]
Last updated: [Date]*
```

When English content updates:
```markdown
*Translation of English version 1.0 (March 2026)
⚠️ English content updated to version 1.1 — translation pending update
Translated by [Name]
Last updated: [Date]*
```

---

## Translation Tools & Resources

### Recommended Tools
- **CAT Tools** (Computer-Assisted Translation): MemoQ, Trados, OmegaT (free)
- **Glossary Management**: Maintain a spreadsheet of term translations
- **Quality Check**: Grammarly, LanguageTool, or native language checkers
- **Collaboration**: Google Docs for team translation projects

### Resources
- **[Glossary.md](Glossary.md)** — Terms to translate consistently
- **Style guides** in your language (AP, MLA, or language-specific standards)
- **Cultural consultants** — If possible, have native speakers review

### Testing Translations
Before submitting:
1. **Read it aloud** — Does it sound natural?
2. **Have someone else read it** — Is it clear?
3. **Test the clearing process** in your language — Does it work?
4. **Check all links** — Do they point to correct files?

---

## Questions?

- **General questions**: See [CONTRIBUTING.md](CONTRIBUTING.md)
- **Translation-specific questions**: 
  - Open a GitHub issue tagged "Translation"
  - Email: info@theclearingcodes.com

---

## Current Translation Status

*(To be updated as translations are completed)*

| Language | Code | Progress | Translator(s) | Status |
|----------|------|----------|---------------|--------|
| Spanish | ES | 0% | — | Not started |
| French | FR | 0% | — | Not started |
| German | DE | 0% | — | Not started |
| Portuguese | PT | 0% | — | Not started |
| Italian | IT | 0% | — | Not started |
| Japanese | JA | 0% | — | Not started |
| Chinese (Simplified) | ZH | 0% | — | Not started |
| Korean | KO | 0% | — | Not started |
| Russian | RU | 0% | — | Not started |
| Arabic | AR | 0% | — | Not started |
| Hindi | HI | 0% | — | Not started |

*Want to start a translation? Contact us or open a GitHub issue!*

---

**Thank you for helping make The Clearing Codes accessible to more people worldwide!**

Every translation is a gift to the global community.

---

**The Clearing Codes** — Open Source • Free to Use • Free to Share

Licensed under CC BY-ND 4.0
