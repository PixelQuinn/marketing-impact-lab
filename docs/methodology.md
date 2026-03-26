# Methodology

This project evaluates how intentional marketing actions affect portfolio traffic and engagement on quinnreams.com.

## Core Measurement Areas
- Sessions
- Session source / medium
- Session campaign
- Project page views
- Project clicks
- GitHub clicks
- Resume clicks
- Email clicks

## Data Collection Process
Data is collected daily from GA4 after each day has fully completed.

The primary reports used are:
- **Traffic acquisition** for sessions and source / medium
- **Pages and screens** for project page views
- **Events** for click and custom interaction counts

## Daily Logging Rule
Metrics are logged only after a full day has completed to avoid partial-day reporting.

Each row in the tracking dataset represents:
- one date
- one experiment name
- one phase
- one source / medium bucket

## Baseline and Experiment Design
This project uses a simple weekly experiment structure:

1. Collect a natural baseline
2. Launch one focused marketing action
3. Measure traffic and engagement in GA4
4. Compare experiment results against baseline behavior
5. Document findings and next actions

## Week 1 Baseline Notes
The Week 1 baseline was collected before any LinkedIn activation. The purpose of this period was to establish a realistic pre-experiment picture of traffic and engagement.

Early baseline patterns showed:
- low and inconsistent traffic
- mostly direct traffic
- sporadic interaction behavior
- one unusually high day that should be treated as an outlier

## Interpretation Notes
Because traffic volume is currently low, early results should be interpreted as directional rather than definitive.

Also, click-based metrics in this project represent **interaction counts**, not unique users. A single visitor may trigger multiple events.