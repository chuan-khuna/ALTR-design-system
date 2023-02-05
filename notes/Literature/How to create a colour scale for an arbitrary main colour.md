by [[City Intelligence Data Design Guidelines|London Style Guide]] p25

Use Chroma.js: https://gka.github.io/palettes/

> Avoids colour kinks that occur when you interpolate across the spectrum (p 25)


# To create shades of core colours
- In this wheel - use diverging scale
![[Screenshot 2023-02-05 at 14.07.48.png]]


# To create a sequential scale from core colours
1. Select a core categorical colour - to create lighter/darker shades
2. Create dark/light shade by generating ==a **diverging** scale== with 11 shades
  - dark: `#121212`, light: `#f5f5f5`
  - 11 shades => 
    - `#121212` | 4 darker | core | 4 lighter | `#f5f5f5`
    - ![[Screenshot 2023-02-05 at 14.02.37.png]]
3. There is a kink in the diverging scale => pick the useful dark/light shade
4. ==Switch back to a sequential scale to generate a smooth scale==
  - ![[Screenshot 2023-02-05 at 14.03.47.png]]