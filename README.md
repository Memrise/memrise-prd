# Memrise — Product Requirements Document

## 1. Overview

**Product Name:** Memrise

**Purpose:** Memrise is a language learning platform that helps users learn new languages through immersive, culturally rich content delivered via native speaker videos, AI-powered conversations, community-created word lists, and story-based reading experiences. The product combines spaced repetition vocabulary learning with authentic cultural context to help learners progress from complete beginners to advanced speakers.

**Target Users:**
- Casual language learners exploring a new language for travel, fun, or personal enrichment
- Students preparing for language exams (GCSE, AP, A-Level, IGCSE)
- Professionals needing a second language for work or relocation
- Heritage speakers reconnecting with family languages
- Self-directed learners who prefer authentic, culturally immersive content over textbook-style drills

**Value Proposition:** Unlike traditional flashcard apps, Memrise immerses learners in real-world language through native speaker videos, AI conversation partners, and culturally grounded stories. The platform offers both structured self-study courses and a newer story-based reading experience, catering to learners at every level across 150+ languages.

**Deployment Model:** Web application (memrise.com / app.memrise.com), with companion mobile apps referenced throughout the product. The platform operates two interconnected products: the **Self-Study App** (classic vocabulary-focused learning) and **Memrise Stories** (narrative-based reading and cultural immersion).

---

## 2. Features

### 2.1 Marketing & Landing Page

| Feature | Description |
|---------|-------------|
| Landing Page | Public-facing marketing page with product pitch, press mentions (BBC, etc.), testimonials, "How it Works" overview, and call-to-action for signup |
| Exam Prep Promotion | Marketing section promoting exam preparation capabilities (note: dedicated exam prep page is no longer available as a separate product) |

![Landing Page](screenshots/01-landing-page.png)

![Landing Page Full](screenshots/01b-landing-page-full.png)

### 2.2 Signup & Onboarding

| Feature | Description |
|---------|-------------|
| Language Selection | Searchable grid of 150+ languages to learn, including major world languages and constructed/historical languages (Klingon, Latin, Esperanto, etc.) |
| Account Creation | Email/password registration, or social signup via Facebook and Apple. Password must be 6+ characters |
| Skill Level Assessment | 4-tier self-assessment: Learn from scratch, Getting started, Making good progress, Improving my skills |
| Learning Goals | Multi-select goals: Short trip, Moving abroad, Connect with friends & family, Work/school, Fun & brain exercise, Other |
| Word List Curation | AI-suggested word lists based on goals + browsable community word lists organized by topic |
| Commitment Selection | Three tiers: Free ("Just curious"), Free 3-day Pro trial ("Ready to get serious"), Go Pro ("I'm all in") |

![Language Selection](screenshots/02-signup-start.png)

![Signup Form](screenshots/03-onboarding-signup.png)

![Skill Level Selection](screenshots/05-course-home.png)

![Learning Goals](screenshots/06-onboarding-next.png)

![Word List Curation](screenshots/07-onboarding-daily-goal.png)

![Commitment Level](screenshots/08-learning-home.png)

### 2.3 Self-Study App (Classic Memrise)

| Feature | Description |
|---------|-------------|
| Dashboard / Home | Central hub showing current word list, lesson start button, learning journey progress, streak counter, and quick access to all features |
| Vocabulary Lessons | Structured lessons presenting new words with native speaker videos, audio pronunciations, literal translations, and cultural "Did you know?" tips |
| Video Quiz Testing | Multiple-choice quizzes using native speaker video clips — users identify what was said |
| Vocabulary Management | "My Words" section tracking words across three states: Learned, Heard, Used. Create custom word lists or review difficult words |
| Video Library | Filterable library of native speaker video lessons. Filter by: All, Ready to watch, Watched, Needs practice. Searchable by topic |
| Conversations (MemBot) | AI-powered chatbot for conversational practice. 150+ scenario-based conversations organized into "Chats" (open-ended) and "Missions" (goal-oriented) |
| Talk Prep (Beta) | 3-step guided conversation practice: Build (shape conversation), Learn (practice saying lines), Perform (say from memory). Sound Like a Local mode |
| AI Buddies (Beta) | Six AI-powered practice tools: Assistant (general guide), Sentence Builder, Pronunciation, Grammar, Role-Play, Conjugation |
| Community Word Lists | Browse thousands of user-created word lists organized by popularity and recency. Users can create and share their own lists |
| Streak Tracking | Daily learning streak counter encouraging consistent practice |
| My Journey | Progress tracker showing current learning stage (Absolute Beginner through Advanced) |

![Self-Study Dashboard](screenshots/29-classic-dashboard.png)

![Vocabulary Lesson — Word Card](screenshots/39-lesson.png)

![Video Quiz](screenshots/39c-lesson-test.png)

![Video Library](screenshots/31-videos.png)

![Conversations with MemBot](screenshots/32-conversations.png)

![Talk Prep (Beta)](screenshots/33-talk-prep.png)

![AI Buddies (Beta)](screenshots/34-ai-buddies.png)

![Vocabulary Management](screenshots/30-vocabulary.png)

![My Words](screenshots/41-my-words.png)

![Community Word Lists](screenshots/43-browse-community.png)

### 2.4 Memrise Stories

| Feature | Description |
|---------|-------------|
| Stories Onboarding | Separate 4-step onboarding: Name entry, Language selection (Spanish/French/English), Level (Beginner/Intermediate/Advanced), Interest selection from 10 categories |
| Stories Home | Personalized dashboard showing reading stats (stories reading, read once, total re-reads), recommended stories, and navigation |
| Story Library | Categorized collection of culturally immersive stories (Food & Markets, Community & Local Life, Traditions & Celebrations) with metadata: type (Short story, Scene, True story), reading time, and origin |
| 5-Step Reading Flow | Structured reading experience: 1) First Read (unassisted), 2) Discover (vocabulary, phrases, cultural insights), 3) Re-read (bilingual view), 4) Check (sentence reordering exercise), 5) Score (self-assessment) |
| Tap-to-Translate | Tappable words within stories that reveal translations on demand |
| Audio Playback | Story narration with normal and slow-speed (turtle icon) playback |
| Vocabulary Discovery | Post-reading breakdown into Key Phrases, Slang & Vocabulary, and Cultural Insights with "Save to Notebook" option |
| Bilingual Re-read | Side-by-side Spanish/English view with toggle to hide all translations |
| Story Order Exercise | Drag-and-drop sentence reordering comprehension check |
| Self-Assessment | Dual rating system: comprehension level (Lost → Crystal clear) and enjoyment (Loved it / Interesting / Not for me) plus difficulty rating |
| Notebook | Personal reference with 5 tabs: Words, Phrases, Cultural insights, Notes, Journal |
| Create Your Own Stories | User-generated story creation capability (shown in library footer) |
| Your Growth | Learning progress tracking (currently marked "Coming Soon") |
| Practice | Dedicated practice mode for review (currently marked "Coming Soon") |

![Stories Onboarding — Name](screenshots/10-stories-home.png)

![Stories Onboarding — Language](screenshots/11-stories-onboarding-step2.png)

![Stories Onboarding — Level](screenshots/12-stories-onboarding-step3.png)

![Stories Onboarding — Interests](screenshots/13-stories-onboarding-step4.png)

![Stories Dashboard](screenshots/14-stories-dashboard.png)

![Story Detail & Prediction](screenshots/15-story-detail.png)

![First Read](screenshots/16-story-reading.png)

![Story Text with Tappable Words](screenshots/16b-story-text.png)

![Rate & Review](screenshots/17-story-rate-review.png)

![Discover — Overview](screenshots/18-story-discover.png)

![Discover — Key Phrases](screenshots/18b-discover-key-phrases.png)

![Discover — Cultural Insights](screenshots/18c-discover-cultural.png)

![Bilingual Re-read](screenshots/19-story-reread.png)

![Story Order Exercise](screenshots/20-story-check.png)

![Post-Story Score](screenshots/21-story-score.png)

![Story Completion Summary](screenshots/22-story-complete.png)

![Stories Library](screenshots/23-stories-library.png)

![Notebook](screenshots/24-notebook.png)

### 2.5 Monetization & Pricing

| Feature | Description |
|---------|-------------|
| Free Tier | Access to all languages, basic lessons, targeted word lists |
| Pro Monthly | €21.99/month — full access to all Pro features |
| Pro Annual | €69.99/year (€5.84/month) — marked as "Most Popular" |
| Pro Lifetime | €127.49 one-time (50% off from €254.99) |
| Pro Features | Extra word lists, ad-free experience, all native speaker videos, unlimited pronunciation practice, unlimited sentence building, unlimited AI conversations, grammar lessons, verb conjugation drills, extra role-play sessions, cultural & language tips |

![Pricing Comparison](screenshots/38-pricing.png)

![Full Pricing Page](screenshots/38b-pricing-full.png)

### 2.6 Account & Settings

| Feature | Description |
|---------|-------------|
| Profile Settings | Username and email management |
| Password Management | Separate password change interface |
| Learning Settings | Per-language configuration: skill level, streak management, words per session (Learning: 3/5/7/10, Review: 5/10/15/25/50, Speed Review: 10/25/50/100/150, Difficult Words: 5/10/15/20) |
| Test Type Preferences | Toggle controls for: Arrange the words tests, Typing tests, Prioritise typing in review, Audio tests |
| Delete Account | Account deletion with permanent data removal warning |
| Download Personal Data | GDPR-compliant personal data export |
| Stories Settings | Name, language, level, and interest preferences for the Stories product |

![Profile Settings](screenshots/36-profile-settings.png)

![Learning Settings](screenshots/37b-learning-settings-full.png)

![Stories Settings](screenshots/27b-settings-full.png)

---

## 3. User Stories

### Casual Learner
- As a **casual learner**, I want to pick a language and start learning immediately, so that I can begin without any commitment or payment
- As a **casual learner**, I want to read culturally immersive stories in my target language, so that I can learn language in a meaningful context rather than isolated vocabulary
- As a **casual learner**, I want to tap on words I don't know to see translations, so that I can learn at my own pace without frustration
- As a **casual learner**, I want to choose topics that interest me (food, humour, everyday life), so that I stay engaged with content I care about

### Committed Student
- As a **committed student**, I want to track my daily streak, so that I stay motivated to practice consistently
- As a **committed student**, I want to adjust the number of words per learning session, so that I can control my study intensity
- As a **committed student**, I want to review difficult words separately, so that I can focus on areas where I struggle
- As a **committed student**, I want to practice conversations with an AI chatbot, so that I can build speaking confidence in a low-pressure environment
- As a **committed student**, I want to practice verb conjugations and grammar with AI Buddies, so that I can strengthen specific weak areas

### Exam Preparer
- As an **exam preparer**, I want to find community word lists specific to my exam (GCSE, AP, A-Level), so that I study the exact vocabulary I'll be tested on
- As an **exam preparer**, I want to toggle typing tests on or off, so that I can practice the format my exam requires
- As an **exam preparer**, I want to create my own word lists, so that I can organize vocabulary by exam topic or unit

### Travel Learner
- As a **travel learner**, I want curated "Travel Essentials" word lists, so that I learn the most useful phrases for my trip
- As a **travel learner**, I want to hear multiple native speakers say each phrase, so that I can understand different accents and speaking styles
- As a **travel learner**, I want cultural insights alongside vocabulary, so that I understand the cultural context behind what I'm learning

### Content Creator
- As a **community member**, I want to create and share word lists, so that other learners can benefit from my knowledge
- As a **community member**, I want to browse popular and recently created word lists, so that I can find high-quality study materials

### Pro Subscriber
- As a **Pro subscriber**, I want ad-free learning, so that I can focus without interruptions
- As a **Pro subscriber**, I want unlimited AI conversation practice, so that I can practice speaking as much as I want
- As a **Pro subscriber**, I want access to all native speaker videos, so that I get the full immersive experience

---

## 4. Functional Requirements

| ID | Requirement |
|----|-------------|
| FR-1 | The system shall allow users to create accounts using email/password, Facebook, or Apple authentication |
| FR-2 | The system shall support learning 150+ languages from multiple source languages |
| FR-3 | The system shall present a 4-level skill assessment during onboarding and allow changes later in settings |
| FR-4 | The system shall generate personalized word list recommendations based on the user's stated goals and skill level |
| FR-5 | The system shall deliver vocabulary lessons that include native speaker video clips, multiple audio pronunciations, literal translations, and cultural context tips |
| FR-6 | The system shall test vocabulary recall through multiple-choice quizzes using video clips of native speakers |
| FR-7 | The system shall track words across three progression states: Learned, Heard, and Used |
| FR-8 | The system shall maintain a daily learning streak counter that resets if a day is missed |
| FR-9 | The system shall allow users to mark words as "difficult" for targeted review |
| FR-10 | The system shall provide a video library filterable by watch status (All, Ready to watch, Watched, Needs practice) |
| FR-11 | The system shall offer AI-powered conversational practice (MemBot) with 150+ scenario-based conversation topics |
| FR-12 | The system shall provide Talk Prep with a 3-step conversation rehearsal flow: Build, Learn, Perform |
| FR-13 | The system shall provide six AI Buddy tools: Assistant, Sentence Builder, Pronunciation, Grammar, Role-Play, and Conjugation |
| FR-14 | The system shall allow users to browse, search, create, and subscribe to community-created word lists |
| FR-15 | The system shall present stories in a 5-step reading flow: First Read, Discover, Re-read, Check, Score |
| FR-16 | The system shall provide tap-to-translate functionality on individual words within stories |
| FR-17 | The system shall offer audio playback of stories at normal and slow speeds |
| FR-18 | The system shall categorize story vocabulary into Key Phrases, Slang & Vocabulary, and Cultural Insights |
| FR-19 | The system shall allow users to save vocabulary and phrases from stories to a personal Notebook |
| FR-20 | The system shall provide a bilingual re-read mode with a toggle to hide translations |
| FR-21 | The system shall test comprehension through sentence reordering exercises |
| FR-22 | The system shall collect self-assessment ratings for comprehension level, enjoyment, and difficulty after each story |
| FR-23 | The system shall organize stories by category (Food & Markets, Community & Local Life, Traditions & Celebrations) and metadata (type, reading time, origin country) |
| FR-24 | The system shall offer configurable session sizes for Learning (3/5/7/10), Review (5/10/15/25/50), Speed Review (10/25/50/100/150), and Difficult Words (5/10/15/20) |
| FR-25 | The system shall allow users to toggle test types: Arrange words, Typing, Prioritised typing in review, and Audio tests |
| FR-26 | The system shall support three subscription tiers: Monthly (€21.99), Annual (€69.99/yr), and Lifetime (€127.49) |
| FR-27 | The system shall gate Pro features (extra word lists, ad-free, all videos, unlimited AI practice, grammar, conjugation, role-play, cultural tips) behind the paid subscription |
| FR-28 | The system shall allow account deletion with a permanent data removal warning |
| FR-29 | The system shall provide GDPR-compliant personal data download |
| FR-30 | The system shall support per-language learning settings (each language can have its own skill level, session sizes, and test preferences) |

---

## 5. Business Rules

| ID | Rule |
|----|------|
| BR-1 | **Password Policy:** Passwords must be 6 or more characters |
| BR-2 | **Free vs Pro Gating:** Free users have access to all languages, basic lessons, and targeted word lists. Pro features (extra word lists, ad-free, all videos, unlimited AI, grammar, conjugation, role-play, cultural tips) require a paid subscription |
| BR-3 | **Streak Calculation:** Streaks increment by one for each consecutive day of learning activity. Missing a day resets the streak to zero. Users can manually override their streak count in Learning Settings |
| BR-4 | **Skill Level Mapping:** Users self-assess into one of four levels, which determines course starting points and content recommendations. Levels can be changed at any time in settings |
| BR-5 | **Stories Progression:** Stories follow a mandatory sequential flow (Read → Discover → Re-read → Check → Score). Users cannot skip ahead but can skip the Check exercise |
| BR-6 | **Story Comprehension Tracking:** Post-reading self-assessments feed into a comprehension progress metric displayed on the story completion summary |
| BR-7 | **Word List Subscriptions:** Users can subscribe to multiple word lists simultaneously. The "Selected Word Lists" count is shown during onboarding |
| BR-8 | **Commitment Screen Sequencing:** The commitment/pricing screen appears only once during initial onboarding, after word list selection |
| BR-9 | **Per-Language Settings:** All learning settings (skill level, session sizes, test preferences) apply only to the currently selected language |
| BR-10 | **Community Word Lists:** Any user can create word lists. Lists are publicly browsable and sortable by popularity and creation date |
| BR-11 | **Notebook Persistence:** Items saved to the Notebook persist across sessions and are organized into Words, Phrases, Cultural insights, Notes, and Journal tabs |
| BR-12 | **Stories Interest-Based Curation:** Story recommendations are personalized based on the user's selected interest categories (up to 10 topics) |
| BR-13 | **Trial Offer:** New users are offered a free 3-day Pro trial during the commitment selection step |
| BR-14 | **Multi-Language Support:** Users can learn multiple languages on a single account. The language selector in the top bar allows switching between active languages |
| BR-15 | **Account Deletion:** Account deletion is permanent and irreversible. All learning progress is removed |

---

## 6. Domain Concepts

### User
A person who has created an account on Memrise. Users have a username, email, and password. They can learn multiple languages simultaneously, each with independent progress and settings.

### Language
A target language the user is learning (e.g., Spanish, French, Korean). Each language has its own course content, community word lists, videos, and conversation scenarios. Settings like skill level and session size are configured per language.

### Skill Level
A self-assessed proficiency tier that determines content difficulty and starting points. Four levels exist: Learn from scratch, Getting started, Making good progress, Improving my skills. In the Stories product, three levels are used: Beginner, Intermediate, Advanced.

### Word List
A curated collection of vocabulary items. Word lists can be official (created by Memrise, e.g., "Travel Essentials"), community-created (by other users), or personal (created by the individual user). Each word list has a title, description, word count, and creator.

### Lesson
A structured learning session that presents a configurable number of new vocabulary items. Each word in a lesson includes a native speaker video, audio pronunciations, English translation, literal translation, and a cultural "Did you know?" tip. Lessons conclude with quiz testing.

### Story
A culturally immersive reading piece in the target language. Stories are categorized by theme (Food & Markets, Community & Local Life, etc.), tagged with metadata (type, reading time, origin country), and processed through a 5-step reading flow. Stories contain Key Phrases, Slang & Vocabulary, and Cultural Insights.

### Notebook
A personal reference collection where users save vocabulary, phrases, cultural insights, and personal notes discovered during story reading. The Notebook also includes a Journal for reflective writing.

### Streak
A consecutive-day learning counter that incentivizes daily practice. Streaks reset to zero on a missed day but can be manually adjusted in settings.

### Conversation
An AI-powered dialogue scenario using the MemBot chatbot. Conversations are categorized as "Chats" (open-ended discussions) or "Missions" (goal-oriented tasks like ordering food or booking a hotel).

### AI Buddy
A specialized AI practice tool focused on a specific language skill. Six types exist: Assistant (general guide), Sentence Builder, Pronunciation, Grammar, Role-Play, and Conjugation.

### Talk Prep
A guided conversation rehearsal feature with three stages: Build (shape the conversation content), Learn (practice saying the lines), and Perform (recite from memory).

### Pro Subscription
A paid membership tier that unlocks premium features. Available in Monthly, Annual, and Lifetime pricing. Pro features include ad-free experience, all native speaker videos, unlimited AI practice, grammar lessons, and more.

### Community
The collective of Memrise users who create and share word lists. The Community Word Lists section allows browsing by popularity and recency, with search functionality.

---

## 7. User Flows

### 7.1 New User Signup & Onboarding Flow

1. User arrives at the landing page (memrise.com)
   ![Landing Page](screenshots/01-landing-page.png)

2. User clicks "Start Learning"

3. User selects the language they want to learn from a searchable grid of 150+ languages
   ![Language Selection](screenshots/02-signup-start.png)

4. User creates an account with email/password or social login
   ![Signup Form](screenshots/03-onboarding-signup.png)

5. User selects their current skill level (4 options from beginner to advanced)
   ![Skill Level](screenshots/05-course-home.png)

6. User selects their learning goals (multi-select from 6 options)
   ![Learning Goals](screenshots/06-onboarding-next.png)

7. System suggests word lists based on goals; user can add community lists
   ![Word List Curation](screenshots/07-onboarding-daily-goal.png)

8. User selects their commitment level (Free, Trial, or Pro)
   ![Commitment Selection](screenshots/08-learning-home.png)

9. User arrives at the Self-Study Dashboard, ready to start their first lesson
   ![Dashboard](screenshots/29-classic-dashboard.png)

### 7.2 Vocabulary Lesson Flow

1. User clicks "Start lesson" from the dashboard

2. System presents a new word with native speaker video, translation, audio variants, and a cultural tip
   ![Word Presentation](screenshots/39-lesson.png)

3. User can play the video, listen to multiple audio clips, read the "Did you know?" section, or click "I already know this" to skip

4. After learning 3-10 new words (configurable), quiz testing begins

5. System presents video-based multiple choice quizzes
   ![Video Quiz](screenshots/39c-lesson-test.png)

6. User selects an answer or clicks "I don't know"

7. Upon completion, learned words are added to "My Words" and the progress bar advances

### 7.3 Story Reading Flow

1. User navigates to Stories and selects a story from the library
   ![Stories Library](screenshots/23-stories-library.png)

2. Story detail page shows preview text with tap-to-translate, metadata, and a comprehension prediction quiz
   ![Story Detail](screenshots/15-story-detail.png)

3. **Stage 1 — First Read:** User reads the story in the target language without help. Audio playback available at normal and slow speed
   ![First Read](screenshots/16-story-reading.png)

4. User clicks "I've finished reading" and rates their comprehension, enjoyment, and difficulty
   ![Rate & Review](screenshots/17-story-rate-review.png)

5. **Stage 2 — Discover:** System breaks down vocabulary into Key Phrases, Slang & Vocabulary, and Cultural Insights. User can save items to Notebook
   ![Discover](screenshots/18-story-discover.png)
   ![Key Phrases](screenshots/18b-discover-key-phrases.png)
   ![Cultural Insights](screenshots/18c-discover-cultural.png)

6. **Stage 3 — Re-read:** Bilingual view with translations below each sentence. Toggle to hide translations
   ![Bilingual Re-read](screenshots/19-story-reread.png)

7. **Stage 4 — Check:** Sentence reordering exercise to test comprehension
   ![Story Order](screenshots/20-story-check.png)

8. **Stage 5 — Score:** Final self-assessment of comprehension
   ![Score](screenshots/21-story-score.png)

9. Completion summary shows stats and recommends next story or practice activities
   ![Completion](screenshots/22-story-complete.png)

### 7.4 Stories Onboarding Flow (First-Time Stories User)

1. User enters the Stories product and sees the welcome page
   ![Stories Welcome](screenshots/09-learning-dashboard.png)

2. Step 1: User enters their display name
   ![Name Entry](screenshots/10-stories-home.png)

3. Step 2: User selects their language (Spanish, French, or English)
   ![Language Selection](screenshots/11-stories-onboarding-step2.png)

4. Step 3: User selects their level (Beginner, Intermediate, Advanced)
   ![Level Selection](screenshots/12-stories-onboarding-step3.png)

5. Step 4: User selects interest categories from 10 options (Food & markets, Family & traditions, Local customs, etc.)
   ![Interest Selection](screenshots/13-stories-onboarding-step4.png)

6. User arrives at the personalized Stories Dashboard
   ![Stories Dashboard](screenshots/14-stories-dashboard.png)

### 7.5 Upgrading to Pro

1. User clicks "Upgrade to Pro" from the sidebar or encounters a gated feature

2. Pricing page displays Free vs Pro feature comparison and three pricing options
   ![Pricing](screenshots/38-pricing.png)
   ![Full Pricing](screenshots/38b-pricing-full.png)

3. User selects a plan (Monthly €21.99, Annual €69.99/yr, Lifetime €127.49) and subscribes

---

## 8. Edge Cases

| Scenario | Handling |
|----------|----------|
| **Failed signup** | If the email is already registered, the system should display an appropriate error message |
| **Select-product page JS error** | Observed during testing: the /select-product page occasionally fails to render (JS error "Cannot read properties of undefined (reading 'gridRows')"). Users are stuck on a white screen. Navigating directly to /dashboard works as a workaround |
| **AI Buddies 404** | Direct navigation to /ai-buddies returns a 404. The correct URL is /buddies. Internal navigation from the sidebar works correctly |
| **Exam Prep page gone** | The /exam-prep URL returns a 404 with a redirect to Community Word Lists. Exam prep content appears to have been merged into the main product |
| **Empty state — My Words** | When no words have been learned, the My Words page shows an empty state with encouragement to start learning |
| **Empty state — Notebook** | New users see empty Notebook tabs with no content until they save items from stories |
| **Coming Soon features** | "Your Growth" and "Practice" sections in Stories display "Coming Soon" placeholders rather than functional content |
| **Story skip** | Users can skip the "Check" (sentence reordering) exercise, which is recorded as "Skipped" in the completion summary |
| **Streak reset** | If a user misses a day, the streak resets to zero. The manual override in Learning Settings allows restoration |
| **Multiple products confusion** | Users navigate between two distinct products (Self-Study at /dashboard and Stories at /stories) with different navigation structures, which may cause confusion |
| **Free user hitting Pro gates** | When free users attempt to access Pro-only features, the system should redirect to the pricing page |
| **Browser compatibility** | The Stories product is a modern SPA that may have rendering issues in older browsers |

---

## 9. Non-Functional Requirements

| Category | Requirement |
|----------|-------------|
| **Performance** | Vocabulary lessons with video should load within 3 seconds on a standard broadband connection. Audio playback should begin within 1 second of pressing play |
| **Scalability** | The platform serves 370,000+ Pro subscribers (per marketing page) and must handle concurrent learning sessions across all languages |
| **Availability** | The platform should be available 24/7 with minimal downtime, as users learn across all time zones |
| **Security** | User credentials must be securely stored. Social authentication (Facebook, Apple) must follow OAuth 2.0 standards. Session management must prevent unauthorized access |
| **Privacy** | GDPR compliance: users can download personal data and delete their accounts. Cookie consent is required for EU users |
| **Accessibility** | The platform includes "Skip to main content" links, keyboard shortcuts in lessons, and ARIA labels on interactive elements. Lesson interface supports keyboard navigation (number keys for answer selection) |
| **Localization** | The platform interface is available in 25+ languages (Arabic, Chinese, Dutch, English, French, German, Hindi, Indonesian, Italian, Japanese, Korean, Norwegian, Persian, Polish, Portuguese, Russian, Spanish, Swedish, Turkish, Vietnamese, etc.) |
| **Mobile Responsiveness** | The web application references companion mobile apps; the web interface should be responsive for tablet and mobile viewports |
| **Content Delivery** | Native speaker videos and audio files must be served efficiently via CDN to minimize latency across global regions |
| **Data Persistence** | Learning progress, streaks, notebook entries, and word list subscriptions must persist reliably across sessions and devices |
| **Offline Support** | Not observed in web version; likely a mobile-only feature |

---

## 10. Assumptions and Unknowns

### Confirmed Facts (from stakeholder input)

1. **Stories is an experiment:** Memrise Stories is currently a beta experiment running alongside the core Self-Study App. It is not intended to replace the classic product at this time.

2. **Geo-based pricing:** Pricing varies by country/region. The Euro amounts shown (€21.99/mo, €69.99/yr, €127.49 lifetime) are region-specific and will differ for users in other markets.

3. **AI feature strategy is evolving:** The relationship between AI Buddies, Talk Prep, and MemBot Conversations is still being evaluated. All three may coexist, or some may be consolidated based on user data.

4. **Your Growth and Practice are next-quarter launches:** The "Coming Soon" placeholders in the Stories product represent features planned for release within the next quarter.

5. **Community content moderation:** Community Word Lists use a community reporting and flagging system for quality control, rather than editorial pre-review.

6. **Exam Prep is being rebuilt:** The former Exam Prep page was taken down and is being rebuilt as a new feature, not simply merged into Community Word Lists.

7. **Consumer subscriptions are the sole revenue model:** There are no institutional or B2B licensing arrangements. Revenue comes entirely from consumer Pro subscriptions.

8. **Stories are entirely human-authored:** All story content (text, cultural insights, vocabulary annotations) is written by human authors, not generated by AI.

### Assumptions

1. **Pro subscription spans both products:** It is assumed that a single Pro subscription unlocks premium features in both the Self-Study App and Stories, though this was not explicitly verified.

2. **Mobile apps offer additional features:** The web product references mobile apps in multiple places; it is assumed the mobile experience may include additional features like speech recognition, push notifications, and offline mode.

3. **AI features are Pro-gated:** AI Buddies, unlimited Conversations, and Talk Prep are assumed to have usage limits on the free tier, based on the pricing page feature comparison.

4. **Spaced repetition is used:** Though not explicitly confirmed through the UI alone, the "Review" and "Speed Review" session types with configurable intervals strongly suggest a spaced repetition algorithm underlies the vocabulary review system.

### Unknowns

1. **Revenue model details:** Exact conversion rates between free and Pro tiers, trial-to-paid conversion, and the relative proportion of Monthly/Annual/Lifetime subscribers are unknown.

2. **AI model backing:** Which language models power the MemBot conversations, AI Buddies, and story generation is not visible from the front end.

3. **Offline capabilities:** Whether the web app supports any offline learning, and what offline features the mobile apps provide, is unknown.

4. **A/B testing:** Whether different users see different onboarding flows, pricing, or feature gates is unknown.

5. **Analytics and progress algorithms:** How comprehension progress is calculated, how the "My Journey" stage progression works, and what triggers level-up recommendations are opaque from the UI.

6. **Stories language expansion:** Stories currently shows only Spanish, French, and English. The expansion roadmap to additional languages is TBD.

7. **Data portability:** While personal data download exists, the format and completeness of exported data is unknown.

8. **Notification system:** Whether the platform sends email reminders, streak warnings, or learning nudges is not visible from the web interface alone.

9. **Exam Prep redesign scope:** The rebuilt Exam Prep feature's shape, timeline, and target exams are unknown.
