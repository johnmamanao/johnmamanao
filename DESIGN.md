# Design record

## Brief and product truth

This repository renders John Mamanao's public GitHub profile README. Visitors need to understand who he is, what kind of work he does, and where to contact him without reading a portfolio catalogue.

The profile should feel authored, monochrome, compact, and readable in GitHub light and dark themes. It should not depend on project cards, animated typing, statistics widgets, decorative numbering, or a large technology badge wall.

## Reference evidence

The supplied reference was the public `ayangabryl/ayangabryl` README. Its useful relationship is a centered identity followed by a compact link cluster and personal copy. Its typing animation, jokes, badges, and streak widget belong to that profile and are not reused here.

The transferred principle is: establish identity first, keep navigation nearby, and let one short personal statement carry the rest.

## Alternatives before implementation

- **Wordmark only:** name, sentence, and text links. Clean, but too generic and visually disconnected from John's new mark.
- **Identity banner with custom link controls:** one monochrome SVG lockup, three matching SVG links, and a short statement. Strongest brand recognition with little reading effort.
- **Résumé panel:** split layout with experience and toolkit columns. Informative, but recreates the dense structure the user asked to remove.

## Selected system

The identity banner is selected. It uses an inverse version of the folded J mark, a black field, white primary type, and quiet gray supporting type. The banner owns the visual expression. The rest of the README remains plain and centered.

Brand roles:

- Canvas: GitHub's native page surface.
- Identity field: `#0a0a0a` with a `#303030` edge.
- Primary: white.
- Supporting: `#b8b8b8`.
- Type: GitHub-compatible system sans-serif.
- Shape: the existing folded J geometry and modest rounded rectangles.
- Motion: none. This is a static profile document.

## Verification and disposition

Status: ready for user review.

The SVGs were rendered at full README width on light and dark surfaces and at a 420 px mobile viewport. The first mobile render exposed an undersized banner subtitle, so the title and subtitle were enlarged. Relative assets render, link targets remain separate, and the composition retains contrast in both themes.
