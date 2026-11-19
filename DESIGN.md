# DESIGN.md - Work of Human Hands

## Identity
A reading site for one book: Rev. Anthony Cekada's "Work of Human Hands: A
Theological Critique of the Mass of Paul VI" (2nd ed., SGG Resources, 2015).
The design should feel like a well-set missal crossed with a modern reference
edition: quiet pages, strong typography, nothing that competes with 400 pages
of text.

## Audience
Readers who came for the book's argument: traditionalist Catholics, liturgy
students, researchers. They want to read long chapters and find passages fast.

## Palette (2 core + 1 accent, neutrals excluded)
- Light theme: paper #faf7f0 (warm cream), ink #23201a (near-black brown).
- Dark theme: page #171512, ink #e9e4d8.
- Core structural color: none beyond neutrals; the paper/ink pair carries it.
- Accent (one, used sparingly: links, active chapter, search hits): liturgical
  red #8c2f24 (light) / #d4796a (dark). Red is the book's own visual language
  (Mass vestments, rubrics - the very word "rubric" comes from Latin ruber,
  red). Written reason: accent = rubric red, matching the subject matter.

## Typography
- Body: a readable serif. System serif stack (Georgia, 'Times New Roman') with
  generous line-height (1.7). Reason: the book is a printed text; a serif keeps
  the feel of the page and stays readable for long chapters.
- Headings: same serif family, small-caps tracking for chapter titles.
- Footnotes: 0.85em, slightly muted.
- Monospace: none. No fake-terminal aesthetic (R-06).

## Spacing & rhythm
- Content column max-width 40rem, centered.
- Section spacing varies: chapter title gets more air than a paragraph break.
- RHYTHM dial 1: this is a book reader; uniformity is deliberate.

## Dials
- ENERGY 1 (calm, GOV.UK-like restraint)
- RHYTHM 1 (a book, uniform by nature)
- MOTION 1 (hover/focus states only)

## Themes
Light default (a book on paper), working dark mode toggle (R-21, R-34). Both
themes meet WCAG AA (R-25). Theme choice persists in localStorage.

## Layout
- Header: book title (text, no logo invented - R-23), search box, theme toggle.
- Left sidebar on wide screens: table of contents (14 chapters + front and back
  matter). Collapses to a top menu button on phones (R-03).
- Main: chapter content. Footnotes render inline at chapter end under a rule,
  with their numbers.
- Search: searches book.json client-side, lists hits with chapter and snippet,
  click jumps to the chapter. Static, no server.
- No hero section, no feature cards, no testimonials, no pricing, no FAQ, no
  emoji, no icons beyond what the browser renders, no gradients, no glows,
  no shadows except a single subtle one under the mobile menu if needed.
- Footer: one line (source note + copyright), not four columns.

## Copy voice
Minimum added text, per the brief: navigation labels, search placeholder,
theme toggle label, a one-line source note. No marketing copy at all.
