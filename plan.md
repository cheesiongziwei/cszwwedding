You are a senior frontend architect and UI engineer.

Build a PRODUCTION-READY mobile-first luxury wedding invitation web app.

TECH STACK:
- HTML + TailwindCSS
- Vanilla JavaScript (modular, clean)
- Google Forms integration ready
- Optional Firebase/Google Sheets hooks (frontend only)

================================================
GLOBAL THEME
================================================
- Luxury cute cat-themed wedding invitation
- White elegant base design
- Botanical decorations (soft green leaves + flowers)
- Cinematic romantic experience
- Mobile-first responsive design

================================================
FEATURE MODULE 1: ULTRA PRO RSVP SYSTEM
================================================
Build a structured RSVP system:

FORM FIELDS:
- Full Name
- Number of attendees
- Optional message

INTEGRATION DESIGN (IMPORTANT):
- Must be ready for Google Forms mapping
- Include function stubs:
  - submitRSVP()
  - sendToGoogleForm()
  - sendToGoogleSheets()
  - sendToFirebase()

GOOGLE FORM SUPPORT:
- Prepare hidden mapping keys for each input field
- Example:
  name -> entry.xxxxx
  attendees -> entry.xxxxx

SUBMIT BEHAVIOR:
- On submit:
  - show success animation
  - OR redirect placeholder Google Form URL

NO BACKEND IMPLEMENTATION REQUIRED

================================================
FEATURE MODULE 2: CINEMATIC EXPERIENCE SYSTEM
================================================

1. OPENING ENVELOPE EXPERIENCE
- Page starts with CAT PAW "Open Invitation" button
- On click:
  - cinematic transition (fade + zoom + blur)
  - envelope opening animation effect
  - reveal full website

2. SOUND SYSTEM (OPTIONAL HOOK)
- Add placeholder:
  playBackgroundMusic()
  playOpenSound()

3. STORYTELLING FLOW
- Website should feel like a story:
  Section reveal in sequence:
  Hero → Story → Gallery → Cats → RSVP

4. ANIMATIONS:
- Scroll reveal animations
- Floating leaves/flowers
- Smooth easing transitions
- Soft hover micro-interactions

================================================
FEATURE MODULE 3: PHOTO & CAT SYSTEM
================================================

PRE-WEDDING GALLERY:
- Responsive grid
- Lazy-load ready structure
- Placeholder images

CAT SYSTEM:
- 5 cartoon cat placeholders
- Light floating animation
- Subtle decorative role (not dominant)

================================================
FEATURE MODULE 4: OPTIMIZATION SYSTEM
================================================

MUST INCLUDE:

1. PERFORMANCE
- Lazy load images
- Minimal DOM complexity
- Avoid heavy animations on mobile

2. MOBILE FIRST
- 1-column layout on mobile
- touch-friendly buttons
- optimized spacing

3. LIGHTWEIGHT STRUCTURE
- single HTML file
- modular JS functions
- no unnecessary libraries

4. SCROLL OPTIMIZATION
- intersection observer for animations
- avoid continuous animation loops on mobile

================================================
FEATURE MODULE 5: DESIGN QUALITY RULES
================================================
- Must feel like Apple-level landing page
- Elegant spacing (not crowded)
- Botanical decoration subtle, not heavy
- Cats are decorative accents only
- Typography clean and premium

================================================
OUTPUT RULE:
================================================
- Return ONLY a single complete HTML file
- No explanation
- Production-ready structure