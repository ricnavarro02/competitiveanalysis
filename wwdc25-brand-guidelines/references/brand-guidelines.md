# WWDC25 Brand Guidelines Reference

## Typography

### Font Family

| Font | Usage | Size |
|------|-------|------|
| SF Pro Semi Expanded Medium | Theme default, major headings | 132pt titles |
| SF Hello Bold | Slide titles, emphasis | — |
| SF Hello Regular | Body text, subtitles | 18-30pt |
| SF Hello Light | Supporting text | — |
| SF Mono Medium | Code blocks (primary) | 48pt default |
| SF Mono Regular | Inline code | — |
| SF Mono Bold | Code emphasis | — |
| SF Pro Rounded | Version badge numbers | — |

### Typography Rules

- Use SF Symbols with **SF Pro Regular** weight
- Maintain consistent weight across all SF Symbols
- Code on bullet slides: SF Mono with Code Mix Character Style
- Code NOT permitted in Slide Titles
- Subtitles and bullets: **sentence case**
- Session titles: **sentence case**

---

## Color Palette

### Theme Colors (Hex)

```
Dark 1 (Primary Text):  #222426  rgb(34, 36, 38)
Light 1:                #62ACDB  rgb(98, 172, 219)
Dark 2:                 #8D2CBF  rgb(141, 44, 191)
Light 2:                #007F95  rgb(0, 127, 149)
Background:             #F5F5F7  rgb(245, 245, 247)
Pure White:             #FFFFFF
Pure Black:             #000000
Secondary Gray:         #94A8B2  rgb(148, 168, 178)
```

### Accent Colors (Hex)

```
Accent 1 (Green):   #8FCB9A  rgb(143, 203, 154)
Accent 2 (Yellow):  #F5CF8B  rgb(245, 207, 139)
Accent 3 (Orange):  #F0B582  rgb(240, 181, 130)
Accent 4 (Red):     #EC938E  rgb(236, 147, 142)
Accent 5 (Purple):  #9596D4  rgb(149, 150, 212)
Accent 6 (Blue):    #7CA9EE  rgb(124, 169, 238)
```

### Link Colors

```
Hyperlink:       #0000FF
Followed Link:   #FF00FF
```

### Color Usage

- Use **Blue 1 (Primary)** for text highlights
- Only highlight when critically important
- Diagram drop shadows match box Primary color
- Lighter screens: dark gray callout lines
- Darker screens: dark gray + white callout lines

---

## Layout Specifications

### Canvas

- Working: 1920 × 1080 pt
- Output: 4K (3840 × 2160)

### Split Screen

| Layout | Content Width | Position |
|--------|---------------|----------|
| 50/50 | 820 pt | x: 100pt, y: 300pt |
| 2/3 | 1140 pt | x: 100pt, y: 300pt |

### Placement Guides

| Element | Longest Dimension |
|---------|-------------------|
| Hardware | 670 pt |
| Icon | 480 pt |
| SF Symbol | 400 pt |

---

## Shape Styles

- Inner containers: **8pt** corner radius
- Outer containers: **28pt** corner radius
- Code blocks: max 21 lines, 1740pt wide

---

## Animation

### Approved

| Type | Animation | Parameters |
|------|-----------|------------|
| Statement | Fade and Move | Bottom to top / 2s / 3% |
| Bullet | Fade and Move | Bottom to top / 1.25s / 4% |
| Large Number | Fade and Move | Bottom to top / 1.5s / 4% |
| Diagrams | Magic Move, Fade/Move, Line Draw, Dissolve | — |
| Code | Keyboard | NEW sequences only |
| Badges | Animated movies | NEW, BETA, check, x, ! |

### Avoid

- "Special Effects" animations
- "Flip, Spin and Scale" animations

### Split Screen Rules

- Max 3 alpha/split screens in a row
- Do NOT mix 50/50 and 2/3 layouts in sequence
- Use Alpha slides to break text-heavy runs

---

## Notes

### Color Coding

| Box Color | Purpose |
|-----------|---------|
| Orange | Notes TO design team |
| Blue | Notes FROM design team |

### Presenter Notes

- 􀩫 (click): animation advance
- 􀊆 (pause): breathing reminder
- Use **asterisks** and **CAPS** for emphasis (teleprompter ignores formatting)
