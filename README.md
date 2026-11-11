# Flight Calibration Checklist (9 packs)

Field session for calibrating the flight model (body drag, H-force, propeller
dynamic performance, frame lift and vortex ring state) from blackbox logs and
DVR, on the Lightswitch Racing stack.

- **Configurations:** A = 477 g (no ballast attached), B = 677 g (one attached), C = 877 g (both attached).
- **Legend:** ★ must fly · ○ fly if battery allows.
- **Throttle values** are what the OSD throttle element shows (stick position).
  With 5.5% idle, the motors get about 5.5% + 0.945 × that, so 0% on the OSD is
  idle, not off.

---

## Session setup (once)

**Course**
- [ ] Flags every 4 m over 200 m, measured with a tape or wheel, in a straight
  line along the wind direction.
- [ ] Start, end and middle flags in a distinct colour.
- [ ] Run-up of 100 m or more each end, 200 m or more for full-throttle passes,
  plus clear braking room.

**Level platform and accelerometer bias**
- [ ] Level the platform to 0.1°. Check the phone level by turning it 180° on
  the same spot. Stake it firm and level it again.
- [ ] Tape the drone's position on the platform.
- [ ] **Propellers off:** drone on the platform, start the DVR, arm, record
  10 s → rotate 180° in yaw by hand → record 10 s → disarm.
- [ ] **Do not recalibrate the accelerometer after this.**

**Ballast, conditions, spotter**
- [ ] **Start only if the wind is under about 3 m/s and steady.** Save packs A3
  and C3 (vertical descents) for the calmest part of the session.
- [ ] **Spotter:** has the note sheet, calls out each item, and writes down what
  was flown and any bad passes.

---

## Every pack

**Before**
- [ ] Motors cool to the touch.
- [ ] Erase the blackbox flash.

**Start**
- [ ] Drone on the platform at the taped position.
- [ ] **Start the DVR, then arm.**
- [ ] **Ground recording:** idle, hands off, no throttle, **10 s**.
- [ ] **Hover:** **15 s** as still as possible at 3–5 m. ○ Add one slow 360° yaw
  turn (about 8 s) as a bias cross-check.

**After**
- [ ] Land, then **disarm before stopping the DVR**.
- [ ] Download the log and name the log and DVR file with the pack ID (e.g. `A2`).
- [ ] Note anything aborted.
- [ ] Cool the motors and battery before the next pack.

---

## How to fly a pass

1. Start beyond the end of the course, leaving enough run-up.
2. Settle at the target attitude **before the first flag**.
3. Hold the stick fixed. Use throttle only to stay level, at 3 m or higher. Keep
   the **same distance from the flag line** both ways.
4. Hold steady **through the last flag + 1 s**, then brake and turn.
5. Fly the return leg the same way. That's one **pair**.
6. **A pitch off its target is fine** because it's measured. Steadiness through
   the timed stretch is what matters.

---

## Pack 1: A1 (477 g)

*Shallow-to-moderate pitch passes.*

- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **5°** pair (about 9 m/s)
- [ ] ★ **10°** pair (about 13 m/s)
- [ ] ★ **20°** pair (about 17 m/s)
- [ ] ★ **30°** pair (about 21 m/s)
- [ ] ★ **45°** pair (about 26 m/s)
- [ ] ○ **10°** repeat pair
- [ ] ○ **30°** repeat pair
- [ ] ○ **3°** pair

## Pack 2: A2 (477 g)

*Sideways drag, frame lift, top speed. Full throttle last.*

- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **Sideways pairs:** yaw 90° (the same way every time) and fly the course
  sideways.
  - [ ] 15° roll 
  - [ ] 30° roll
  - [ ] 45° roll
- [ ] ★ **Chop pair at 20° pitch**, at **20 m or higher**:
  - 2–3 flags steady and level.
  - Then chops along the whole course: **0.8 s at zero throttle, about 1.2 s of
    power**, repeated. Hold attitude during each chop and recover height on each
    power segment.
  - Then 2–3 flags steady and level after the last chop.
- [ ] ★ **Chop pair at 45° pitch** (same pattern).
- [ ] ★ **50% throttle** pair (about 70–75° pitch) at **20 m or higher**. Hold
  height carefully.
  - ○ After the last flag on each leg: **pitch-sweep chop**: throttle to zero,
    ease the nose smoothly up towards level over about 1 s, then recover.
- [ ] ★ **100% throttle** pair (about 80° pitch), **last**. Long run-up, settled
  before the first flag, clear braking area.

## Pack 3: A3 (477 g, hover about 14% on the OSD)

*Vertical airflow. All at height. Fly in calm air (under about 2 m/s at
altitude).*

- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **Vertical descents ×4**, shallowest first.

  | Cut | OSD throttle | Start height | Hold |
  |---|---|---|---|
  | 1 | about 9% | 40 m or higher | 5 s |
  | 2 | about 6% | 50 m or higher | 4–5 s |
  | 3 | about 3% | 60 m or higher | 3–4 s |
  | 4 | 0% (idle) | 60 m or higher | 3 s |

  - **Each descent:**
    - Hover steady 3 s.
    - Cut the throttle in one clean move and **hold the stick still**. Keep level
      and **let the drone drift with the wind**; don't correct position or yaw.
    - Recover to hover throttle, then hover steady 3 s.
  - **If it shakes or won't stop sinking: pitch forward and fly out, then return
    to a steady hover.**
  - Stop a hold early if the ground comes up faster than expected.
- [ ] ★ **Vertical climbs ×2:** at 20 m or higher, hover 3 s → throttle step up
  and hold **2–3 s** → hover steady 3 s.
  - [ ] Small step: about **24%** on the OSD (hover × 1.5)
  - [ ] Larger step: about **34%** on the OSD (hover × 2)
- [ ] ★ **Hover throttle steps ×4:** at 10 m or higher, hover → +30% for
  **0.3 s** → hover, about 3 s apart.
- [ ] ○ **Reversals ×3:** from high throttle pass, do the same quick 180° at the
  middle flag each time, then hover.

## Pack 4: B1 (677 g, one weight attached)

*Speeds about 1.19× A's.*

- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **5°** pair
- [ ] ★ **10°** pair
- [ ] ★ **20°** pair
- [ ] ★ **30°** pair
- [ ] ★ **45°** pair

## Pack 5: B2 (677 g, hover about 19% on the OSD)

- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **20°** repeat pair
- [ ] ★ **50% throttle** pair
- [ ] ★ **100% throttle** pair, **last**
- [ ] ○ **Vertical descents ×2**, same method as A3.

  | Cut | OSD throttle | Start height | Hold |
  |---|---|---|---|
  | 1 | about 7% | 60 m or higher | 4 s |
  | 2 | about 2% | 70 m or higher | 3 s |

## Pack 6: C1 (877 g, both weights attached)

*Speeds about 1.36× A's. Shorter packs: watch the voltage.*

- [ ] **One gentle familiarisation circuit** first. It brakes and turns slower at
  this weight.
- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **5°** pair
- [ ] ★ **10°** pair
- [ ] ★ **20°** pair
- [ ] ★ **30°** pair
- [ ] ★ **45°** pair
- [ ] ○ **10°** repeat pair
- [ ] ○ **30°** repeat pair

## Pack 7: C2 (877 g)

- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **Sideways pairs** at 15°, 30° and 45° roll
- [ ] ★ **Chop pair at 20° pitch** (same pattern as A2, at 20 m or higher)
- [ ] ★ **Chop pair at 45° pitch**
- [ ] ★ **50% throttle** pair at **20 m or higher**, with ○ a pitch-sweep chop
  after the last flag on each leg (same as A2)
- [ ] ★ **100% throttle** pair, **last**. Extra braking room at this weight.

## Pack 8: C3 (877 g, hover about 22% on the OSD)

*Calm air. It falls faster and needs more height and forward speed to recover.*

- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **Vertical descents ×4**, same method as A3.

  | Cut | OSD throttle | Start height | Hold |
  |---|---|---|---|
  | 1 | about 14% | 50 m or higher | 5 s |
  | 2 | about 10% | 60 m or higher | 4–5 s |
  | 3 | about 5% | 80 m or higher | 3–4 s |
  | 4 | 0% (idle) | 80 m or higher | 3 s |

- [ ] ★ **Vertical climbs ×2**, same method as A3:
  - [ ] Small step: about **36%** on the OSD (hover × 1.5)
  - [ ] Larger step: about **50%** on the OSD (hover × 2)
- [ ] ★ **Hover throttle steps ×3**
- [ ] ○ **Reversals ×3**

## Pack 9: R (477 g)

*Repeatability check plus redos.*

- [ ] Re-weigh. It should match pack 1.
- [ ] Ground recording 10 s · Hover 15 s
- [ ] ★ **20°** pair
- [ ] ★ **45°** pair
- [ ] ★ **100% throttle** pair
- [ ] ○ Redo passes marked bad earlier (sideways and 5° first).
- [ ] Final wind speed and direction, and temperature.

---


## If things go wrong

- **A pack runs short:** drop ○ items first, then reversals → climbs → B2's
  descents → repeat pairs. Never skip the ground recording and hover.
- **Wind over about 3 m/s or gusty:** postpone the 5° and sideways passes, and
  fly the steeper passes meanwhile. Wait for calm air for A3 and C3.
- **A pack can't be used:** drop pack R first, then merge B2 into B1 (keep the
  50% and 100% pairs).
- **A pass goes wrong** (gust, height change, wobble): the spotter marks it bad.
  Fly it again only if the battery allows.
- **The drone disarms mid-pack** (crash or failsafe): re-arm with the DVR still
  running. The new arm gives a fresh sync point.
