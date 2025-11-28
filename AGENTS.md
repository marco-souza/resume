# AGENTS.md

Guidelines for working on this project.

**Related Thread:** https://ampcode.com/threads/T-d2609474-e9d2-4718-a108-10bde07d0209

## Project Structure

- `RESUME.md` - Main resume with rich formatting (emojis, icons, HTML links) for web/GitHub display
- `RESUME_PDF.md` - PDF-safe version with plain text formatting for PDF conversion
- `resume.yml` - Structured resume data (skills organized by category)

## Resume Guidelines

### Content

- **Use concrete metrics and outcomes**, not generic descriptions
- **Lead with impact**: quantify improvements (% reduction, time saved, scale achieved)
- **Include dates** for all positions in `MMM/YYYY – MMM/YYYY` format
- **Highlight team leadership** if applicable (number of direct reports, collaboration)
- **Links**: Use company names with links to official websites
- **PodCodar**: Keep as community impact differentiator

### Formatting Rules

#### RESUME.md (Web Version)

- Use emojis in header (permitted)
- Use HTML for contact section with images/badges
- Use skillicons.dev for technology icons
- Bold key achievements with `**text**`
- Markdown links: `[text](url)`

#### RESUME_PDF.md (PDF Version)

- NO emojis
- NO external images
- Plain markdown only
- **Bold** for emphasis
- Plain text links (no markdown syntax)
- Contact section as simple list with labels
- All skills listed as plain text in organized sections

### Contact Information

- Email: ma.souza.junior@gmail.com
- Codementor: codementor.io/@masjr
- LinkedIn: linkedin.com/in/masouzajunior
- StackOverflow: stackoverflow.com/users/7988674/marco-antônio
- GitHub: github.com/marco-souza

## Git Workflow

- Commit messages: use `fea:`, `fix:`, `style:` prefixes
- Always commit both markdown files when updating content
- Push after each commit
- Example: `feat: add achievement metrics to Amazon experience`

## Key Achievements to Highlight

- MongoDB: CI/CD pipeline 15→3 min, Next.js migration, E2E testing
- Paradigm: 6 direct reports, memory 80→15MB, deploy 4h→26min, API metrics
- Amazon: FBA compliance automation, 2 micro frontends at scale (millions of visits)
- Able & SmarttBot: Team leadership, tech migrations, PWA implementation

## Metrics Format

When documenting improvements:

- Time: `X → Y minutes/hours`
- Memory/Size: `XMB → YMB`
- Performance: `X% improvement` or `X→Y metric`
- Scale: `X+ connections`, `X+ requests/min`
- Latency: `<Xms`

## Before Converting to PDF

1. Remove all emojis from content
2. Remove all external image links
3. Convert all links to plain text format
4. Test formatting in markdown viewer
5. Ensure no HTML tags remain
