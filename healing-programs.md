# Healing Programs Comparison Plan

## Design Approach
Like SaaS pricing pages (Stripe, Linear, Notion), we'll use a **feature-row comparison table** where:
- Columns = Programs
- Rows = Features/attributes
- Checkmarks (✓) and descriptive text show what's included
- Sticky header row with program names + price
- Highlighted "recommended" column

## Programs (7 In-Person, all 222 EUR / 5 sessions)

| Feature / Attribute        | Basic 🔔 | Advanced 🌀 | Family 👨‍👩‍👧‍👦 | Couple Beginner 💞 | Couple Advanced 🔥 | Spiritual 👁️ | Deep Healing 🦋 |
|---------------------------|----------|------------|--------|------------------|-------------------|-------------|----------------|
| **Best For**              | Newcomers | Meditators | Groups | Partners (new)   | Partners (exp.)   | Seekers     | Trauma/Release  |
| **Focus Area**            | Foundations | Higher Freq | Bonding | Heart & Trust   | Tantra & Intimacy | Crown & 3rd Eye | Inner Child  |
| Sound Bowls Scanning      | ✓        |            |        |                  |                   |             |                |
| Instruments Trial         | ✓        |            |        |                  |                   |             |                |
| Chakra Balancing          | ✓        | ✓          |        | ✓                |                   |             |                |
| Tuning Fork Therapy       | ✓        |            |        |                  |                   |             |                |
| OM Technique              |          | ✓          |        |                  |                   |             |                |
| Guided Trance             |          | ✓          |        |                  |                   |             |                |
| Emotional Release         |          | ✓          |        |                  |                   |             | ✓              |
| Higher Frequencies        |          | ✓          |        |                  |                   |             |                |
| Hong-Sau Meditation       |          | ✓          |        |                  |                   |             |                |
| Group Sound Bath          |          |            | ✓      |                  |                   |             |                |
| Interactive Session       |          |            | ✓      |                  |                   |             |                |
| Energy Restore            |          |            | ✓      |                  |                   |             |                |
| Heart Chakra Focus        |          |            |        | ✓                |                   |             |                |
| Intimacy Healing          |          |            |        | ✓                | ✓                 |             |                |
| Tantra Practices          |          |            |        |                  | ✓                 |             |                |
| Sacral Chakra Work        |          |            |        |                  | ✓                 |             |                |
| Self-Heal Teaching        |          |            |        |                  | ✓                 |             |                |
| Crystal Healing           |          |            |        |                  |                   | ✓           |                |
| Akashic Records           |          |            |        |                  |                   | ✓           |                |
| Crown Chakra Focus        |          |            |        |                  |                   | ✓           |                |
| Nature Elements           |          |            |        |                  |                   | ✓           |                |
| Inner Child Work          |          |            |        |                  |                   |             | ✓              |
| Trauma Healing            |          |            |        |                  |                   |             | ✓              |
| Energy Cleanse            |          |            |        |                  |                   |             | ✓              |
| Sound Drawing             |          |            |        |                  |                   |             | ✓              |
| Breath/Sound Guided Med.  | ✓        | ✓          | ✓      |                  |                   |             |                |
| Reflection/Integration    | ✓        |            |        | ✓                |                   |             |                |
| Custom Sound Bath         |          |            |        | ✓                | ✓                 |             |                |

## UI Implementation
- Horizontal scroll on mobile with sticky first column
- Tab switcher to filter: "Individual" | "Couples" | "Group" | "All"
- Highlighted column for "Spiritual Awakening" as recommended
- Each column header: icon + name + "Best for" tag
- Checkmarks use ✓ with accent color, empty cells use —
- "Book Now" CTA at bottom of each column
