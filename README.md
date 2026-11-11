# UPSC 2027 Test-Driven Study Planner

Updated test schedule:
- 1 January–24 April 2027: tests every alternate day.
- The alternate-day schedule includes two timed tests each for GS Paper I, GS Paper II, GS Paper III and GS Paper IV, interleaved with Prelims GS and CSAT practice.
- 25 April–20 May 2027: a Prelims-focused test/practice paper every day.
- 25 May–19 August 2027: a Mains paper or timed answer-writing session every day, rotating GS I–IV, Essay, Chemistry Optional Papers I and II, and GS answer-writing drills.

## Publish the updated app on GitHub Pages

1. Download and extract this ZIP.
2. Open your repository: `Manmohan1225/upsc-2027-study-planner`.
3. Upload/replace the files at the repository root: `index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `.nojekyll`, and `README.md`.
4. Commit the changes to the `main` branch.
5. GitHub Pages will redeploy automatically. Open:
   `https://manmohan1225.github.io/upsc-2027-study-planner/`
6. If the old version remains visible, refresh the page. If installed as a PWA, close it and reopen after the service worker updates.

## Features
- Exact daily timetable: 6:00–8:00 AM Chemistry; 8:30–10:00 AM new GS; 10:30 AM–12:00 PM revision; 1:00–2:00 PM current affairs; 2:00–3:00 PM MCQs/CSAT; 4:00–5:00 PM answer writing; 5:00–6:00 PM Chemistry PYQs.
- Scheduled timed tests/papers use the 2:00–5:00 PM reserved slot on test days, replacing the usual afternoon practice blocks.
- Dated study roadmap.
- GS and Chemistry Optional topic checklist.
- Filterable test calendar.
- Test completion marks.
- Test score and mistake log.
- Browser-local progress storage.
- PWA manifest and offline app-shell caching.

## Data
Progress is stored in browser localStorage on the device. It does not sync between devices. Export or separately record important scores and notes.

## Exam dates
The dates are planning targets. Verify the latest UPSC official calendar and notification; the app does not guarantee exam dates or test-series bookings.

## Exact daily chapter assignment (latest update)
The Dashboard and Daily Routine now show the chapter/topic assigned to each exact time slot for the selected date. Use the date picker to preview another day. The assignment follows the dated topic roadmap and test calendar. Some later Mains dates use phase-level topic assignments, so align the exact subtopic with the official syllabus and your remaining gaps.

## Smart daily assignment and progress (v5)
- GS topics and Chemistry Optional subtopics rotate by date within the dated syllabus phase.
- Revision assigns a specific chapter by weekday and rotates weekly.
- Dashboard includes daily, weekly and monthly study-block completion, weekly/monthly test completion, and weekly topic completions.
- Date selector previews the plan and progress period for the selected date.

## Daily study target update (v6)
- Daily focused study target increased from 9 to 11 hours.
- Added 7:00–9:00 PM evening revision: 7:00–8:00 PM active recall of a completed GS subject; 7:00–8:00 PM revise the day's GS topic, solve 20 PYQs and update the error notebook.
- Checklist and daily/weekly/monthly study progress now use 8 study blocks and an 11-hour target.
- On test days, use 5:00–6:00 PM for test analysis and retain 7:00–9:00 PM for evening revision.

## Flexible unfinished-task carry-forward (v7)
- When the app is opened on a new date, unfinished blocks from the previous saved study day are automatically added to a carry-forward queue.
- The 7:00–9:00 PM slot prioritises carried-forward tasks. If pending work exceeds two hours, the app advises spreading it across following evenings rather than attempting an unrealistic overload.
- Mark carried-forward items Done to remove them from the queue. When no tasks are pending, use 7:00–9:00 PM for GS active recall, today's topic revision, 20 PYQs and the error notebook.


## Evening slot update
The flexible catch-up and revision slot is now 7:00–9:00 PM. Use 7:00–8:00 PM for active recall and 8:00–9:00 PM for today's GS topic, 20 PYQs and error-notebook updates when no carryover tasks are pending.


V15 FINAL UPDATE: Chemistry Optional first syllabus coverage is scheduled through 25 March 2027. From 26 March onward, the app assigns a structured Paper I and Paper II revision cycle (26 March–20 May), followed by continued sectional revision and full-length Optional papers through the Mains preparation period. Alternate 7–9 PM evenings switch from new-chapter sprint to Chemistry revision after 25 March.


V16 FINAL: The daily dated plan now uses the detailed UPSC Chemistry syllabus blocks from 11 Nov 2026 through 25 Mar 2027. The Chemistry tracker contains 67 line-item subtopics covering all sections of Paper I and Paper II. From 26 Mar 2027 the daily topic assignment switches to a topic-wise revision cycle, then sectional tests and full-length Paper I/II practice. The official syllabus reference used is the UPSC Civil Services Examination 2025 notice, Chemistry syllabus pages 49–51; confirm against the 2027 notice when published.
