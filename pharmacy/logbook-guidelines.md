# 📘 Unified Logbook Guidelines: UBC Pharmacy High-Pressure Steam Plant

The following unified, comprehensive logbook guidelines combine UBC Pharmacy
Plant requirements with modern industrial operations standards (including ALCOA
Data Integrity principles and the Symptom-Cause-Resolution format).

## 📘 Part 1: Core Professional & Legal Standards

The logbook is a legal business record and a critical safety document. It must
provide a flawless chronological audit trail of the plant's history.

- **Format Integrity:** Use permanent, waterproof black or blue ink. Never use
  red ink (traditionally reserved for Chief Engineer reviews, inspections, or
  safety device failures).

- **Errors & Edits:** Never erase, scratch out, use correction fluid, or write
  over an entry. Draw a single neat line through the error, write the
  correction, and initial the change.

- **Factual Objectivity:** Logbooks are not free-form diaries or complaint
  books. Every note must be factual, specific, and action-oriented.

- **ALCOA Data Integrity:** All entries must be Legible, Contemporaneous
  (recorded immediately at the time of the event), Original, and Accurate.

## 🕒 Part 2: Shift Structure & Timeline (ALCOA Flow)

Every shift must be bookended by clear timeline records to preserve the chain of
custody and plant responsibility.

### 1. Shift Start (The Handover Entry)

- **Date & Shift Duration:** Write the exact calendar date, shift hours, and
  crew number.
- **Licensed Operators:** List the full names and certificate classes of all
  operators on shift.
- **Current Plant Status:** State the running/standby status of all major
  equipment (Boilers 3–6, FWT-2, Water Softener).

#### Example Start-of-Shift Entry:

July 15, 2026 | Day Shift (07:00 - 19:00 hrs) | Crew #31S

> Assumed shift responsibility: Operating Engineer Aaron Vasi (4th Class, Cert
> #XXXXXX).
>
> Initial Plant Status: Boilers 3 and 5 in automatic remote modulation under
> Hawk Master control; Boilers 4 and 6 in cold standby[cite: 375, 725, 883].
> FWT-2 at 65% level, operating temperature at 172°F[cite: 462, 1542]. Water
> Softener online, normal operation[cite: 416].

### 2. End-of-Shift Sign-off

You must clearly print your name in **BLOCK CAPITALS**, followed by your
physical signature. This legally completes the handover of plant responsibility.

---

## 📋 Part 3: What MUST Be Logged (Comprehensive List)

Beyond routine checks, you are legally and operationally required to record the
following events:

### 1. Daily Safety & Operational Baselines

- **Plant Assessment:** If the shift was completely normal and routine, log the
  minimum baseline:

> 06:00 hrs. plant assessed, routine shift.

- **Daily Inspections:** Record successful blowdowns of all operating boiler
  gauge glasses , testing of water level alarms , and visual checks on
  safety-relief valves.

### 2. Equipment Exceptions, Failures, & Maintenance

- **Maintenance & Repair:** Any maintenance action must identify the exact item,
  who performed the work (including external contractors/vendors), and the
  target resolution.
- **Isolation & Verification:** Log the exact time an asset was locked out
  (LOTO) and the exact time it was returned to active service.
- **Setpoint Modifications:** Any manual change to pressure setpoints, high/low
  limits, or lead-lag sequence parameters.

### 3. Water Chemistry & Environmental Compliance

- **Chemical Logs:** Log the numerical results of your daily Chem-Aqua water
  tests, chemical volumes added, and mud-drum bottom blowdowns.
- **Quench Verification:** Note that the blowdown tank discharge to the sewer
  was verified to be below the 65°C limit (normally targeting 60°C or lower).

## ✍️ Part 4: The Structured Entry Templates

To keep logs consistent across all shifts, use these two standardized entry
templates:

### Template A: Standard Operational Event (The 5-Step Rule)

For routine actions, vendor visits, or minor system shifts.

$$\text{Timestamp} \rightarrow \text{Equipment Identifier} \rightarrow \text{Status Change / Event} \rightarrow \text{Action Taken} \rightarrow \text{Final Status}$$

#### Example Operational Entry:

> 10:15 hrs. (Time) Chem-Aqua Representative (Identifier) on-site for monthly
> service check. (Event) Assisted with raw and treated water sampling on
> operating Boilers 3 and 5. Replaced reagent bottles in testing cabinet.
> (Action Taken) 11:00 hrs. Chem-Aqua representative off-site. Water testing
> station clean and restocked. (Final Status)

### Template B: Diagnostic & Repair (Symptom-Cause-Resolution)

Use this specific layout for any equipment faults, safety trips, or process
deviations.

| Field      | Entry Standard                                                        |
| ---------- | --------------------------------------------------------------------- |
| Symptom    | Describe the alarm, warning, or physical anomaly observed.            |
| Cause      | Detail the root cause found during diagnostic checks.                 |
| Resolution | Detail the steps taken to repair, reset, or bypass the system safely. |

#### Example Diagnostic Entry:

> 14:20 hrs. FWT-2 (Feed Water Tank 2)
>
> - **Symptom:** FWT-2 temperature indicating 194°F on dial thermometer and
>   rising. High-temperature alarm registered on DDC panel.
> - **Cause:** Found the thermodynamic steam trap on the inlet leg of the
>   primary sparging lance pressure-and-temperature regulating station failed
>   open, passing unregulated 100 PSIG steam directly into the tank.
> - **Resolution:** Isolated the primary sparging lance steam line. Switched
>   feed water heating over to the secondary sparging lance supplied by Boiler
>   6, maintaining temperature control between 160°F and 180°F. Isolated the
>   failed thermodynamic steam trap and submitted work order #99402 to the
>   Mechanical Supervisor for replacement.
> - **Status:** FWT-2 temperature stabilized at 171°F. Plant operating normally
>   under secondary sparger.
