# Agent Guidelines for Travel Itineraries Project

## Project Overview
This is a **documentation-only repository** containing European campervan travel itineraries. There is no code to build, test, or run. All content is written in Markdown format.

**Purpose:** Detailed travel planning guides for campervan trips from Netherlands across Europe  
**Format:** Markdown documentation in single directory  
**Style:** Hub-and-spoke travel model (stay 2-3 nights per campsite, day trips by car)

---

## Repository Structure

```
travel/
├── README.md                          # Main overview and guide
├── itineraries/
│   ├── 01-norwegian-fjords.md        # 10-day trip
│   ├── 02-alpine-lakes.md            # 10-day trip
│   ├── 01-scottish-highlands.md      # 15-day trip
│   ├── 02-adriatic-coast.md          # 15-day trip
│   ├── 03-french-spanish-atlantic.md # 15-day trip
│   ├── 04-italian-lakes-mountains.md # 15-day trip
│   ├── croatia-slovenia.md           # 18-day trip
│   └── archive-original-itinerary.md # Original unstructured version
```

---

## Build/Test Commands

**N/A** - This is a documentation repository with no build system, test framework, or code to execute.

### Validation (Manual)
- Markdown syntax: Use any Markdown preview tool
- Links: Verify relative links work correctly
- Formatting: Ensure tables, lists, and headers render properly

---

## Content Guidelines

### 1. Document Structure

Each itinerary file should follow this structure:
```markdown
# [Trip Name] - [Duration] Days

**Best Season:** [Months]
**Total Campervan Distance:** ~[X] km
**Driving Style:** [Description]
**Campsites:** [Strategy]

---

## Quick Navigation
**Jump to Campsite Hubs:**
- [Hub #1: Location](#campsite-hub-1-location)
- [Hub #2: Location](#campsite-hub-2-location)
- [Hub #3: Location](#campsite-hub-3-location)

---

## Campsite Schedule at a Glance

| Hub # | Location | Check-in Date | Check-out Date | Nights | Days |
|-------|----------|---------------|----------------|--------|------|
| 1 | [Location] | [Date] | [Date] | [N] | [Day X-Y] |
| 2 | [Location] | [Date] | [Date] | [N] | [Day X-Y] |
| 3 | [Location] | [Date] | [Date] | [N] | [Day X-Y] |

---

## Overview
[Brief introduction]

---

## Day 1: [Location] → [Destination]
**Drive:** [Distance] km ([Hours] hours)
**Overnight:** [Location]

### Activities
- [Activity list]

### Campsite
- [Campsite name/recommendations]
- [Cost per night]

---

## CAMPSITE HUB #[N]: [Location]
**Location:** [Specific area]
**Nights:** [Number] nights (Days [X-Y])
**Move:** [Distance] km from previous hub

[Continue with daily breakdowns]

---

## Budget Estimate
[Table with cost breakdown]

---

## Practical Tips
[Detailed tips sections]

---

## What Makes This Itinerary Special
[Bullet points with checkmarks]
```

### 2. Writing Style

**Tone:**
- Informative and practical
- Enthusiastic but not overly promotional
- Second-person ("you", "your")
- Friendly and encouraging

**Language:**
- Clear, concise English
- Use bullet points for lists
- Bold for emphasis on **important information**
- Italics for *nice-to-have* details

**Formatting:**
- Headers: Use `##` for main sections, `###` for subsections, `####` for details
- Lists: Use `-` for unordered lists, `1.` for numbered lists
- Tables: Use Markdown tables for comparisons and budgets
- Checkmarks: Use `✅` for highlights and benefits
- Emoji flags: Use country flags (🇳🇴 🇮🇹 etc.) sparingly, typically at document end

### 3. Content Standards

**Distance & Driving:**
- Always provide distance in kilometers
- Include estimated driving time with breaks
- Distinguish between:
  - Campervan driving (with trailer, slower)
  - Car day trips (without trailer, more flexible)
- Note "long drives" (600-800 km) vs "short moves" (200-400 km)

**Money:**
- Currency: Always use **€** (Euro) for all budgets
- Cost ranges: Provide range (e.g., €30-40) not single number
- Budget tables: Use consistent categories:
  - Fuel
  - Tolls & vignettes
  - Camping
  - Food & groceries
  - Activities
  - Attractions

**Locations:**
- Provide specific place names (not just regions)
- Include alternative options when relevant
- Note distances between locations
- Mention parking/access considerations for campervan

**Activities:**
- **Kayaking:** Specify water conditions (calm/rough, cold/warm)
- **Hiking:** Include distance, duration, difficulty level
- **Photography:** Mention best times (golden hour, sunrise, etc.)
- **Drone:** Note regulations and restrictions

### 4. Hub-and-Spoke Model Requirements

Every itinerary MUST follow this pattern:
- **Long drives** to reach destination (600-800 km acceptable)
- **Campervan stays put** for 2-3 nights at each hub
- **Day trips by car** from campsite base (typically 50-150 km round trip)
- **Short moves** between hubs (200-400 km maximum)
- This reflects the user's travel preference!

### 5. Essential Information Sections

Every itinerary must include:
- ✅ Quick navigation links to all campsite hubs
- ✅ Campsite schedule table with check-in/check-out dates
- ✅ Day-by-day breakdown
- ✅ Campsite recommendations with costs
- ✅ Budget estimate table
- ✅ Kayaking specifics (water temp, conditions, launch points)
- ✅ Photography/drone opportunities and regulations
- ✅ Driving tips specific to region
- ✅ Food highlights
- ✅ Weather considerations
- ✅ Practical tips section
- ✅ "What Makes This Itinerary Special" summary
- ✅ Alternative adjustments (if more/less time)
- ✅ Campsite summary table

### 6. Consistent Terminology

Use these exact terms:
- **Campervan** (not RV, motorhome, or caravan)
- **Hub-and-spoke model** (not base camp or similar)
- **Day trip by car** (not excursion)
- **Campsite hub** (not just campsite)
- **Round trip** when describing day trip distances

### 7. Special Considerations

**User Context (always keep in mind):**
- Starting point: Netherlands
- Vehicle: Peugeot 5008 1.6 THP (2015) towing campervan
- Travelers: 2 adults (couple)
- Activities: Kayaking (inflatable), hiking, photography, drone videography
- Kayaking level: Amateur (prefer calm waters)
- Driving preference: Hub-and-spoke model

**Kayaking Notes:**
- Specify if suitable for inflatable kayak
- Note water temperature
- Mention calm vs. rough conditions
- Include rental availability
- Safety considerations

**Drone Notes:**
- Country-specific regulations
- Registration requirements
- Restricted areas (airports, military, parks)
- Best locations for aerial shots

---

## Making Changes

### Adding New Itinerary

1. **Create file:** `itineraries/[name].md` (use descriptive name with optional duration suffix)
2. **Follow structure:** Use existing itineraries as template
3. **Include quick navigation links** to all campsite hubs at the top
4. **Add campsite schedule table** showing check-in/check-out dates
5. **Update README.md:**
   - Add to appropriate section based on duration
   - Add to comparison chart
   - Update "Choosing Your Itinerary" section if relevant

### Modifying Existing Itinerary

1. **Maintain structure:** Don't break the established format
2. **Verify links:** Ensure all relative links still work
3. **Update README:** If costs, distances, or highlights change
4. **Keep hub-and-spoke model:** Don't change to daily campsite moves

### Updating README.md

The README serves as the master index and decision guide:
- **Keep comparison chart updated** with all itineraries
- **Maintain consistency** in "Best For" descriptions
- **Update budget ranges** if individual itineraries change
- **Ensure all links work** (use relative paths)

---

## Quality Checklist

Before considering any itinerary complete:

- [ ] Follows hub-and-spoke model (2-3 nights per campsite)
- [ ] Includes all required sections (see §5)
- [ ] Budget table present with realistic estimates
- [ ] Campsite recommendations with costs
- [ ] Kayaking details for all water activities
- [ ] Photography/drone notes included
- [ ] Driving distances and times realistic
- [ ] Day trip round-trip distances noted
- [ ] "What Makes This Special" section with ✅ checkmarks
- [ ] Practical tips section comprehensive
- [ ] Alternative adjustments provided
- [ ] No broken internal links
- [ ] Consistent formatting throughout
- [ ] Matches user's travel style preferences

---

## Common Patterns

### Budget Table Format
```markdown
| Category | Cost (EUR) |
|----------|------------|
| Fuel (campervan) | €[X]-[Y] |
| Tolls & vignettes | €[X]-[Y] |
| Camping ([N] nights) | €[X]-[Y] |
| Food & groceries | €[X]-[Y] |
| Activities | €[X]-[Y] |
| **Total** | **€[X]-[Y]** |
```

### Campsite Hub Header
```markdown
## CAMPSITE HUB #[N]: [Location Name]
**Location:** [Specific town/area]
**Nights:** [X] nights (Days [Y-Z])
**Move:** [Distance] km from [previous location]
```

### Day Trip Header
```markdown
### Day [N]: [Activity/Location] (Day Trip by Car)
**Car Round Trip:** ~[X] km
```

---

## Tone Examples

**Good:**
> "This itinerary combines the dramatic peaks of the Dolomites with the serene beauty of alpine lakes and the stunning Adriatic coast - truly the best of three incredible countries!"

**Avoid:**
> "This is literally the most amazing trip you'll ever take! You MUST do this!"

**Good:**
> "Your inflatable kayak is perfect for Lake Bled's calm waters. Launch from multiple spots around the lake for 2-3 hours of peaceful paddling with mountain reflections."

**Avoid:**
> "Go kayaking on the lake."

---

## Version Control

- Keep `archive-original-itinerary.md` as historical reference
- Don't delete old versions; move to archive folder if needed
- When making substantial changes, document reason in commit message

---

## Final Notes

This is a **living documentation project** that may be updated based on:
- User feedback after trips
- Changes in costs, regulations, or access
- Discovery of new locations or better routes
- Seasonal variations

Always prioritize **accuracy, practicality, and user experience** over promotional language.

**Most important:** Remember the user wants a relaxed, hub-based travel style with their campervan parked for 2-3 nights while they explore by car. Every itinerary must respect this fundamental preference.
