# Storage Operations & Inventory Management Workflow

**Last Updated:** __________________ | **Supervisor:** __________________

## Overview
Complete procedures for organizing, storing, and maintaining inventory in the warehouse to maximize efficiency and accuracy.

---

## Storage Zone Map & Organization

### Warehouse Layout Reference

**Fast-Moving Items (High Turnover):**
- Zone A: Front of warehouse, nearest to packing stations
- Aisle 1-3: Daily picks, popular items
- Ground level: Heavy or bulky items

**Medium-Turnover Items:**
- Zone B: Middle section
- Aisle 4-7: Regular picks, moderate demand
- Mixed shelf levels

**Slow-Moving Items (Low Turnover):**
- Zone C: Back of warehouse
- Aisle 8-10: Occasional picks, seasonal items
- Upper shelves acceptable

### Storage Type by Product

| Product Type | Preferred Storage | Max Stack Height | Special Notes |
|--------------|-------------------|------------------|---------------|
| Seed & Food (bird) | Climate controlled, pallets | 4 pallets high | Check expiration dates |
| Bird Cages | Floor or low shelves | 3 units high | Fragile, nest inside each other |
| Toys & Accessories | Bins on shelving | Full shelf height | Small items, organize by type |
| Heavy Equipment | Floor/pallet racking | 1-2 high | Use forklift zones |
| Bulk/Overstock | Upper racks | Depends on system | Label clearly, less accessible |

---

## Putaway Process (Moving Items to Storage)

### Step 1: Receive Putaway Assignment
- [ ] Check receiving staging area for items awaiting storage
- [ ] Review putaway list from system
- [ ] Prioritize by urgency:
  - **P1:** Blocking receiving area (immediate)
  - **P2:** Fast-moving items needed for orders (within 1 hour)
  - **P3:** Standard stock (same shift)

### Step 2: Verify Item Information
Before moving any item to storage:
- [ ] Scan barcode or verify SKU manually
- [ ] Confirm quantity
- [ ] Check system for assigned location
- [ ] If no location assigned, determine based on:
  - Item size/weight
  - Turnover rate
  - Category/type
  - Available space

### Step 3: Locate Storage Spot

**System-Assigned Location:**
1. [ ] Navigate to Zone ___ Aisle ___ Shelf ___
2. [ ] Verify location is empty or has correct item
3. [ ] If occupied by wrong item, investigate and correct

**Manual Assignment (No system location):**
1. [ ] Identify appropriate zone based on item type
2. [ ] Find available space with sufficient room
3. [ ] Assign location code
4. [ ] Enter location in system
5. [ ] Label location clearly

### Location Code Format
`Z[Zone]-A[Aisle]-S[Shelf]-B[Bin]`

**Example:** Z-A-02-S-05-B-03 = Zone A, Aisle 2, Shelf 5, Bin 3

---

## Step 4: Store Item Properly

### General Storage Guidelines
- [ ] Heavy items on bottom, light on top
- [ ] Labels facing outward for easy scanning
- [ ] Items stored securely (won't fall)
- [ ] "First In, First Out" (FIFO) - new stock behind old stock
- [ ] Group similar items together
- [ ] Leave aisle space clear (no protruding items)

### Storage Method by Item Type

**Bins/Totes:**
- Use for small loose items
- Label bin with contents and quantity
- Don't overfill - should close properly
- Stack bins of same size only

**Shelving:**
- Distribute weight evenly
- Don't exceed shelf weight limit (usually marked)
- Use shelf dividers for small items
- Face labels forward

**Pallet Racking:**
- Ensure pallet is stable before racking
- Use proper forklift technique
- Check clearance above and below
- Secure load if needed (stretch wrap)

**Floor Storage:**
- Keep 18" from walls (fire code)
- Maintain aisle widths (usually 4-6 feet)
- Use pallet collars for unstable items
- Mark floor with tape if permanent location

---

## Step 5: Update System & Label

### System Entry
1. [ ] Scan item barcode
2. [ ] Scan location barcode (or enter manually)
3. [ ] Confirm quantity stored
4. [ ] Mark putaway complete in system
5. [ ] Print confirmation if required

### Physical Labels
- [ ] Location label on shelf/bin (if not already present)
- [ ] Item label on product (if needed)
- [ ] Quantity tag on pallet/box
- [ ] Date received tag for perishables

**Labeling Best Practices:**
- Use clear, large fonts
- Laminate labels in humid areas
- Include date on perishable items
- Add "FRAGILE" or "HEAVY" warnings as needed

---

## Inventory Organization Best Practices

### ABC Classification System

**A Items (High Value/High Turnover) - 20% of items, 80% of value:**
- Prime locations (easy access)
- Frequently cycle counted
- Tight inventory control
- Examples: Popular bird seed, best-selling cages

**B Items (Medium Value/Turnover) - 30% of items, 15% of value:**
- Standard locations
- Regular cycle counts
- Moderate control
- Examples: Mid-range toys, accessories

**C Items (Low Value/Turnover) - 50% of items, 5% of value:**
- Less accessible locations acceptable
- Annual cycle counts
- Basic control
- Examples: Specialty items, slow-moving stock

### Slotting Strategy

**Goal:** Minimize picker travel time, maximize efficiency

**Rules:**
1. **Fast movers near packing** - Place top 100 SKUs in front zone
2. **Similar items together** - All bird seed in one area, all cages together
3. **Order patterns** - Items often ordered together should be close
4. **Size considerations** - Heavy/bulky items at ground level
5. **Seasonal adjustment** - Move holiday items to prime spots during season

---

## Cycle Counting & Accuracy

### Daily Cycle Count Process

**Target:** Count minimum 5% of locations per day = 100% inventory monthly

### Cycle Count Procedure
1. [ ] Select locations to count (system-generated list)
2. [ ] Navigate to location
3. [ ] Count physical items (don't look at system first)
4. [ ] Enter actual count in system
5. [ ] If discrepancy, recount to verify
6. [ ] Investigate and adjust if count confirmed

### Cycle Count Log
| Date | Location | SKU | System Qty | Physical Qty | Variance | Reason/Action |
|------|----------|-----|------------|--------------|----------|---------------|
|      |          |     |            |              |          | ☐ Corrected ☐ Investigating |
|      |          |     |            |              |          | ☐ Corrected ☐ Investigating |
|      |          |     |            |              |          | ☐ Corrected ☐ Investigating |

### Common Variance Reasons
- **Picking error:** Item picked but not scanned
- **Putaway error:** Item stored in wrong location
- **Theft/damage:** Item lost or damaged, not documented
- **System error:** Data entry mistake during receiving
- **Duplicate scan:** Same item scanned twice

**Investigation Steps:**
1. Check recent transaction history for that SKU
2. Look for item in nearby locations (misplaced)
3. Review security footage if suspected theft
4. Interview staff who handled item recently
5. Adjust system after confirming actual count

---

## Inventory Replenishment

### Picking Location Replenishment

**Trigger:** Bin/location reaches minimum threshold (usually 20% capacity)

### Replenishment Process
1. [ ] System generates replenishment task
2. [ ] Go to bulk/overstock location
3. [ ] Retrieve needed quantity
4. [ ] Transport to picking location
5. [ ] Stock picking location (FIFO - new behind old)
6. [ ] Scan to confirm replenishment in system
7. [ ] Update bulk location quantity

### Replenishment Priority
- **Priority 1:** Location empty, orders waiting
- **Priority 2:** Below minimum, will run out today
- **Priority 3:** Below optimal, plan for tomorrow

---

## Stock Rotation & FIFO Management

### Why FIFO Matters
- Prevents expiration of dated products
- Ensures product quality (older stock sold first)
- Reduces waste and spoilage
- Maintains customer satisfaction

### FIFO Implementation
**For Dated Products (food, medicines):**
1. [ ] Always check expiration dates during receiving
2. [ ] Store new stock behind existing stock
3. [ ] Use date stickers if not printed on product
4. [ ] Weekly expiration check (remove items < 30 days to expiry)
5. [ ] Flag slow-moving items approaching expiration

**For Non-Dated Products:**
1. [ ] Mark received date on boxes/pallets
2. [ ] Place new deliveries at back
3. [ ] Pull from front for orders
4. [ ] Quarterly rotation check for slow movers

### Expiration Alert System
| SKU | Product Name | Current Location | Expiration Date | Qty on Hand | Action Needed |
|-----|--------------|------------------|-----------------|-------------|---------------|
|     |              |                  |                 |             | ☐ Discount ☐ Donate ☐ Destroy |
|     |              |                  |                 |             | ☐ Discount ☐ Donate ☐ Destroy |
|     |              |                  |                 |             | ☐ Discount ☐ Donate ☐ Destroy |

---

## Inventory Adjustments

### When to Adjust Inventory
- Cycle count variance confirmed
- Damaged items found
- Items expired and removed
- Customer returns processed
- Theft/loss documented

### Adjustment Process
1. [ ] Identify discrepancy
2. [ ] Document reason for adjustment
3. [ ] Obtain supervisor approval (if required by policy)
4. [ ] Enter adjustment in system with reason code
5. [ ] Take photo of damaged/discarded items (if applicable)
6. [ ] File adjustment report

### Reason Codes
- **DAM:** Damaged in warehouse
- **EXP:** Expired/out of date
- **LOST:** Cannot locate (lost/stolen)
- **CYC:** Cycle count adjustment
- **RET:** Customer return adjustment
- **REC:** Receiving error correction
- **PICK:** Picking error correction

---

## Warehouse Organization & 5S Method

### 5S Principles for Storage Areas

**1. Sort (Seiri) - Separate needed from unneeded:**
- [ ] Remove obsolete/discontinued items
- [ ] Clear out damaged items
- [ ] Relocate misplaced items
- [ ] Remove personal items from work areas

**2. Set in Order (Seiton) - Organize and label:**
- [ ] Assign home location for every item
- [ ] Label all locations clearly
- [ ] Create logical flow patterns
- [ ] Mark aisles and zones

**3. Shine (Seiso) - Clean and inspect:**
- [ ] Sweep aisles daily
- [ ] Wipe down shelves weekly
- [ ] Inspect racking for damage
- [ ] Remove trash/packaging promptly

**4. Standardize (Seiketsu) - Create standards:**
- [ ] Document storage procedures
- [ ] Train all staff on standards
- [ ] Use visual management (color coding, signs)
- [ ] Establish routine schedules

**5. Sustain (Shitsuke) - Maintain discipline:**
- [ ] Daily audits of storage areas
- [ ] Hold team accountable
- [ ] Continuous improvement mindset
- [ ] Celebrate good practices

---

## Storage Area Inspection Checklist

### Daily Checks (5 minutes)
- [ ] Aisles clear and accessible
- [ ] No obvious safety hazards
- [ ] Spills cleaned up
- [ ] Trash removed
- [ ] Equipment properly stored

### Weekly Checks (15 minutes)
- [ ] Shelf labels accurate and readable
- [ ] Inventory in correct locations
- [ ] No overloaded shelves
- [ ] Proper FIFO rotation maintained
- [ ] Storage areas organized and neat

### Monthly Checks (30 minutes)
- [ ] Racking system secure (bolts tight, no damage)
- [ ] Fire extinguishers accessible
- [ ] Emergency exits clear
- [ ] Lighting adequate
- [ ] Floor markings visible
- [ ] Storage plan optimized (slotting review)

---

## Common Storage Problems & Solutions

### Problem: Running out of space
**Solutions:**
- Review slow-moving items (can they be returned to vendor?)
- Optimize vertical space (use upper racks)
- Consolidate partial bins/locations
- Implement more aggressive FIFO (sell through old stock)
- Request additional racking or off-site storage

### Problem: Can't find items (incorrect locations)
**Solutions:**
- Enforce scan requirements during putaway
- Daily cycle counts of problem locations
- Simplify location labeling system
- Train staff on importance of accuracy
- Implement location verification steps

### Problem: Damage during storage
**Solutions:**
- Review stacking methods (lighter on top)
- Add protective materials (wrap, dividers)
- Improve shelf/bin organization
- Train on proper handling techniques
- Investigate forklift operator skills

### Problem: Slow putaway (bottleneck at receiving)
**Solutions:**
- Assign dedicated putaway staff during busy times
- Pre-assign locations during receiving
- Use mobile devices for faster system updates
- Batch putaway by zone (reduce travel)
- Set time standards and track performance

---

## Storage Performance Metrics

### Key Metrics to Track

**Inventory Accuracy:**
- Formula: (Locations accurate / Total locations counted) × 100
- Target: 98%+
- Track weekly

**Putaway Speed:**
- Formula: Total items put away / Total hours
- Target: 50+ items/hour (varies by item type)
- Track daily

**Space Utilization:**
- Formula: (Used space / Total available space) × 100
- Target: 85-90% (leave room for flexibility)
- Track monthly

**Picker Travel Time:**
- Formula: Average distance traveled per pick
- Target: Minimize (through optimal slotting)
- Track during time studies

---

## Quick Reference Guide

### Storage Decision Tree

**New item received, where to store?**
1. Is it a fast mover (ordered daily)? → Zone A, ground level
2. Is it medium turnover (ordered weekly)? → Zone B, standard shelves
3. Is it slow/seasonal? → Zone C, upper shelves acceptable
4. Is it oversized/heavy? → Floor storage or low pallet racks
5. Is it fragile/valuable? → Secure area, careful handling

### Storage Zone Quick Reference

| Zone | Purpose | Typical Items | Access Frequency |
|------|---------|---------------|------------------|
| A | Fast movers | Top 100 SKUs | Multiple times/hour |
| B | Regular stock | Standard inventory | Multiple times/shift |
| C | Slow movers | Seasonal, specialty | Few times/week |
| O | Overstock/Bulk | Backup inventory | As needed for replenishment |
| R | Returns holding | Items being processed | Daily processing |
| D | Damaged/Dispose | Awaiting decision | Weekly review |

---

**Completed By:** _______________________ | **Date:** __________ | **Time:** __________
