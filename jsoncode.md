{
  "task": "Generate a full HTML file for a CHE101 chapter page",
  "instructions": [
    "Use clean, semantic HTML structure.",
    "The page should follow the same UI styling and layout principles as the CHE101 homepage (index.html), with the styles being defined in 'chapter.css'.",
    "Link to an external CSS file named 'chapter.css' located in the same directory.",
    "Include a header with course info and chapter title.",
    "Add a Table of Contents (TOC) if provided.",
    "Use consistent formatting for section headings, chemical reactions, example boxes, and images.",
    "Ensure accessibility, clean indentation, and responsive layout.",
    "Wrap the content in a container class for layout consistency."
  ],
  "output_format": "Complete standalone HTML page with <html>, <head>, and <body>.",
  "css_link": "chapter.css",
  "content": {
    "chapter_number": "Chapter 4",
    "chapter_title": "Reactions in Aqueous Solutions",
    "toc": [
      "4.1 General Properties",
      "4.2 Types of Aqueous Reactions",
      "4.3 Precipitation Reactions",
      "4.4 Acid-Base Reactions",
      "4.5 Redox Reactions"
    ],
    "sections": [
      {
        "heading": "4.1 General Properties of Aqueous Reactions",
        "paragraphs": [
          "An aqueous solution is one in which the solvent is water. Many reactions occur in aqueous media and are essential in both lab and biological systems."
        ]
      },
      {
        "heading": "4.2 Types of Aqueous Reactions",
        "paragraphs": [
          "There are three major types of reactions that commonly occur in aqueous solutions:",
          "1. Precipitation reactions",
          "2. Acid-base reactions",
          "3. Oxidation-reduction (redox) reactions"
        ]
      },
      {
        "heading": "4.3 Precipitation Reactions",
        "paragraphs": [
          "These occur when two soluble salts react to form an insoluble product, called a precipitate."
        ],
        "reaction": "AgNO₃(aq) + NaCl(aq) → AgCl(s) + NaNO₃(aq)"
      },
      {
        "heading": "4.4 Acid-Base Reactions",
        "paragraphs": [
          "These reactions involve the transfer of a proton (H⁺) from an acid to a base."
        ],
        "reaction": "HCl(aq) + NaOH(aq) → NaCl(aq) + H₂O(l)"
      },
      {
        "heading": "4.5 Redox Reactions",
        "paragraphs": [
          "Oxidation is the loss of electrons; reduction is the gain of electrons. Redox reactions are vital in energy production and metabolism."
        ],
        "reaction": "Zn(s) + Cu²⁺(aq) → Zn²⁺(aq) + Cu(s)"
      }
    ],
    "visual_summary": {
      "image_src": "summary-diagram-ch4.png",
      "caption": "Summary of reactions in aqueous solutions."
    },
    "footer": "© 2025 CHE101 – Reactions in Aqueous Solutions"
  }
}
