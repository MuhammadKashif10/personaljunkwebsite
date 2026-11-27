# Goal-keyword plan, round 2 — 10 targets, 60 supporting articles

**Written:** 2026-11-26. **This file does not publish anything** and it does not edit `keywords.md`, `article-registry.md`, or any other existing file until the owner approves it and later says to write a batch.

**Follows** `docs/content-system/content-plan-60-articles-goal-keywords.md` (the first 30-day calendar, now finished for every eligible slot). That plan kept the 10 generic targets on their money pages and added supporting articles with **different** intents. This plan does the same for a new 30-day window.

**Calendar:** two articles a day, Friday 2026-11-27 through Saturday 2026-12-26 (30 days, 60 slots). Nothing is commissioned until the owner says yes for that batch. Nothing goes live until the owner says “Merge and live” for that batch. One pull request per batch.

**Search volumes, difficulty and rank positions:** not measured, and not invented. Strength labels below mean a distinct intent and a supporting role, not a traffic forecast.

**Audit basis:** the live repository at https://github.com/MuhammadKashif10/personaljunkwebsite, branch `main`, commit `87b9666` (“Day 28: freestanding noticeboard guide (#33)”). `article-registry.md` records **155 published articles** as at 2026-11-26. This plan was checked programmatically against those 155 records, the §5.2 claims index, `content/file-posts.js`, mapped rows in `keywords.md`, and the blocked, held and DO NOT WRITE lists.

---

## How ranking is still split

Three kinds of URL, and they must not swap jobs. This is unchanged from the first plan.

| Intent | Who owns it | What must not happen |
|---|---|---|
| Generic target, no neighbourhood | The one page named in the map below | A second service page or a blog post aimed at the same phrase |
| Target plus a community | That community’s `/areas/{slug}` page | A new “junk removal in Marina” article, or the same paragraph pasted across area pages |
| A specific problem, item or deadline | One new or existing article | An article whose keyword is a target, or a word-order variant of a target |

Articles may link to an area page only when the sentence is about that community for a reason already in the area copy. No list of areas. No invented gate rules, lift sizes, “most residents” claims, prices, ratings, reviews, licence details, addresses, hours, Google Business Profile links, search volumes, or Dubai regulations.

---

## (a) Keyword-to-owner map — unchanged

The 10 generic targets stay on the same money pages as in the first plan. No article in this calendar may claim one of these as its primary keyword.

### Cluster A head terms — targets 1, 2, 7 and 8

| # | Target | Owner |
|---|---|---|
| 1 | junk removal Dubai | `/` |
| 2 | Dubai junk removal | `/` |
| 7 | junk removal service in Dubai | `/` |
| 8 | Dubai junk collection | `/` |

### Cluster B and commercial cardboard — targets 9, 10 and 3

| # | Target | Owner |
|---|---|---|
| 9 | rubbish removal service | `/services/junk-removal` |
| 10 | trash pickup Dubai | `/services/junk-removal` |
| 3 | cardboard removal service | `/services/junk-removal` |

### Single-owner targets

| # | Target | Owner |
|---|---|---|
| 4 | bulky waste collection | `/blog/dubai-municipality-bulky-waste` |
| 5 | furniture removal Dubai | `/services/furniture-removal` |
| 6 | waste collection service Dubai | `/services/waste-removal` |

Every article below targets its own narrow long-tail and signposts to one of these five money pages.

---

## ID series

New IDs continue the cluster series already used in `keywords.md` and `article-registry.md`. None of these IDs exist in the published set, the blocked or held set, or the current keyword map.

| Series | Already used through | This plan | Money-page cluster |
|---|---|---|---|
| A | A1–A44 (A45 was free) | A45–A56 (12) | Homepage `/` — core junk collection |
| F | F1–F27 (F28 was free) | F28–F43 (16) | `/services/junk-removal` — rubbish, trash, cardboard |
| C | C1–C44 (C45 was free) | C45–C56 (12) | `/services/furniture-removal` |
| M | M1–M31 (M32 was free; M28–M30 stay held or blocked and are not reused) | M32–M41 (10) | `/blog/dubai-municipality-bulky-waste` |
| K | K1–K21 (K22 was free; K20 and K21 stay blocked and are not reused) | K22–K31 (10) | `/services/waste-removal` |

G24, G25, G26, K20, K21, M28, M29 and M30 remain unused in this plan.

---

## How the 60 articles support the 10 targets

The 60 slots are spread across all five money pages so each of the 10 targets gets topical and internal-link support. Counts are slot counts, not traffic forecasts.

| Money page | Slots | New IDs | Main targets supported |
|---|---|---|---|
| `/` | 12 | A45–A56 | 1, 2, 7, 8 |
| `/services/junk-removal` | 16 | F28–F43 | 3, 9, 10 |
| `/services/furniture-removal` | 12 | C45–C56 | 5 |
| `/blog/dubai-municipality-bulky-waste` | 10 | M32–M41 | 4 |
| `/services/waste-removal` | 10 | K22–K31 | 6 |

Inside the 16 junk-removal slots, five are cardboard situations (F28–F32), six are rubbish situations (F33–F38), and five are trash-pickup situations (F39–F43). That split is deliberate, so targets 3, 9 and 10 are not left to a single article type.

Days are interleaved: most days pair two different money pages, so a week of publishing does not stack twelve furniture URLs in a row.

---

## Cannibalization and exclusion guardrails

A proposed article is dropped if any of the following is true.

1. Its primary keyword, slug or ID already appears in the 155 published records, the §5.2 claims index, `file-posts.js`, or a mapped `keywords.md` row.
2. Its primary keyword is one of the 10 targets, or a word-order variant of a target.
3. Its subject is a blocked or held slot: G24 (pergola, shed, deck, gazebo, fence), K21 (restaurant furniture), G25 (artificial grass), K20 (exhibition stands), M29 (waste transporters), M30 (water-damaged furniture), G26 (municipal green-waste collection), M28 (rubbish dump / public tip).
4. Its subject is a blocked specialty item: water-damaged furniture, piano, pool table, safe, aquarium, hot tub, above-ground pool frame, water tank, ceiling fan, commercial gym.
5. Its subject is on the DO NOT WRITE list: coffee table, bunk bed, curtain, bookshelf, chest of drawers, mirror, filing cabinet, baby cot, microwave / general cardboard, exercise bike / rowing machine, office partition / mannequin, pallet / tiles, previous-tenant furniture / scrap metal, clothes / tyres, plus the earlier dressing-table and office-chair pair.
6. The draft would need an invented price, rating, review count, licence, address, hours, Google Business Profile link, search volume, or unverified Dubai regulation.

**Programmatic check, 2026-11-26:** 60 unique IDs, 60 unique slugs, 60 unique primary keywords, and **zero** collisions with the 155 published posts, the blocked and held IDs, or the DO NOT WRITE slugs and keywords.

---

## (b) Calendar

Anchors are suggestions. Vary them. Do not use a raw target as the anchor on every article, and never use a raw target as the article’s primary keyword.

Each slot is marked `PROPOSED — pending owner approval`. Strength is a writing priority, not a demand figure: **Strong** means a clear decision the published set does not already make; **Adequate** means a narrow job that must stop if the draft starts repeating a named guide.

### Master schedule

| Day | Date | Slot | ID | Title | Primary keyword | URL | Money page | Targets |
|---|---|---|---|---|---|---|---|---|
| 1 | Friday 27 November 2026 | A | A45 | A bean bag that will not compact | bean bag removal dubai | `/blog/bean-bag-removal-dubai` | `/` | 1, 2, 7, 8 |
| 1 | Friday 27 November 2026 | B | F28 | A carton stack in a shop back room | shop back room carton stack dubai | `/blog/shop-back-room-cartons-dubai` | `/services/junk-removal` | 3, 9 |
| 2 | Saturday 28 November 2026 | A | C45 | A hallway console table | console table removal dubai | `/blog/console-table-removal-dubai` | `/services/furniture-removal` | 5 |
| 2 | Saturday 28 November 2026 | B | M32 | A plastic playhouse in a villa garden | plastic playhouse removal dubai | `/blog/plastic-playhouse-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 3 | Sunday 29 November 2026 | A | K22 | Salon waste bags at closing time | salon end of day waste collection dubai | `/blog/salon-end-of-day-waste-dubai` | `/services/waste-removal` | 6 |
| 3 | Sunday 29 November 2026 | B | A46 | A cat tree at the end of a hallway | cat tree removal dubai | `/blog/cat-tree-removal-dubai` | `/` | 1, 2, 8 |
| 4 | Monday 30 November 2026 | A | F29 | Marketplace-seller cartons in a spare room | marketplace seller cartons dubai | `/blog/marketplace-seller-cartons-dubai` | `/services/junk-removal` | 3 |
| 4 | Monday 30 November 2026 | B | C46 | A bathroom vanity unit | bathroom vanity unit removal dubai | `/blog/bathroom-vanity-unit-removal-dubai` | `/services/furniture-removal` | 5 |
| 5 | Tuesday 1 December 2026 | A | M33 | A dog kennel that is coming out | dog kennel removal dubai | `/blog/dog-kennel-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 5 | Tuesday 1 December 2026 | B | K23 | Cafe packaging waste after close | cafe closing waste collection dubai | `/blog/cafe-closing-waste-dubai` | `/services/waste-removal` | 6 |
| 6 | Wednesday 2 December 2026 | A | A47 | A car seat the child has outgrown | car seat removal dubai | `/blog/car-seat-removal-dubai` | `/` | 1, 8 |
| 6 | Wednesday 2 December 2026 | B | F30 | Catering cartons after a villa gathering | catering cartons villa gathering dubai | `/blog/catering-cartons-villa-dubai` | `/services/junk-removal` | 3, 9 |
| 7 | Thursday 3 December 2026 | A | C47 | A kitchen dresser with the plates already packed | kitchen dresser removal dubai | `/blog/kitchen-dresser-removal-dubai` | `/services/furniture-removal` | 5 |
| 7 | Thursday 3 December 2026 | B | M34 | An inflatable paddling pool, not a frame pool | inflatable paddling pool removal dubai | `/blog/inflatable-paddling-pool-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 8 | Friday 4 December 2026 | A | K24 | Florist stem and bucket waste | florist waste collection dubai | `/blog/florist-waste-collection-dubai` | `/services/waste-removal` | 6 |
| 8 | Friday 4 December 2026 | B | A48 | A standing punching bag in a spare room | punching bag removal dubai | `/blog/punching-bag-removal-dubai` | `/` | 1, 7, 8 |
| 9 | Saturday 5 December 2026 | A | F31 | Archive cartons from a home office | archive cartons home office dubai | `/blog/archive-cartons-home-office-dubai` | `/services/junk-removal` | 3 |
| 9 | Saturday 5 December 2026 | B | C48 | A drinks cabinet from a living room | drinks cabinet removal dubai | `/blog/drinks-cabinet-removal-dubai` | `/services/furniture-removal` | 5 |
| 10 | Sunday 6 December 2026 | A | M35 | A hanging egg chair | hanging egg chair removal dubai | `/blog/hanging-egg-chair-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 10 | Sunday 6 December 2026 | B | K25 | Bakery trays and packaging at the end of the day | bakery waste collection dubai | `/blog/bakery-waste-collection-dubai` | `/services/waste-removal` | 6 |
| 11 | Monday 7 December 2026 | A | A49 | A stepladder that is being replaced | stepladder removal dubai | `/blog/stepladder-removal-dubai` | `/` | 1, 2, 8 |
| 11 | Monday 7 December 2026 | B | F32 | Cartons the movers did not take back | movers leftover cartons dubai | `/blog/movers-leftover-cartons-dubai` | `/services/junk-removal` | 3, 9 |
| 12 | Tuesday 8 December 2026 | A | C49 | A hallway bench that blocks the door | hallway bench removal dubai | `/blog/hallway-bench-removal-dubai` | `/services/furniture-removal` | 5 |
| 12 | Tuesday 8 December 2026 | B | M36 | A hammock stand with the fabric already packed | hammock stand removal dubai | `/blog/hammock-stand-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 13 | Wednesday 9 December 2026 | A | K26 | Classroom waste after the term ends | classroom waste after term dubai | `/blog/classroom-waste-after-term-dubai` | `/services/waste-removal` | 6 |
| 13 | Wednesday 9 December 2026 | B | A50 | A portable clothes rail after a move | portable clothes rail removal dubai | `/blog/portable-clothes-rail-removal-dubai` | `/` | 1, 7 |
| 14 | Thursday 10 December 2026 | A | F33 | Party rubbish the chute will not take | party rubbish chute will not take dubai | `/blog/party-rubbish-chute-dubai` | `/services/junk-removal` | 9, 10 |
| 14 | Thursday 10 December 2026 | B | C50 | A chaise longue that will not turn the corner | chaise longue removal dubai | `/blog/chaise-longue-removal-dubai` | `/services/furniture-removal` | 5 |
| 15 | Friday 11 December 2026 | A | M37 | A patio heater, not a barbecue | patio heater removal dubai | `/blog/patio-heater-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 15 | Friday 11 December 2026 | B | K27 | Leftover waste after a community-hall booking | community hall event waste dubai | `/blog/community-hall-event-waste-dubai` | `/services/waste-removal` | 6 |
| 16 | Saturday 12 December 2026 | A | A51 | A wheelbarrow and a rusted tool pile | wheelbarrow removal dubai | `/blog/wheelbarrow-removal-dubai` | `/` | 1, 2, 8 |
| 16 | Saturday 12 December 2026 | B | F34 | A takeaway-container stack in the kitchen | takeaway container stack dubai | `/blog/takeaway-container-stack-dubai` | `/services/junk-removal` | 9, 10 |
| 17 | Sunday 13 December 2026 | A | C51 | A storage ottoman at the end of a bed | storage ottoman removal dubai | `/blog/storage-ottoman-removal-dubai` | `/services/furniture-removal` | 5 |
| 17 | Sunday 13 December 2026 | B | M38 | A portable basketball hoop | portable basketball hoop removal dubai | `/blog/portable-basketball-hoop-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 18 | Monday 14 December 2026 | A | K28 | Dry-cleaner hangers and film | dry cleaner hangers and film waste dubai | `/blog/dry-cleaner-hangers-film-dubai` | `/services/waste-removal` | 6 |
| 18 | Monday 14 December 2026 | B | A52 | A kayak against a villa wall | kayak removal dubai | `/blog/kayak-removal-dubai` | `/` | 1, 8 |
| 19 | Tuesday 15 December 2026 | A | F35 | Wrapping paper and gift packaging after a celebration | gift wrapping waste dubai | `/blog/gift-wrapping-waste-dubai` | `/services/junk-removal` | 9, 3 |
| 19 | Tuesday 15 December 2026 | B | C52 | A toy chest after the children have grown | toy chest removal dubai | `/blog/toy-chest-removal-dubai` | `/services/furniture-removal` | 5 |
| 20 | Wednesday 16 December 2026 | A | M39 | A children’s plastic slide | kids plastic slide removal dubai | `/blog/kids-plastic-slide-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 20 | Wednesday 16 December 2026 | B | K29 | Waste left when a self-storage unit is emptied | self storage unit waste collection dubai | `/blog/self-storage-unit-waste-dubai` | `/services/waste-removal` | 6 |
| 21 | Thursday 17 December 2026 | A | A53 | A golf bag from a hall cupboard | golf bag removal dubai | `/blog/golf-bag-removal-dubai` | `/` | 1, 2, 8 |
| 21 | Thursday 17 December 2026 | B | F36 | Bagged rubbish after a villa guest weekend | villa guest weekend rubbish dubai | `/blog/villa-guest-weekend-rubbish-dubai` | `/services/junk-removal` | 9, 10 |
| 22 | Friday 18 December 2026 | A | C53 | A children’s table and chair set | kids table and chairs removal dubai | `/blog/kids-table-and-chairs-removal-dubai` | `/services/furniture-removal` | 5 |
| 22 | Friday 18 December 2026 | B | M40 | A fire pit or chimenea | fire pit removal dubai | `/blog/fire-pit-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 23 | Saturday 19 December 2026 | A | K30 | Damaged-parcel waste from a courier bay | damaged parcel waste collection dubai | `/blog/damaged-parcel-waste-dubai` | `/services/waste-removal` | 6, 3 |
| 23 | Saturday 19 December 2026 | B | A54 | A table-tennis table that will not fold | table tennis table removal dubai | `/blog/table-tennis-table-removal-dubai` | `/` | 1, 7, 8 |
| 24 | Sunday 20 December 2026 | A | F37 | Bagged rubbish when the chute is out of use | bagged rubbish when chute is out of use dubai | `/blog/bagged-rubbish-chute-out-of-use-dubai` | `/services/junk-removal` | 9, 10 |
| 24 | Sunday 20 December 2026 | B | C54 | A folding screen in a home, not an office | folding screen removal dubai | `/blog/folding-screen-removal-dubai` | `/services/furniture-removal` | 5 |
| 25 | Monday 21 December 2026 | A | M41 | A garden statue that has to come off a plinth | garden statue removal dubai | `/blog/garden-statue-removal-dubai` | `/blog/dubai-municipality-bulky-waste` | 4 |
| 25 | Monday 21 December 2026 | B | K31 | Leftover décor after a wedding-hall event | wedding hall decor waste dubai | `/blog/wedding-hall-decor-waste-dubai` | `/services/waste-removal` | 6 |
| 26 | Tuesday 22 December 2026 | A | A55 | A turntable and a crate of vinyl | turntable removal dubai | `/blog/turntable-removal-dubai` | `/` | 1, 8 |
| 26 | Tuesday 22 December 2026 | B | F38 | Iftar packaging after a home gathering | iftar packaging waste dubai | `/blog/iftar-packaging-waste-dubai` | `/services/junk-removal` | 9, 3 |
| 27 | Wednesday 23 December 2026 | A | C55 | A headboard when the bed frame is staying | headboard removal dubai | `/blog/headboard-removal-dubai` | `/services/furniture-removal` | 5 |
| 27 | Wednesday 23 December 2026 | B | F39 | A burst bin bag on a tower landing | burst bin bag on a landing dubai | `/blog/burst-bin-bag-landing-dubai` | `/services/junk-removal` | 10, 9 |
| 28 | Thursday 24 December 2026 | A | A56 | An evaporative cooler at the end of summer | evaporative cooler removal dubai | `/blog/evaporative-cooler-removal-dubai` | `/` | 1, 2, 7 |
| 28 | Thursday 24 December 2026 | B | F40 | Trash bags left after a barbecue | bbq leftover trash bags dubai | `/blog/bbq-leftover-trash-bags-dubai` | `/services/junk-removal` | 10, 9 |
| 29 | Friday 25 December 2026 | A | C56 | A bar cart that is no longer used | bar cart removal dubai | `/blog/bar-cart-removal-dubai` | `/services/furniture-removal` | 5 |
| 29 | Friday 25 December 2026 | B | F41 | Leftover trash after a garage sale | garage sale leftover trash dubai | `/blog/garage-sale-leftover-trash-dubai` | `/services/junk-removal` | 10, 9 |
| 30 | Saturday 26 December 2026 | A | F42 | Trash bags after a children’s party | kids party trash bags dubai | `/blog/kids-party-trash-bags-dubai` | `/services/junk-removal` | 10, 9 |
| 30 | Saturday 26 December 2026 | B | F43 | Empty water bottles the supplier will not take back | empty water bottle stack dubai | `/blog/empty-water-bottle-stack-dubai` | `/services/junk-removal` | 10, 9 |

### Day 1 — Friday 27 November 2026

#### Slot A — `PUBLISHED 2026-11-27` — Strong — A45

Set to `PUBLISHED` on 2026-11-27 after the owner said “Merge and live”. §5.2 claim applied. The published count is 157. The pull request is not merged in this change.

- **ID:** A45
- **Primary keyword:** bean bag removal dubai
- **Title:** A bean bag that will not compact
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/bean-bag-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 2, 7, 8 — 1 (junk removal Dubai); 2 (Dubai junk removal); 7 (junk removal service in Dubai); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “book a junk collection”; `/blog/decluttering-small-dubai-apartment`
- **Why this slot:** A soft, bulky piece that does not compress for the chute or a car boot. It is not a sofa, armchair or mattress, and it is not a full-room clear-out.

#### Slot B — `PUBLISHED 2026-11-27` — Strong — F28

Set to `PUBLISHED` on 2026-11-27 after the owner said “Merge and live”. §5.2 claim applied. The published count is 157. The pull request is not merged in this change.

- **ID:** F28
- **Primary keyword:** shop back room carton stack dubai
- **Title:** A carton stack in a shop back room
- **Search intent:** Commercial cardboard / shop operations
- **Suggested URL:** `/blog/shop-back-room-cartons-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC6)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 3, 9 — 3 (cardboard removal service); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a cardboard collection with the rest of the load”; `/blog/shop-clearance-dubai`; `/blog/packing-material-disposal-dubai`
- **Why this slot:** Daily or weekly carton volume at the back of a trading shop, not a shop-fit clearance and not household shipping cartons, product boxes or wet cardboard. Supports the junk-removal page’s commercial cardboard phrase without claiming it.

### Day 2 — Saturday 28 November 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — C45

- **ID:** C45
- **Primary keyword:** console table removal dubai
- **Title:** A hallway console table
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/console-table-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for a single piece”; `/blog/coat-stand-removal-dubai`; `/blog/shoe-cabinet-removal-dubai`
- **Why this slot:** A narrow hall table, not a coffee table (which stays DO NOT WRITE), not a sideboard and not a media wall unit. The coat-stand and shoe-cabinet guides keep those pieces.

#### Slot B — `PROPOSED — pending owner approval` — Strong — M32

- **ID:** M32
- **Primary keyword:** plastic playhouse removal dubai
- **Title:** A plastic playhouse in a villa garden
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/plastic-playhouse-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the municipal bulky-waste guide”; `/blog/trampoline-removal-dubai`; `/services/junk-removal`
- **Why this slot:** A large hollow playhouse that often sits too far from the gate for a municipal pickup to take unaided. The trampoline and kids’ slide guides stay on their own objects.

### Day 3 — Sunday 29 November 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — K22

- **ID:** K22
- **Primary keyword:** salon end of day waste collection dubai
- **Title:** Salon waste bags at closing time
- **Search intent:** Commercial waste / end of day
- **Suggested URL:** `/blog/salon-end-of-day-waste-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “a waste collection for a one-off load”; `/blog/office-waste-collection-dubai`
- **Why this slot:** Bagged general waste from a salon or barbershop at close, not clinical or hazardous waste, and not salon furniture. The office-waste guide stays on office loads.

#### Slot B — `PROPOSED — pending owner approval` — Strong — A46

- **ID:** A46
- **Primary keyword:** cat tree removal dubai
- **Title:** A cat tree at the end of a hallway
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/cat-tree-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 2, 8 — 1 (junk removal Dubai); 2 (Dubai junk removal); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “junk removal for a single awkward piece”; `/blog/pet-carrier-removal-dubai`
- **Why this slot:** A tall, awkward pet tree, not a pet carrier and not a full room clearance. Signposts a collection, not a head-term page fight.

### Day 4 — Monday 30 November 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — F29

- **ID:** F29
- **Primary keyword:** marketplace seller cartons dubai
- **Title:** Marketplace-seller cartons in a spare room
- **Search intent:** Situation / cardboard volume at home
- **Suggested URL:** `/blog/marketplace-seller-cartons-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC6)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 3 — 3 (cardboard removal service)
- **Internal links:** `/services/junk-removal` — anchor: “cardboard collection from the home”; `/blog/shipping-cartons-filling-a-flat-dubai`; `/blog/product-boxes-not-moving-boxes-dubai`
- **Why this slot:** Stock cartons from online selling, not one-off delivery boxes, not a house-move packing load, and not wet cardboard.

#### Slot B — `PROPOSED — pending owner approval` — Strong — C46

- **ID:** C46
- **Primary keyword:** bathroom vanity unit removal dubai
- **Title:** A bathroom vanity unit
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/bathroom-vanity-unit-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for a fitted piece”; `/blog/bedroom-furniture-removal-dubai`
- **Why this slot:** A bathroom vanity, not a chest of drawers (DO NOT WRITE), not a bedside table, and not a dressing table (DO NOT WRITE). Scope stops at disconnection the owner has already arranged.

### Day 5 — Tuesday 1 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — M33

- **ID:** M33
- **Primary keyword:** dog kennel removal dubai
- **Title:** A dog kennel that is coming out
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/dog-kennel-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “whether it can go on a bulky-waste collection”; `/blog/pet-carrier-removal-dubai`
- **Why this slot:** An outdoor kennel, not a plastic pet carrier and not a crate kept indoors. Useful where the municipal guide’s ground-level rule is the reader’s real question.

#### Slot B — `PROPOSED — pending owner approval` — Strong — K23

- **ID:** K23
- **Primary keyword:** cafe closing waste collection dubai
- **Title:** Cafe packaging waste after close
- **Search intent:** Commercial waste / closing time
- **Suggested URL:** `/blog/cafe-closing-waste-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “waste collection after close”; `/blog/restaurant-equipment-removal-dubai`
- **Why this slot:** Packaging and bagged general waste at closing time, not cafe or restaurant furniture (K21 stays blocked) and not kitchen equipment (already published).

### Day 6 — Wednesday 2 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — A47

- **ID:** A47
- **Primary keyword:** car seat removal dubai
- **Title:** A car seat the child has outgrown
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/car-seat-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 8 — 1 (junk removal Dubai); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “add it to a junk collection”; `/blog/stroller-removal-dubai`; `/blog/high-chair-removal-dubai`
- **Why this slot:** An outgrown car seat, not a stroller, high chair, playpen or baby cot (the cot stays DO NOT WRITE). No invented donation or expiry rules.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — F30

- **ID:** F30
- **Primary keyword:** catering cartons villa gathering dubai
- **Title:** Catering cartons after a villa gathering
- **Search intent:** Situation / cardboard after an event
- **Suggested URL:** `/blog/catering-cartons-villa-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC6)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 3, 9 — 3 (cardboard removal service); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a cardboard and rubbish pickup”; `/blog/majlis-clearance-dubai`
- **Why this slot:** Catering cartons left after a gathering, not a majlis furniture clearance and not a general cardboard URL.

### Day 7 — Thursday 3 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — C47

- **ID:** C47
- **Primary keyword:** kitchen dresser removal dubai
- **Title:** A kitchen dresser with the plates already packed
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/kitchen-dresser-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for a heavy cupboard”; `/blog/glass-display-cabinet-removal-dubai`; `/blog/freestanding-kitchen-trolley-dubai`
- **Why this slot:** A kitchen dresser or plate cupboard, not a bookshelf (DO NOT WRITE), not a glass display cabinet, and not the kitchen trolley already published.

#### Slot B — `PROPOSED — pending owner approval` — Strong — M34

- **ID:** M34
- **Primary keyword:** inflatable paddling pool removal dubai
- **Title:** An inflatable paddling pool, not a frame pool
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/inflatable-paddling-pool-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide for garden items”; `/blog/cooler-box-removal-dubai`
- **Why this slot:** A drained inflatable paddling pool, not an above-ground pool frame, not a hot tub, and not a water tank (all still blocked). The cooler-box article keeps the store-room ice box.

### Day 8 — Friday 4 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — K24

- **ID:** K24
- **Primary keyword:** florist waste collection dubai
- **Title:** Florist stem and bucket waste
- **Search intent:** Commercial waste / florist
- **Suggested URL:** `/blog/florist-waste-collection-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “a waste collection for the cut load”; `/blog/landscaping-waste-removal-dubai`; `/blog/grass-clippings-disposal-dubai`
- **Why this slot:** Cut stems, sleeves and buckets from a florist, not villa garden waste, grass clippings or a landscaping load.

#### Slot B — `PROPOSED — pending owner approval` — Strong — A48

- **ID:** A48
- **Primary keyword:** punching bag removal dubai
- **Title:** A standing punching bag in a spare room
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/punching-bag-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 7, 8 — 1 (junk removal Dubai); 7 (junk removal service in Dubai); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “junk removal for a heavy home item”; `/blog/treadmill-removal-dubai`
- **Why this slot:** One home punching bag, not a treadmill, and not an exercise bike, rowing machine or commercial gym load (those stay blocked or unpublished).

### Day 9 — Saturday 5 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — F31

- **ID:** F31
- **Primary keyword:** archive cartons home office dubai
- **Title:** Archive cartons from a home office
- **Search intent:** Situation / cardboard from a home office
- **Suggested URL:** `/blog/archive-cartons-home-office-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC6)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 3 — 3 (cardboard removal service)
- **Internal links:** `/services/junk-removal` — anchor: “collect the cartons with the junk”; `/blog/magazine-file-holder-dubai`; `/blog/shredded-paper-out-of-furniture-load-dubai`
- **Why this slot:** Closed archive cartons, not a magazine-file holder, not shredded paper inside a furniture load, and not a filing cabinet (DO NOT WRITE).

#### Slot B — `PROPOSED — pending owner approval` — Strong — C48

- **ID:** C48
- **Primary keyword:** drinks cabinet removal dubai
- **Title:** A drinks cabinet from a living room
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/drinks-cabinet-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for the cabinet”; `/blog/glass-display-cabinet-removal-dubai`; `/blog/sideboard-after-tv-removed-dubai`
- **Why this slot:** A closed drinks or bar cabinet, not a glass display cabinet and not a sideboard after the TV has gone.

### Day 10 — Sunday 6 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — M35

- **ID:** M35
- **Primary keyword:** hanging egg chair removal dubai
- **Title:** A hanging egg chair
- **Search intent:** Item / bulky outdoor or balcony
- **Suggested URL:** `/blog/hanging-egg-chair-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide”; `/blog/armchair-removal-dubai`; `/blog/balcony-clearance-dubai`
- **Why this slot:** A hanging egg or swing chair, including its stand, not an indoor armchair and not a whole balcony clearance.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — K25

- **ID:** K25
- **Primary keyword:** bakery waste collection dubai
- **Title:** Bakery trays and packaging at the end of the day
- **Search intent:** Commercial waste / bakery
- **Suggested URL:** `/blog/bakery-waste-collection-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “waste collection at close”; `/blog/office-waste-collection-dubai`
- **Why this slot:** End-of-day bakery trays and packaging, not a shop-fit clearance and not a restaurant equipment job.

### Day 11 — Monday 7 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — A49

- **ID:** A49
- **Primary keyword:** stepladder removal dubai
- **Title:** A stepladder that is being replaced
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/stepladder-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 2, 8 — 1 (junk removal Dubai); 2 (Dubai junk removal); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “include it in a junk collection”; `/blog/bolt-together-shelving-removal-dubai`
- **Why this slot:** A household stepladder, not bolt-together shelving and not a ceiling fan (still blocked).

#### Slot B — `PROPOSED — pending owner approval` — Strong — F32

- **ID:** F32
- **Primary keyword:** movers leftover cartons dubai
- **Title:** Cartons the movers did not take back
- **Search intent:** Situation / leftover moving cartons
- **Suggested URL:** `/blog/movers-leftover-cartons-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC6)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 3, 9 — 3 (cardboard removal service); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a cardboard pickup after the move”; `/blog/packing-material-disposal-dubai`; `/blog/shipping-cartons-filling-a-flat-dubai`
- **Why this slot:** Cartons a moving crew left behind, not the packing-material sort-out already published and not delivery cartons filling a flat.

### Day 12 — Tuesday 8 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — C49

- **ID:** C49
- **Primary keyword:** hallway bench removal dubai
- **Title:** A hallway bench that blocks the door
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/hallway-bench-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal from a narrow hall”; `/blog/shoe-cabinet-removal-dubai`; `/blog/coat-stand-removal-dubai`
- **Why this slot:** A hall bench, not a shoe cabinet, not a coat stand, and not a waiting-room chair stack.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — M36

- **ID:** M36
- **Primary keyword:** hammock stand removal dubai
- **Title:** A hammock stand with the fabric already packed
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/hammock-stand-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide for garden pieces”; `/blog/garden-furniture-disposal-dubai`
- **Why this slot:** A freestanding hammock frame, not a garden furniture set and not a hanging egg chair.

### Day 13 — Wednesday 9 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — K26

- **ID:** K26
- **Primary keyword:** classroom waste after term dubai
- **Title:** Classroom waste after the term ends
- **Search intent:** Commercial waste / school term-end
- **Suggested URL:** `/blog/classroom-waste-after-term-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “a waste collection after term”; `/blog/school-office-clearance-dubai`
- **Why this slot:** Bagged classroom waste after term, not a school-office furniture clearance and not a commercial gym or playground-equipment job.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — A50

- **ID:** A50
- **Primary keyword:** portable clothes rail removal dubai
- **Title:** A portable clothes rail after a move
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/portable-clothes-rail-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 7 — 1 (junk removal Dubai); 7 (junk removal service in Dubai)
- **Internal links:** `/` — anchor: “junk removal for leftover moving items”; `/blog/coat-stand-removal-dubai`; `/blog/drying-rack-removal-dubai`
- **Why this slot:** The rail itself, not a coat stand, not a drying rack, and not a clothes or textiles article (clothes stay DO NOT WRITE).

### Day 14 — Thursday 10 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — F33

- **ID:** F33
- **Primary keyword:** party rubbish chute will not take dubai
- **Title:** Party rubbish the chute will not take
- **Search intent:** Situation / rubbish after a party
- **Suggested URL:** `/blog/party-rubbish-chute-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 9, 10 — 9 (rubbish removal service); 10 (trash pickup Dubai)
- **Internal links:** `/services/junk-removal` — anchor: “a rubbish removal when the chute is the limit”; `/blog/duvets-that-will-not-fit-a-chute-dubai`; `/blog/what-dubai-bins-wont-take`
- **Why this slot:** Bagged party rubbish that will not go down a chute, not a duvet/pillow chute piece and not the general “what bins will not take” guide.

#### Slot B — `PROPOSED — pending owner approval` — Strong — C50

- **ID:** C50
- **Primary keyword:** chaise longue removal dubai
- **Title:** A chaise longue that will not turn the corner
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/chaise-longue-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal when the route is tight”; `/blog/armchair-removal-dubai`; `/blog/sofa-wont-fit-through-door-dubai`
- **Why this slot:** A chaise longue, not a wingback or recliner armchair, not an L-shaped sofa, and not a sofa bed.

### Day 15 — Friday 11 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — M37

- **ID:** M37
- **Primary keyword:** patio heater removal dubai
- **Title:** A patio heater, not a barbecue
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/patio-heater-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide”; `/blog/bbq-grill-disposal-dubai`
- **Why this slot:** A freestanding patio heater. The published BBQ guide keeps the grill and the fuel. Not a hot tub and not a fire pit, which has its own slot.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — K27

- **ID:** K27
- **Primary keyword:** community hall event waste dubai
- **Title:** Leftover waste after a community-hall booking
- **Search intent:** Commercial waste / venue after an event
- **Suggested URL:** `/blog/community-hall-event-waste-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “waste collection after the booking”; `/blog/office-waste-collection-dubai`
- **Why this slot:** Bagged leftover waste after a hall booking, not exhibition-stand waste (K20 stays blocked) and not a wedding-hall décor load, which has its own slot.

### Day 16 — Saturday 12 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — A51

- **ID:** A51
- **Primary keyword:** wheelbarrow removal dubai
- **Title:** A wheelbarrow and a rusted tool pile
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/wheelbarrow-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 2, 8 — 1 (junk removal Dubai); 2 (Dubai junk removal); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “a junk collection from the yard”; `/blog/garden-hose-reel-removal-dubai`; `/blog/garage-clearance-dubai`
- **Why this slot:** A wheelbarrow and loose hand tools, not a hose reel, not a full garage clearance, and not landscaping waste.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — F34

- **ID:** F34
- **Primary keyword:** takeaway container stack dubai
- **Title:** A takeaway-container stack in the kitchen
- **Search intent:** Situation / household rubbish volume
- **Suggested URL:** `/blog/takeaway-container-stack-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 9, 10 — 9 (rubbish removal service); 10 (trash pickup Dubai)
- **Internal links:** `/services/junk-removal` — anchor: “a rubbish pickup for the stack”; `/blog/what-dubai-bins-wont-take`
- **Why this slot:** A kitchen stack of takeaway containers the regular bin run will not clear in one go. Not packing material and not a chute article.

### Day 17 — Sunday 13 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — C51

- **ID:** C51
- **Primary keyword:** storage ottoman removal dubai
- **Title:** A storage ottoman at the end of a bed
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/storage-ottoman-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for the ottoman”; `/blog/bed-frame-disposal-dubai`; `/blog/bedroom-furniture-removal-dubai`
- **Why this slot:** A storage ottoman at the end of a bed, not a coffee table (DO NOT WRITE), not a chest of drawers, and not a whole bedroom set.

#### Slot B — `PROPOSED — pending owner approval` — Strong — M38

- **ID:** M38
- **Primary keyword:** portable basketball hoop removal dubai
- **Title:** A portable basketball hoop
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/portable-basketball-hoop-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide”; `/blog/trampoline-removal-dubai`
- **Why this slot:** A wheeled or base-weighted hoop, not a trampoline and not a children’s slide. Base water or sand is emptied by the owner before collection.

### Day 18 — Monday 14 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — K28

- **ID:** K28
- **Primary keyword:** dry cleaner hangers and film waste dubai
- **Title:** Dry-cleaner hangers and film
- **Search intent:** Commercial waste / dry cleaner
- **Suggested URL:** `/blog/dry-cleaner-hangers-film-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “a waste collection for the leftover hangers”; `/blog/shop-clearance-dubai`
- **Why this slot:** Hangers and film from a dry-cleaner, not a shop-fit clearance and not a clothes or textiles article (clothes stay DO NOT WRITE).

#### Slot B — `PROPOSED — pending owner approval` — Strong — A52

- **ID:** A52
- **Primary keyword:** kayak removal dubai
- **Title:** A kayak against a villa wall
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/kayak-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 8 — 1 (junk removal Dubai); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “junk collection for an awkward outdoor piece”; `/blog/villa-storage-clearance-dubai`
- **Why this slot:** A kayak or paddleboard stored against a wall or in a villa store, not a full villa-storage clearance and not a boat or marina-berth job.

### Day 19 — Tuesday 15 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — F35

- **ID:** F35
- **Primary keyword:** gift wrapping waste dubai
- **Title:** Wrapping paper and gift packaging after a celebration
- **Search intent:** Situation / rubbish and packaging after a celebration
- **Suggested URL:** `/blog/gift-wrapping-waste-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 9, 3 — 9 (rubbish removal service); 3 (cardboard removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a rubbish and cardboard pickup”; `/blog/packing-material-disposal-dubai`; `/blog/seasonal-clear-out-dubai`
- **Why this slot:** Gift wrap and packaging after a celebration, not move or delivery packing material and not a seasonal whole-home clear-out.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — C52

- **ID:** C52
- **Primary keyword:** toy chest removal dubai
- **Title:** A toy chest after the children have grown
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/toy-chest-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for the chest”; `/blog/childrens-room-clearance-dubai`
- **Why this slot:** A single toy chest, not a chest of drawers (DO NOT WRITE) and not a whole children’s-room clearance.

### Day 20 — Wednesday 16 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — M39

- **ID:** M39
- **Primary keyword:** kids plastic slide removal dubai
- **Title:** A children’s plastic slide
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/kids-plastic-slide-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide”; `/blog/trampoline-removal-dubai`; `/blog/plastic-playhouse-removal-dubai` (once live)
- **Why this slot:** A plastic slide, not a trampoline and not the playhouse in M32. Above-ground pool frames stay blocked.

#### Slot B — `PROPOSED — pending owner approval` — Strong — K29

- **ID:** K29
- **Primary keyword:** self storage unit waste collection dubai
- **Title:** Waste left when a self-storage unit is emptied
- **Search intent:** Situation / storage-unit waste
- **Suggested URL:** `/blog/self-storage-unit-waste-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “waste collection from the unit”; `/blog/storage-room-clearance-dubai`; `/blog/villa-storage-clearance-dubai`
- **Why this slot:** Discarded waste when a rented self-storage unit is emptied, not a household store-room clearance and not a villa store.

### Day 21 — Thursday 17 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — A53

- **ID:** A53
- **Primary keyword:** golf bag removal dubai
- **Title:** A golf bag from a hall cupboard
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/golf-bag-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 2, 8 — 1 (junk removal Dubai); 2 (Dubai junk removal); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “add it to a junk collection”; `/blog/suitcases-after-a-trip-dubai`
- **Why this slot:** A golf bag and clubs, not a suitcase set after a trip and not a general sports-equipment or commercial-gym article.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — F36

- **ID:** F36
- **Primary keyword:** villa guest weekend rubbish dubai
- **Title:** Bagged rubbish after a villa guest weekend
- **Search intent:** Situation / household rubbish
- **Suggested URL:** `/blog/villa-guest-weekend-rubbish-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 9, 10 — 9 (rubbish removal service); 10 (trash pickup Dubai)
- **Internal links:** `/services/junk-removal` — anchor: “a rubbish removal after the guests leave”; `/blog/weekend-junk-removal-dubai`
- **Why this slot:** Bagged rubbish left after guests, not a weekend booking-and-access guide and not a garage or villa-storage clearance.

### Day 22 — Friday 18 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — C53

- **ID:** C53
- **Primary keyword:** kids table and chairs removal dubai
- **Title:** A children’s table and chair set
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/kids-table-and-chairs-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for the set”; `/blog/dining-table-removal-dubai`; `/blog/dining-chairs-without-the-table-dubai`; `/blog/high-chair-removal-dubai`
- **Why this slot:** A small children’s set, not a dining table, not dining chairs without the table, and not a high chair.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — M40

- **ID:** M40
- **Primary keyword:** fire pit removal dubai
- **Title:** A fire pit or chimenea
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/fire-pit-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide”; `/blog/bbq-grill-disposal-dubai`; `/blog/patio-heater-removal-dubai` (once live)
- **Why this slot:** A fire pit or chimenea, not a BBQ grill and not a patio heater. Fuel and ash are dealt with by the owner before collection; the article will not invent disposal rules.

### Day 23 — Saturday 19 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — K30

- **ID:** K30
- **Primary keyword:** damaged parcel waste collection dubai
- **Title:** Damaged-parcel waste from a courier bay
- **Search intent:** Commercial waste / courier
- **Suggested URL:** `/blog/damaged-parcel-waste-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6, 3 — 6 (waste collection service Dubai); 3 (cardboard removal service)
- **Internal links:** `/services/waste-removal` — anchor: “waste collection from the bay”; `/services/junk-removal` — only if a sentence is about the cartons; `/blog/warehouse-clearance-dubai`
- **Why this slot:** Damaged parcels and their packaging from a courier or last-mile bay, not a warehouse clearance and not household shipping cartons.

#### Slot B — `PROPOSED — pending owner approval` — Strong — A54

- **ID:** A54
- **Primary keyword:** table tennis table removal dubai
- **Title:** A table-tennis table that will not fold
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/table-tennis-table-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 7, 8 — 1 (junk removal Dubai); 7 (junk removal service in Dubai); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “junk removal for a large home table”; `/blog/dining-table-removal-dubai`
- **Why this slot:** A table-tennis table, not a dining table and not a pool table (still blocked).

### Day 24 — Sunday 20 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — F37

- **ID:** F37
- **Primary keyword:** bagged rubbish when chute is out of use dubai
- **Title:** Bagged rubbish when the chute is out of use
- **Search intent:** Situation / rubbish when the chute is closed
- **Suggested URL:** `/blog/bagged-rubbish-chute-out-of-use-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC3)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 9, 10 — 9 (rubbish removal service); 10 (trash pickup Dubai)
- **Internal links:** `/services/junk-removal` — anchor: “trash pickup when the chute is out of use”; `/blog/party-rubbish-chute-dubai` (once live); `/blog/walk-up-stairs-no-lift-dubai`
- **Why this slot:** Household bags left at the door because the chute is closed or blocked, not party overflow and not a walk-up furniture-access guide.

#### Slot B — `PROPOSED — pending owner approval` — Strong — C54

- **ID:** C54
- **Primary keyword:** folding screen removal dubai
- **Title:** A folding screen in a home, not an office
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/folding-screen-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for the screen”; `/blog/freestanding-noticeboard-removal-dubai`
- **Why this slot:** A home folding screen or room screen, not an office partition or mannequin (both stay DO NOT WRITE), and not a freestanding noticeboard.

### Day 25 — Monday 21 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — M41

- **ID:** M41
- **Primary keyword:** garden statue removal dubai
- **Title:** A garden statue that has to come off a plinth
- **Search intent:** Item / bulky outdoor
- **Suggested URL:** `/blog/garden-statue-removal-dubai`
- **Cluster:** M · Bulky-waste guide support (SC1)
- **Money page:** `/blog/dubai-municipality-bulky-waste`
- **Supports targets:** 4 — 4 (bulky waste collection)
- **Internal links:** `/blog/dubai-municipality-bulky-waste` — anchor: “the bulky-waste guide”; `/blog/soil-sand-pots-disposal-dubai`; `/blog/garden-furniture-disposal-dubai`
- **Why this slot:** A statue or heavy garden ornament, not pots of soil and not a garden furniture set. A pergola, fence or deck stays blocked under G24.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — K31

- **ID:** K31
- **Primary keyword:** wedding hall decor waste dubai
- **Title:** Leftover décor after a wedding-hall event
- **Search intent:** Commercial waste / venue décor
- **Suggested URL:** `/blog/wedding-hall-decor-waste-dubai`
- **Cluster:** K · Waste collection (SC6)
- **Money page:** `/services/waste-removal`
- **Supports targets:** 6 — 6 (waste collection service Dubai)
- **Internal links:** `/services/waste-removal` — anchor: “waste collection after the event”; `/blog/community-hall-event-waste-dubai` (once live)
- **Why this slot:** Loose leftover décor and bagged waste after a wedding-hall event, not exhibition-stand waste (K20 stays blocked) and not restaurant furniture (K21 stays blocked).

### Day 26 — Tuesday 22 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — A55

- **ID:** A55
- **Primary keyword:** turntable removal dubai
- **Title:** A turntable and a crate of vinyl
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/turntable-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 8 — 1 (junk removal Dubai); 8 (Dubai junk collection)
- **Internal links:** `/` — anchor: “junk collection for the crate and the player”; `/blog/keyboard-and-amplifier-removal-dubai`; `/blog/e-waste-disposal-dubai`
- **Why this slot:** A turntable and vinyl crate, not a keyboard and amplifier, not a guitar, and not a general e-waste guide. A piano stays blocked.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — F38

- **ID:** F38
- **Primary keyword:** iftar packaging waste dubai
- **Title:** Iftar packaging after a home gathering
- **Search intent:** Situation / rubbish after a gathering
- **Suggested URL:** `/blog/iftar-packaging-waste-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC3)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 9, 3 — 9 (rubbish removal service); 3 (cardboard removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a rubbish pickup after the gathering”; `/blog/pre-ramadan-clear-out-dubai`
- **Why this slot:** Packaging left after a home iftar, not the pre-Ramadan whole-home clear-out already published.

### Day 27 — Wednesday 23 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — C55

- **ID:** C55
- **Primary keyword:** headboard removal dubai
- **Title:** A headboard when the bed frame is staying
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/headboard-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for the headboard only”; `/blog/bed-frame-disposal-dubai`; `/blog/mattress-disposal-dubai`
- **Why this slot:** A headboard on its own, not a bed frame, not a mattress, and not a bunk bed or baby cot (both stay DO NOT WRITE).

#### Slot B — `PROPOSED — pending owner approval` — Adequate — F39

- **ID:** F39
- **Primary keyword:** burst bin bag on a landing dubai
- **Title:** A burst bin bag on a tower landing
- **Search intent:** Situation / trash in a common area
- **Suggested URL:** `/blog/burst-bin-bag-landing-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC3)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 10, 9 — 10 (trash pickup Dubai); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a trash pickup from the landing”; `/blog/bagged-rubbish-chute-out-of-use-dubai` (once live)
- **Why this slot:** A burst bag on a landing or bin-store floor, not a chute-closed situation and not illegal-dumping guidance already published.

### Day 28 — Thursday 24 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Strong — A56

- **ID:** A56
- **Primary keyword:** evaporative cooler removal dubai
- **Title:** An evaporative cooler at the end of summer
- **Search intent:** Item / household junk
- **Suggested URL:** `/blog/evaporative-cooler-removal-dubai`
- **Cluster:** A · Core junk collection (SC1)
- **Money page:** `/`
- **Supports targets:** 1, 2, 7 — 1 (junk removal Dubai); 2 (Dubai junk removal); 7 (junk removal service in Dubai)
- **Internal links:** `/` — anchor: “junk removal for the cooler”; `/blog/old-ac-unit-disposal-dubai`; `/blog/cooler-box-removal-dubai`; `/blog/pedestal-fan-removal-dubai`; `/blog/dehumidifier-removal-dubai`
- **Why this slot:** A desert or evaporative cooler, not an AC unit, not a store-room cooler box, not a pedestal fan, and not a dehumidifier.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — F40

- **ID:** F40
- **Primary keyword:** bbq leftover trash bags dubai
- **Title:** Trash bags left after a barbecue
- **Search intent:** Situation / trash after a barbecue
- **Suggested URL:** `/blog/bbq-leftover-trash-bags-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 10, 9 — 10 (trash pickup Dubai); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a trash pickup for the leftover bags”; `/blog/bbq-grill-disposal-dubai`
- **Why this slot:** Bagged leftovers after a barbecue, not the grill or fuel, which stay on the published BBQ guide.

### Day 29 — Friday 25 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — C56

- **ID:** C56
- **Primary keyword:** bar cart removal dubai
- **Title:** A bar cart that is no longer used
- **Search intent:** Item / furniture
- **Suggested URL:** `/blog/bar-cart-removal-dubai`
- **Cluster:** C · Furniture (SC1)
- **Money page:** `/services/furniture-removal`
- **Supports targets:** 5 — 5 (furniture removal Dubai)
- **Internal links:** `/services/furniture-removal` — anchor: “furniture removal for the cart”; `/blog/freestanding-kitchen-trolley-dubai`; `/blog/drinks-cabinet-removal-dubai` (once live)
- **Why this slot:** A drinks bar cart or tea trolley, not a freestanding kitchen trolley and not a drinks cabinet.

#### Slot B — `PROPOSED — pending owner approval` — Adequate — F41

- **ID:** F41
- **Primary keyword:** garage sale leftover trash dubai
- **Title:** Leftover trash after a garage sale
- **Search intent:** Situation / trash after a sale
- **Suggested URL:** `/blog/garage-sale-leftover-trash-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 10, 9 — 10 (trash pickup Dubai); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a trash pickup after the sale”; `/blog/garage-clearance-dubai`
- **Why this slot:** Unsold bags and broken leftovers after a sale, not a full garage clearance of mixed stored goods.

### Day 30 — Saturday 26 December 2026

#### Slot A — `PROPOSED — pending owner approval` — Adequate — F42

- **ID:** F42
- **Primary keyword:** kids party trash bags dubai
- **Title:** Trash bags after a children’s party
- **Search intent:** Situation / trash after a children’s party
- **Suggested URL:** `/blog/kids-party-trash-bags-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 10, 9 — 10 (trash pickup Dubai); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a trash pickup after the party”; `/blog/party-rubbish-chute-dubai` (once live)
- **Why this slot:** A children’s-party trash load, not the adult party-and-chute article and not a toy-chest or children’s-room furniture piece.

#### Slot B — `PROPOSED — pending owner approval` — Strong — F43

- **ID:** F43
- **Primary keyword:** empty water bottle stack dubai
- **Title:** Empty water bottles the supplier will not take back
- **Search intent:** Situation / household trash volume
- **Suggested URL:** `/blog/empty-water-bottle-stack-dubai`
- **Cluster:** F · Rubbish, trash and cardboard (SC1)
- **Money page:** `/services/junk-removal`
- **Supports targets:** 10, 9 — 10 (trash pickup Dubai); 9 (rubbish removal service)
- **Internal links:** `/services/junk-removal` — anchor: “a trash pickup for the bottles”; `/blog/plumbed-water-dispenser-removal-dubai`
- **Why this slot:** Empty bottles a water supplier will not collect, not a plumbed dispenser and not a general recycling-centre article (M28 stays held).

---

## What this plan does not do

- It does not unblock G24, G25, G26, K20, K21, M28, M29 or M30. Those still need an owner decision or a verified source.
- It does not add area-doorway articles, and it does not move any of the 10 targets to a new URL.
- It does not schedule a Search Console review. That still depends on an export the owner shares.
- It does not change `next.config.mjs`, `package.json`, or the HTTP to HTTPS redirect.
- It is not a publishing instruction. Writing starts only after a yes on a named batch. Merging starts only after “Merge and live” for that batch.

---

## After approval

Once the owner is happy with this calendar:

1. Drop a copy of this file into `docs/content-system/` on a review branch, in a later PR, if the owner wants it in the repo.
2. Keep the first-plan workflow: ask before each day’s pair (or batch), write on a Cloud Agent from `main`, one PR, wait for “Merge and live”.
3. On publish, flip the written slots from REVIEW to PUBLISHED on the same PR, then merge.
4. The live article count at the start of this calendar is 155. After all 60 slots are live it would be 215, counted only as slots are actually published.

