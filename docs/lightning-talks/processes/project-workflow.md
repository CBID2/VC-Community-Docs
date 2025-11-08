---
id: project-workflow
title: 'Lightning Talk Project Workflow'
sidebar_label: 'Facilitator Guidelines'
keywords:
  - 'coffee table groups'
  - 'virtual coffee coffee table groups'
  - 'volunteer roles and responsibilities'
  - 'virtual coffee community'
  - 'community guides'
  - 'community documentation'
  - 'tech community'
  - 'online tech community'
  - 'community management'
  - 'community building'
  - 'monthly challenges'
  - 'virtual coffee monthly challenges'
  - 'lightning talk'
  - 'virtual coffee writers'
  - 'community writers'
  - 'volunteer roles in online community'
  - 'responsibilities of online community volunteers'
  - 'building a strong community'
  - 'guidelines for online community'
  - 'writing community documentation'
  - 'online community building strategies'
  - 'effective community management techniques'
  - 'monthly challenges for online communities'
  - 'planning online community events'
tags:
  - 'lightning talks'
---

## Overview

The function of the Lightning Talks Event is to allow opportunities for members of the community to have an intimate space to present on a tech topic for 5-15 minutes. When live-streaming as a members-only event, speakers can feel more comfortable as it's _their_ community listening and watching. However, their is still opportunity to impact a larger audience once the videos have been processed and put up on YouTube.

Below is the workflow for the Lightning Talks Event.

## Lightning Talk Workflow

<details>
  <summary>📊 View Lightning Talk Workflow Diagram</summary>
  <div style={{marginTop: '1rem'}}>

### Planning Phase

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'fontSize':'24px', 'fontFamily':'arial'}}}%%
flowchart LR
  %% Left Column - Team Forming
  subgraph A["👥 Team Forming"]
    direction TB
    A1["📢 Call for Team Members"]
    A2["👥 Onboard New Team"]
    A3["📝 Assign Coordinators"]
    A4["📋 Review Responsibilities"]
    A1 --> A2 --> A3 --> A4
  end

  %% Right Column - Initial Planning
  subgraph B["📋 Initial Planning"]
    direction TB
    B1["📅 Set Timeline"]
    B2["🎯 Define Goals"]
    B3["📝 Create Checklist"]
    B1 --> B2 --> B3
  end

  %% Flow between columns
  A4 --> B1

  %% Styling
  classDef default fill:#f5f5f5,stroke:#2e8555,stroke-width:3px,color:#1a1a1a,padding:15px;
  classDef process fill:#e6f3ed,stroke:#2e8555,stroke-width:3px,color:#1a1a1a;
  class A,B process;
```

  </div>
</details>


### CFP (Call For Proposals) {#cfp-section}

<details>
  <summary>📋 View CFP Process Diagram</summary>
  <div style={{marginTop: '1rem'}}>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'fontSize':'26px', 'fontFamily':'arial'}}}%%
flowchart LR
  %% Left Column - Proposal Collection
  subgraph A["📬 Proposal Collection"]
    direction TB
    A1["📣 CFP Opens"]
    A2["🧾 Collect Proposals"]
    A3{"Enough Proposals?"}
    A4["📢 Extend CFP Period"]
    A1 --> A2 --> A3
    A3 -- No --> A4 --> A2
  end

  %% Right Column - Scheduling
  subgraph B["📅 Scheduling"]
    direction TB
    B1["👩‍💻 Group by Topic"]
    B2["📅 Schedule Talks"]
    B3["📝 Send Confirmations"]
    B4["📅 Add to Calendar"]
    B5["📢 Share Schedule"]
    B1 --> B2 --> B3 --> B4 --> B5
  end

  %% Flow between columns
  A3 -- Yes --> B1

  %% Styling
  classDef default fill:#f0f7ff,stroke:#1976d2,stroke-width:3px,color:#0d47a1,padding:15px;
  classDef process fill:#e3f2fd,stroke:#1976d2,stroke-width:3px,color:#0d47a1;
  classDef decision fill:#fff8e1,stroke:#ff8f00,stroke-width:3px,color:#e65100;
  class A,B process;
  class A3 decision;
```

  </div>
</details>


### Speaker Prep {#speaker-prep-section}

<details>
  <summary>🎤 View Speaker Preparation Process</summary>
  <div style={{marginTop: '1rem'}}>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'fontSize':'24px', 'fontFamily':'arial'}}}%%
flowchart LR
  %% Left Column - Talk Preparation
  subgraph A["🗂 Talk Preparation"]
    direction TB
    A1["🗂 Organize Talks"]
    A2["✅ Send Checklists"]
    A3{"Info Missing?"}
    A4["📬 Request Info"]
    A1 --> A2 --> A3
    A3 -- Yes --> A4 --> A2
  end

  %% Right Column - Speaker Prep
  subgraph B["👤 Speaker Prep"]
    direction TB
    B1["📸 Collect Speaker Info"]
    B2["📁 Create Shared Folder"]
    B3["✅ Verify Materials"]
    B1 --> B2 --> B3
  end

  %% Flow between columns
  A3 -- No --> B1

  %% Styling
  classDef default fill:#f5f5f5,stroke:#2e8555,stroke-width:3px,color:#1a1a1a,padding:15px;
  classDef process fill:#e6f3ed,stroke:#2e8555,stroke-width:3px,color:#1a1a1a;
  classDef decision fill:#fff8e1,stroke:#ff8f00,stroke-width:3px,color:#e65100;
  class A,B process;
  class A3 decision;
```

  </div>
</details>


### Event {#event-section}

<details>
  <summary>🎭 View Event Day Process</summary>
  <div style={{marginTop: '1rem'}}>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'fontSize':'26px', 'fontFamily':'arial'}}}%%
flowchart LR
  %% Left Column - Pre-Event
  subgraph A["📋 Pre-Event"]
    direction TB
    A1["🧾 Final Prep & Tech Check"]
    A2["📨 Send Directions to Speakers"]
    A3["🔗 Share Event Link"]
    A4["⏰ Set Reminders"]
    A1 --> A2 --> A3 --> A4
  end

  %% Right Column - Event
  subgraph B["🎤 Event"]
    direction TB
    B1["🎬 Start Recording"]
    B2["🧑‍🏫 Talks Begin"]
    B3["❓ Q&A Session"]
    B1 --> B2 --> B3
  end

  %% Flow between columns
  A4 --> B1

  %% Styling
  classDef default fill:#f5f5f5,stroke:#2e8555,stroke-width:3px,color:#1a1a1a,padding:15px;
  classDef process fill:#e6f3ed,stroke:#2e8555,stroke-width:3px,color:#1a1a1a;
  class A,B process;
```

  </div>
</details>


### Post-Event {#post-event-section}

<details>
  <summary>📊 View Post-Event Process</summary>
  <div style={{marginTop: '1rem'}}>

```mermaid
%%{init: {'theme':'base', 'themeVariables': {'fontSize':'24px', 'fontFamily':'arial'}}}%%
flowchart LR
  %% Left Column - Video Editing
  subgraph A["🎥 Video Editing"]
    direction TB
    A1["📹 Process Recording"]
    A2["☁️ Upload to YouTube"]
    A3["📝 Add Description & Tags"]
    A4["🔗 Share Video"]
    A1 --> A2 --> A3 --> A4
  end

  %% Right Column - Follow-up
  subgraph B["📣 Follow-up"]
    direction TB
    B1["🙏 Thank Speakers"]
    B2["📊 Gather Feedback"]
    B3["📈 Review Metrics"]
    B4["📋 Document Learnings"]
    B1 --> B2 --> B3 --> B4
  end

  %% Flow between columns
  A4 --> B1

  %% Styling
  classDef default fill:#f5f5f5,stroke:#2e8555,stroke-width:3px,color:#1a1a1a,padding:15px;
  classDef process fill:#e6f3ed,stroke:#2e8555,stroke-width:3px,color:#1a1a1a;
  class A,B process;
```

  </div>
</details>


### Specifics {#specifics-section}

- 5-15 minutes on one topic
- Slides are optional
- Mentorship is provided if requested

### Timeline {#timeline-section}

#### Call for coordinators, mentors, and other teammates

- Happens before the cfp to create a smoother onboarding process
- Roles are clarified and onboarding occurs (specify what this looks like)
  - Early assign coordinators based on input (ie, Bekah will take Group 1)
    - This will allow quick response times.
- Team meeting

### CFP (Call For Proposals)

- This should end at least six weeks before the event.
- Start with a date and time TBA during proposal stage.
  - Ask in form if there are any times that don't work on that day.
- Make sure everyone fills out the form (which creates a Github issues)
- As soon as cfp closes, team lead creates groups
  - Who makes the initial contact? And via email or slack? -- this should be specified in the form. Maybe that's a question for the form?

#### Organizing talks

- Create big issue cards for each coordinator with checklist, but smaller chunks on Project board more closely tied to time (ie, collect initial info (bio, headshot, socials), one week from date (title, description, slides)
  - All of information should be in one central document or folder.
    - Within that folder, there is a checklist that has each category (initial info checklist, talk checklist, etc.)
    - Update checklist for each speaker (if they don't have slides, delete that section)
      -???? SHould the speaker be dropping them into that central location and the coordinator checks it off???
- Coordinators can check it off as they go and all the info will be in one place.

##### Week of

- Send message to speaker channel with direction the week of - Let them know there’s a lag between the stream and the speaker - Ask them to mute or better yet, hide your youtube stream
  (For ref: Bc there is a lag, if you’re watching and up next, you’ll be introduced before the next talk is over.)

### Communication {#communication-section}

#### For LT Team

- slack for quick communication and decisions and/or hype
- Discussions for conversations that should be preserved and talked through

#### With Speakers

- Slack -> Reminders, day of communication, a coordinator does fun things to get the speakers to use that private room
