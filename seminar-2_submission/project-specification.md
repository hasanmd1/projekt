# Prague Dreamland Festival - Project Specification

## 1. Festival identity

- Name : Prague Dreamland Festival[cite: 1]
- Edition / year : First edition, 2026[cite: 1]
- Location : Prague, Czech Republic[cite: 1]
- Dates : 24-26 July 2026 (Friday-Sunday)[cite: 1]
- Type / character : Fantasy Dream World (Tomorrowland-inspired) electronic music festival[cite: 1]
- Main genres / themes : EDM, House, Techno, Trance, Drum & Bass, Hardstyle[cite: 1]
- Main stages : Mainstage - Astral Gate and Underground Stage - Neon Cave[cite: 1]

Prague Dreamland Festival 2026 is a 3-day immersive fantasy-themed electronic music event set in the heart of Prague[cite: 1]. Blending dream-world storytelling with spectacular stage design, large-scale visuals, daily fireworks, and top international and local artists across multiple electronic genres[cite: 1].

## 2. Purpose of the website

The website is the main information and planning tool for festival visitors. It should help people understand the festival, discover artists and activities, compare events by day and stage, and prepare a personal visit.

### Main objectives

- Explain the festival concept and provide essential event information.
- Make the three-day programme easy to browse and understand.
- Help visitors discover performers and read their profiles.
- Explain the two stages and their characteristics.

### Important user actions

Visitors should be able to:
- browse the programme by date, stage, and activity type;
- search for a performer or programme title;
- understand where and when an event takes place;
- open a performer detail page from a programme item;

## 3. Target groups

| Target group | Needs and expectations | Website information / functions |
|---|---|---|
| First-time festival visitors | Quickly understand what the festival is, when it happens, and how to attend. | Clear home page, dates, festival description, practical information, stage overview. |
| Visitors planning a day | Build a realistic plan and know which event is on which stage and at what time. | Day-by-day schedule, stage and type filters, clear event times. |
| Electronic music enthusiasts | Discover unfamiliar DJs/live acts and understand their styles. | Searchable performer list, genre labels, performer detail pages, links from programme items to profiles. |
| Visitors with access needs | Find access information before arriving and identify whom to contact if details are unclear. | Accessibility information on the practical-information page and stage descriptions. |

## 4. Information architecture

### Sitemap

- **Home**
  - Festival introduction and dates
  - Featured programme items
  - Calls to action: Explore programme / Meet performers / Plan your visit
- **Programme**
  - Programme overview
  - Day filter: 24 July / 25 July / 26 July 2026[cite: 1]
  - Stage filter: Mainstage - Astral Gate / Underground Stage - Neon Cave[cite: 1]
  - Activity-type filter
  - Programme item detail or expandable event information
- **Performers**
  - Searchable performer list (60 artists)[cite: 1]
  - Performer detail page for each performer
  - Related programme items
- **Stages & Venues**
  - Mainstage - Astral Gate (Letná Park)[cite: 1]
  - Underground Stage - Neon Cave (Holešovice)[cite: 1]
  - Stage descriptions and facility notes
- **Practical Information**
  - Dates and location[cite: 1]
  - Getting there and tickets (Standard, VIP, Early Bird)[cite: 1]
  - Accessibility and facilities (Food court, lockers, first aid, water refill)[cite: 1]
  - Contact / help information
- **About Prague Dreamland**
  - Festival concept and themes

### Main navigation

Use a persistent, clearly labelled primary navigation:
**Home . Programme . Performers . Stages & Venues . Practical Info . About**

On smaller screens, the same destinations should be available in a compact menu. The current page should be visually identifiable. Pages should have clear headings and meaningful links back to parent sections. Breadcrumbs will be used for detail pages, for example: `Home > Performers > Lunar Pulse`[cite: 1].

### Relationships between sections

- Programme items reference one performer (`performerRef`) and exactly one stage (`_venueRef`)[cite: 1].
- Performer detail pages list the programme items associated with that performer.
- Stage pages list the programme items scheduled at that stage.
- Practical Information is accessible from the main navigation and the home page.
- The Home page links users into the programme, performers, and visit-planning paths.

### Section purposes

| Section | Purpose |
|---|---|
| Home | Introduce the festival and route visitors to the most common tasks. |
| Programme | Find events by date, stage, activity type. |
| Performers | Browse and search artists; open profiles and related events. |
| Performer detail | Show the artist name, role, country, genres, and linked programme items. |
| Stages & Venues | Explain the character, location, capacity, and facilities of each festival stage. |
| Practical Information | Answer common visit-planning questions and ticket options. |
| About | Explain the festival concept. |

## 5. User scenarios

### Key scenario 1 - Find an event at a particular stage

- **User type:** Visitor planning a day at the festival.
- **Goal:** Find events at Mainstage - Astral Gate on Friday, 24 July 2026[cite: 1].
- **Initial situation:** The visitor opens the website on the home page and does not know the detailed schedule.
- **Expected outcome:** The visitor opens Programme, selects 24 July 2026 and Mainstage - Astral Gate, and sees only the matching programme items with readable start and end times[cite: 1].

### Key scenario 2 - Learn about an artist and their scheduled event

- **User type:** Electronic music enthusiast.
- **Goal:** Understand an unfamiliar DJ's style and find their festival appearance.
- **Initial situation:** The visitor searches by performer name or browses the performer list.
- **Expected outcome:** The visitor opens a performer detail page, reads their role, country, and genre tags, and can follow a link to the performer's scheduled programme item.

### Key scenario 3 - Check access information

- **User type:** Visitor with access requirements.
- **Goal:** Find the available access information before visiting.
- **Initial situation:** The visitor is considering attending but has not visited the festival site before.
- **Expected outcome:** The visitor finds the accessibility section and stage facility notes (such as first aid and rest areas) to plan their visit securely.
