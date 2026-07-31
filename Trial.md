# UI Recreation Specification

## Goal

Recreate the attached chatbot builder UI as close as possible to the reference image.

Do NOT redesign.
Do NOT modernize.
Do NOT change spacing.
Follow this specification exactly.

---

# Overall Layout

Desktop only.

Entire application fills viewport.

```
100vw x 100vh
```

Layout:

```
+--------------------------------------------------------------+
| Sidebar |                  Main Workspace                    |
|         |----------------------------------------------------|
|         | Header                                             |
|         |----------------------------------------------------|
|         | Logic Panel         | Preview Panel                |
+--------------------------------------------------------------+
```

Use

```
display:flex;
```

Sidebar fixed width.

Workspace flex-grow.

---

# Colors

Background

```
#ECE8DD
```

Sidebar

```
#3D342F
```

Workspace

```
#F8F7F4
```

Card

```
#FFFFFF
```

Card Border

```
#E4E1DA
```

Purple

```
#7058F6
```

Purple Connector

```
#7A62FF
```

Dark Button

```
#4A4340
```

Primary Text

```
#2E2E2E
```

Secondary Text

```
#777777
```

Input Border

```
#DDDDDD
```

Placeholder

```
#999999
```

---

# Typography

Use

```
Inter
```

Fallback

```
sans-serif
```

Weights

Title

```
700
18px
```

Section title

```
600
15px
```

Navigation

```
500
14px
```

Body

```
400
14px
```

Buttons

```
600
14px
```

Small

```
12px
```

---

# Sidebar

Width

```
240px
```

Layout

```
display:flex;
flex-direction:column;
```

Padding

```
2rem 1.5rem
```

Background

```
#3D342F
```

Top contains

Home icon

Grid icon

Logo

Chatbots badge

Spacing

```
gap:16px
```

---

Navigation groups

Build

Review

Each group title

```
12px
uppercase
600
opacity .8
```

Each navigation item

Height

```
42px
```

Padding

```
0 12px
```

Border radius

```
8px
```

Gap

```
12px
```

Hover

```
rgba(255,255,255,.08)
```

Active

Left border

```
3px solid #7058F6
```

Background

```
rgba(255,255,255,.08)
```

---

# Workspace

```
display:flex;
flex-direction:column;
flex:1;
```

---

# Header

Height

```
72px
```

Padding

```
0 32px
```

Layout

```
display:flex;
justify-content:space-between;
align-items:center;
```

Right contains

Avatar

Dropdown

Share button

Help button

Buttons

Height

```
36px
```

Radius

```
8px
```

---

# Main Content

Use CSS Grid

```
display:grid;
```

Columns

```
1.3fr 1fr
```

Gap

```
32px
```

Padding

```
24px 32px
```

---

# Logic Panel

Vertical flex

Gap

```
24px
```

Header

Logic title

Info icon

Purple Add Logic button

Button

Height

```
42px
```

Radius

```
10px
```

Padding

```
0 18px
```

Purple

```
#7058F6
```

White text

Shadow

```
0 4px 10px rgba(0,0,0,.12)
```

---

# Workflow Cards

Each workflow

White card

Radius

```
14px
```

Border

```
1px solid #E4E1DA
```

Padding

```
20px
```

Gap

```
16px
```

Shadow

```
0 2px 8px rgba(0,0,0,.05)
```

---

Workflow nodes

Height

```
56px
```

Radius

```
10px
```

Padding

```
0 16px
```

Layout

```
display:flex;
align-items:center;
justify-content:space-between;
```

Left

Action icon

Label

Right

Delete icon

Node background

```
#FFFFFF
```

---

Workflow connectors

Purple

Width

```
2px
```

Border radius

```
99px
```

Use SVG or absolute positioned divs.

Connector should visually match screenshot.

---

# Preview Panel

Column layout

Header

Preview title

Restart Chat

Desktop icon

Mobile icon

Spacing

```
24px
```

---

# Phone Mockup

Width

```
360px
```

Height

```
690px
```

Radius

```
28px
```

Background

White

Border

```
1px solid #DDD
```

Shadow

```
0 12px 32px rgba(0,0,0,.12)
```

Center horizontally.

---

# Phone Header

Height

```
72px
```

Center logo

Close button right

Border bottom

```
1px solid #EEE
```

---

# Messages

Flex grow

Padding

```
24px
```

Gap

```
16px
```

---

Bot message

White

Border

```
1px solid #EEE
```

Radius

```
12px
```

Padding

```
12px 16px
```

Width

Fit content

---

Quick Replies

Column

Gap

```
10px
```

Align right

Button background

```
#6E6A68
```

White text

Radius

```
10px
```

Padding

```
10px 14px
```

Shadow

```
0 2px 6px rgba(0,0,0,.15)
```

---

Input

Height

```
56px
```

Border

```
1px solid #DDD
```

Radius

```
12px
```

Padding

```
0 16px
```

Placeholder

```
Ask me anything
```

Right send icon

---

# Border Radius Scale

Cards

```
14px
```

Buttons

```
10px
```

Input

```
12px
```

Phone

```
28px
```

---

# Shadows

Cards

```
0 2px 8px rgba(0,0,0,.05)
```

Phone

```
0 12px 32px rgba(0,0,0,.12)
```

Floating buttons

```
0 4px 12px rgba(0,0,0,.15)
```

---

# Spacing Scale

```
4px
8px
12px
16px
20px
24px
32px
40px
48px
```

Use these consistently.

---

# Icons

Use Lucide React.

Home

Grid

Book

Database

Workflow

Palette

Plug

Sparkles

Settings

MessageSquare

BarChart3

Trash2

ChevronDown

Send

Info

Laptop

Smartphone

Plus

X

---

# Animation

Buttons

```
transition:200ms
```

Hover

```
transform:translateY(-1px)
```

Cards

```
transition:200ms
```

Phone buttons

Scale

```
1.02
```

Purple button

Shadow increases on hover.

---

# Responsive

Only desktop required.

Ignore tablet/mobile.

---

# Tech

React

TypeScript

Tailwind CSS

Lucide React

Framer Motion (only subtle transitions)

No Bootstrap.

No Material UI.

No Ant Design.

---

# Important

The output should closely resemble the reference image.

Prioritize:
- identical spacing
- identical hierarchy
- identical proportions
- matching colors
- matching typography
- matching shadows
- matching rounded corners

Avoid adding any extra UI elements or redesigning the layout.
