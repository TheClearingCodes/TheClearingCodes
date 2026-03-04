# Contributing to The Clearing Codes

Thank you for your interest in contributing to The Clearing Codes! This open-source project welcomes contributions that help make this clearing modality more accessible, complete, and useful for everyone.

---

## Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Before You Contribute](#before-you-contribute)
- [Contribution Guidelines](#contribution-guidelines)
- [Style Guide](#style-guide)
- [Document Structure](#document-structure)
- [Submitting Contributions](#submitting-contributions)
- [Review Process](#review-process)
- [Translation Contributions](#translation-contributions)
- [Code of Conduct](#code-of-conduct)

---

## Ways to Contribute

### Documentation Improvements
- **Fix typos, grammar, or clarity issues** — Help make the content more readable
- **Add examples** — Provide real-world clearing scripts or use cases
- **Expand existing content** — Deepen explanations or add missing details
- **Cross-references** — Add helpful links between related documents

### New Content
- **New programs** — Multi-session clearing sequences for specific life issues
- **New clearing scripts** — Focused clearing language for specific topics
- **Case studies** — Real clearing experiences (anonymized)
- **Integration guides** — How to use Clearing Codes with other modalities

### Website & Tools
- **UI/UX improvements** — Enhance website usability or design
- **New tools** — Interactive clearing tools, calculators, or visualizations
- **Bug fixes** — Fix broken links, layout issues, or JavaScript errors
- **Accessibility improvements** — Make the site more accessible to all users

### Data & Charts
- **New clearing items** — Add items to category charts
- **Chart organization** — Improve categorization or structure
- **Validation** — Verify accuracy of existing items

### Translations
- **Translate documents** — Help make the content available in other languages
- See [TRANSLATING.md](TRANSLATING.md) for translation-specific guidelines

---

## Before You Contribute

### Understand the License
All Clearing Codes files are licensed under [Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0)](https://creativecommons.org/licenses/by-nd/4.0/).

By contributing, you agree that:
- Your contributions become part of The Clearing Codes and are licensed under the same CC BY-ND 4.0 terms
- You have the right to submit the contribution
- You understand that contributions are made to the original work under the author's authority
- Only the author may approve and merge contributions into the project

### Respect the Core Principles
The Clearing Codes modality is built on specific core principles (see [AboutTheClearingCodes.md](AboutTheClearingCodes.md)):
1. **Simplicity** — Keep content clear and accessible
2. **Effectiveness** — Focus on what works
3. **Neutrality** — Use inclusive, non-denominational language
4. **Openness** — Maintain the open-source ethos
5. **Safety** — Include appropriate guidance and disclaimers

### Know the Structure
Familiarize yourself with:
- [INDEX.md](INDEX.md) — Master navigation and organization
- [ClearingAndActivationProtocol.md](ClearingAndActivationProtocol.md) — The technical architecture
- The Clearing Codes Guide — The comprehensive manual *(available at [TheClearingCodes.com](https://theclearingcodes.com))*
- Existing programs in the `Programs/` directory
- The website at [theclearingcodes.com](https://theclearingcodes.com)

---

## Contribution Guidelines

### Documentation

#### Markdown Files
- Use standard Markdown syntax
- Keep lines under 120 characters when possible (except code blocks or tables)
- Use headers hierarchically (don't skip levels)
- Include a clear document title at the top (`# Document Title`)
- Add horizontal rules (`---`) between major sections
- Use relative links for internal references

#### Tone & Voice
- **Respectful** — Honor the user's experience and autonomy
- **Clear** — Avoid jargon; define specialized terms
- **Neutral** — Use inclusive, non-denominational spiritual language
- **Practical** — Focus on actionable guidance
- **Empowering** — Frame from sovereignty, not dependency

#### Language to Use
✅ Good:
- "Center yourself" or "Take a breath"
- "Highest good"
- "Life-Affirming blueprint"
- "For those who resonate with..."
- "You may experience..."

❌ Avoid:
- Prescriptive religious language ("You must connect with Source")
- Absolute claims ("This will cure...")
- Fear-based language ("If you don't do this...")
- Overly complex terminology without explanation

#### Disclaimers
Always include appropriate disclaimers when discussing:
- Health conditions — "Not a replacement for medical care"
- Mental health — "Seek professional support if..."
- Crisis situations — "Call emergency services if..."

### Website & Code

#### HTML/CSS
- Follow existing design patterns and color schemes
- Maintain mobile responsiveness
- Use CSS variables defined in `:root`
- Keep inline styles minimal (prefer classes)
- Test across common browsers (Chrome, Firefox, Safari, Edge)

#### JavaScript
- Use vanilla JavaScript (no frameworks required for current tools)
- Keep code readable with clear variable names
- Add comments for complex logic
- Use `localStorage` for client-side persistence (not cookies)
- Handle errors gracefully with user-friendly messages

#### File Organization
- Charts/category markdown files go in `Charts/`
- Multi-session programs go in `Programs/`
- Keep the root directory organized

### Data & Charts

#### Adding Clearing Items
Items should be:
- **Specific** — "Financial scarcity programming" not "money stuff"
- **Clear** — Easily understood without explanation
- **Non-redundant** — Check if similar item already exists
- **Appropriately categorized** — Place in correct category file

#### Format
Follow this format in both markdown files and `charts-data.js`:
```markdown
- Item name
- Another item name (subcategory if needed)
- Third item name
```

In `charts-data.js`:
```javascript
items: [
    'Item name',
    'Another item name',
    'Third item name'
]
```

---

## Style Guide

### Headings
```markdown
# H1 — Document Title (only one per document)
## H2 — Major Section
### H3 — Subsection
#### H4 — Sub-subsection
```

### Lists
**Unordered:**
```markdown
- First item
- Second item
  - Sub-item (indent with 2 spaces)
```

**Ordered:**
```markdown
1. First step
2. Second step
3. Third step
```

### Links
**Internal (relative):**
```markdown
[TheClearingCommand.md](TheClearingCommand.md)
[Glossary](Glossary.md#specific-term)
```

**External:**
```markdown
[Creative Commons](https://creativecommons.org/licenses/by-nd/4.0/)
```

### Emphasis
- **Bold** for important terms or emphasis: `**bold**`
- *Italic* for subtle emphasis or introducing terms: `*italic*`
- `Code` for filenames, commands, or technical terms: `` `code` ``

### Blockquotes
Use `>` for clearing scripts or quoted commands:
```markdown
> "Loops & Lines, Blocks & Binds. Release, restore, reclaim, refine."
```

### Tables
```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data     | Data     | Data     |
```

---

## Document Structure

### Standard Document Template

```markdown
# Document Title

Brief introduction explaining what this document covers and who it's for.

---

## Section 1: Main Content

Content here.

### Subsection

More specific content.

---

## Section 2: Next Topic

Continue the document.

---

## Related Resources

- [RelatedDoc1.md](RelatedDoc1.md) — Description
- [RelatedDoc2.md](RelatedDoc2.md) — Description

---

**The Clearing Codes** — Open Source • Free to Use • Free to Share

Licensed under CC BY-ND 4.0
```

### Program Document Template

See existing programs in `Programs/` directory for structure:
1. Title and introduction
2."Why a Targeted Protocol?" section
3."Relevant Categories" section with links
4. 5-session sequence with consistent format
5. Integration notes after each session
6. Related resources
7. Footer

---

## Submitting Contributions

### Via GitHub (Preferred)

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/your-feature-name`
3. **Make your changes** following these guidelines
4. **Test your changes**
5. **Commit with clear messages**: `git commit -m "Add: Brief description of change"`
6. **Push to your fork**: `git push origin feature/your-feature-name`
7. **Submit a Pull Request** with:
   - Clear title
   - Description of what changed and why
   - Any testing you performed
   - Reference to related issues if applicable

### Via Email

If you don't use GitHub:
1. Make your changes to a copy of the relevant file(s)
2. Send to: info@theclearingcodes.com
3. Include:
   - File name(s) changed
   - Description of changes
   - Your name (for attribution)

---

## Review Process

### What to Expect

1. **Acknowledgment** — We'll acknowledge receipt within 1-3 days
2. **Review** — Contributions are reviewed for:
   - Alignment with core principles
   - Accuracy of content
   - Consistency with existing style
   - Technical correctness (for code)
3. **Feedback** — We may request changes or clarifications
4. **Acceptance** — Once approved, contributions are merged
5. **Attribution** — Contributors are credited in CHANGELOG.md

### Timeline

- **Small fixes** (typos, links): 1-3 days
- **New content** (programs, guides): 1-2 weeks
- **Major features** (new tools, large restructuring): 2-4 weeks

### Rejection Reasons

Contributions may be declined if they:
- Contradict core principles
- Use prescriptive religious language
- Make unsubstantiated medical claims
- Are redundant with existing content
- Significantly increase complexity without clear benefit
- Don't follow the style guide after requested revisions

---

## Translation Contributions

Translations are highly valued! See [TRANSLATING.md](TRANSLATING.md) for:
- Which files to prioritize
- Translation guidelines
- How to submit translations
- Ongoing translation maintenance

---

## Code of Conduct

### Our Standards

**We are committed to:**
- Respectful, inclusive, and welcoming interactions
- Constructive feedback and discussion
- Honoring diverse perspectives and approaches
- Supporting contributors of all experience levels

**Unacceptable behavior:**
- Harassment, discrimination, or personal attacks
- Trolling, inflammatory comments, or deliberate disruption
- Sharing others' private information without consent
- Behavior that would be inappropriate in a professional setting

### Enforcement

Project maintainers will:
1. Warn contributors about inappropriate behavior
2. Temporarily or permanently ban repeat offenders
3. Remove contributions that violate the code of conduct

Report violations to: info@theclearingcodes.com

---

## Questions?

- Check the Troubleshooting guide for common questions
- Review [INDEX.md](INDEX.md) for navigation help
- Read the Getting Started guide for comprehensive guidance (available at [TheClearingCodes.com](https://theclearingcodes.com))

For contribution-specific questions:
- Open a GitHub issue
- Email: info@theclearingcodes.com

---

**Thank you for contributing to The Clearing Codes!**

Every contribution — no matter how small — helps make this modality more accessible and effective for everyone.

---

**The Clearing Codes** — Open Source • Free to Use • Free to Share

Licensed under CC BY-ND 4.0
