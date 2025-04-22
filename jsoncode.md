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
  {
  "content": {
    "chapter_number": "Chapter 2",
    "chapter_title": "Atoms, Molecules & Ions",
    "toc": [
      "2.1 Atomic Theory",
      "2.2 Classification of Matter",
      "2.3 Subatomic Particles",
      "2.4 Ions and Isotopes",
      "2.5 The Periodic Table"
    ],
    "sections": [
      {
        "heading": "2.1 Atomic Theory",
        "paragraphs": [
          "Two historical views:",
          "1. Democritus: All matter is made of indivisible atoms",
          "2. Zeno: Matter is infinitely divisible",
          "Modern understanding: Atoms exist but can be divided into subatomic particles (losing their chemical properties)"
        ],
        "visual": {
          "image_src": "atomic-theory-timeline.png",
          "caption": "Evolution of atomic theory from Democritus to modern quantum mechanics"
        }
      },
      {
        "heading": "2.2 Classification of Matter",
        "paragraphs": [
          "Three fundamental types:",
          "1. Elements (single atom type)",
          "2. Compounds (fixed ratio of atoms)",
          "3. Mixtures (variable ratios)"
        ],
        "classification_chart": {
          "Pure Substances": {
            "Elements": ["Copper (Cu)", "Sulfur (S)", "Lithium (Li)"],
            "Compounds": ["Galena (PbS)", "Water (H₂O)"]
          },
          "Mixtures": {
            "Homogeneous": ["Gatorade", "Air"],
            "Heterogeneous": ["Belt Mountain ore", "Granite"]
          }
        },
        "example": {
          "Gatorade": "Heterogeneous mixture of water, sugar, and electrolytes",
          "Baking Soda": "Compound (NaHCO₃)",
          "Chlorine Gas": "Element (Cl₂)"
        }
      },
      {
        "heading": "2.3 Subatomic Particles",
        "particles": [
          {
            "name": "Proton",
            "symbol": "p⁺",
            "mass_amu": 1.0073,
            "mass_g": "1.673×10⁻²⁴",
            "charge": "+1",
            "role": "Determines element identity"
          },
          {
            "name": "Neutron",
            "symbol": "n",
            "mass_amu": 1.0087,
            "mass_g": "1.675×10⁻²⁴",
            "charge": "0",
            "role": "Nuclear stability"
          },
          {
            "name": "Electron",
            "symbol": "e⁻",
            "mass_amu": 0.0005486,
            "mass_g": "9.110×10⁻²⁸",
            "charge": "-1",
            "role": "Chemical bonding"
          }
        ],
        "atomic_scale": {
          "nucleus_size": "10⁻¹⁵ m (pea in football stadium)",
          "electron_cloud": "10⁻¹⁰ m",
          "density": "1.8×10¹⁴ g/cm³ (nuclear density)"
        }
      },
      {
        "heading": "2.4 Ions and Isotopes",
        "subsections": [
          {
            "title": "Ions",
            "content": {
              "definition": "Charged atoms/molecules where p⁺ ≠ e⁻",
              "calculation": "Charge = #p⁺ - #e⁻",
              "examples": [
                "S²⁻ (16p⁺, 18e⁻)",
                "Zn²⁺ (30p⁺, 28e⁻)"
              ],
              "memory_aid": "CATion = PAWSitive charge"
            }
          },
          {
            "title": "Isotopes",
            "content": {
              "definition": "Atoms with same protons but different neutrons",
              "hydrogen_examples": [
                "¹H (Protium: 1p⁺, 0n)",
                "²H (Deuterium: 1p⁺, 1n)",
                "³H (Tritium: 1p⁺, 2n, radioactive)"
              ],
              "notation": "ᴬZXᶜ where A=mass#, Z=atomic#, c=charge"
            }
          },
          {
            "title": "Atomic Weight Calculation",
            "content": {
              "method": "Weighted average of isotopic masses",
              "chlorine_example": {
                "Cl-35": {
                  "abundance": "75.53%",
                  "mass": 34.97
                },
                "Cl-37": {
                  "abundance": "24.47%",
                  "mass": 36.96
                },
                "calculation": "(0.7553×34.97) + (0.2447×36.96) = 35.45"
              }
            }
          }
        ]
      },
      {
        "heading": "2.5 The Periodic Table",
        "paragraphs": [
          "Developed by Dmitri Mendeleev (1869) based on chemical properties",
          "Contains 7 periods (rows) and 18 groups/families (columns)"
        ],
        "features": {
          "periods": "Horizontal rows (1-7)",
          "groups": {
            "1A": "Alkali metals (Li, Na, K...)",
            "7A": "Halogens (F, Cl, Br...)",
            "8A": "Noble gases (He, Ne, Ar...)"
          },
          "trends": "Elements in same group have similar properties"
        },
        "visual": {
          "image_src": "mendeleev-original-table.jpg",
          "caption": "Mendeleev's original periodic table with gaps for undiscovered elements"
        }
      }
    ],
    "visual_summary": {
      "diagrams": [
        {
          "image_src": "atom-structure.png",
          "caption": "Atomic structure showing nucleus (protons+neutrons) and electron cloud"
        },
        {
          "image_src": "matter-classification.png",
          "caption": "Flowchart for classifying matter into elements, compounds, and mixtures"
        }
      ]
    },
    "footer": "© 2025 CHE101 – Atoms, Molecules & Ions | Total Slides: 166"
  }
  }
}

