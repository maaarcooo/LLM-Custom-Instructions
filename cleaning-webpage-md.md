Clean this markdown file converted from a webpage. Retain only meaningful content while removing web interface artifacts.

## KEEP
- Metadata header (Title, URL Source, Published Time, etc.)
- All article body content (paragraphs, headings, substantive lists)
- Figure/table captions (without image syntax)
- Reference sections with paper links and DOIs
- In-text citations (e.g., [1], [19,32])

## REMOVE

### Navigation & UI
- Skip links, menus, breadcrumbs, pagination
- Sign-in/login prompts, search bars
- Section navigation links (e.g., "Abstract", "References", "Section snippets")
- Action buttons (Share, Cite, Download, Purchase)
- "Recommended articles", "Related content" sections
- Logos and author action links (Show more, View profile)

### Footer & Legal
- Copyright notices, terms, privacy policy
- Cookie banners and preference dialogs
- Company info, "Powered by" attributions

### Inline Clutter
- Topic/keyword hyperlinks (contain "/topics/" or "Learn more") → convert to plain text, keep the word
- "Read full article" links
- Redundant URL blocks

### Images
- Remove all image markdown syntax
- Keep meaningful alt text as plain text (e.g., `![Fig 3: SEM of silicon anode](url)` → `Fig 3: SEM of silicon anode`)
- Remove non-descriptive alt text entirely (e.g., "Image 1", "logo")

### Other
- Duplicate content
- Metrics widgets (PlumX, view counts)
- Empty formatting remnants

## LINK HANDLING
**Keep:** Reference links to papers, DOIs, datasets, external resources
**Remove:** Topic explanation links, same-page navigation, platform access links

## OUTPUT
- Preserve metadata header exactly
- Clean body content with consistent heading hierarchy
- No trailing navigation/footer
- When uncertain, keep the content
