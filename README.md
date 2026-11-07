# Hi, I'm Aidan Dai 👋

Computing Science student at the University of Alberta (expected April 2028), focused on robotics and embedded software.

- **Summer 2026:** AI Software Intern on a quadruped inspection robot in Guangzhou, China
- **Fall 2026:** building a campsite-lottery Android app with a team of seven (CMPUT 301)
- **Looking for:** robotics, embedded and software internships starting May 2027

## Featured work

### Quadruped robot inspection platform · Internship, Jun–Aug 2026
AI Software Intern at Zhangdong TurboMobile Technology, Guangzhou. The code belongs to the company, so there is no public repo.

`Python` `C++` `Jetson Orin NX` `MQTT (EMQX)` `Grounding DINO` `YOLO` `Vue 3 + TypeScript`

- Wrote a ~250-line Python post-processing module for 3 false-positive types (cross-class NMS, per-class score and area limits, multi-frame voting); the team enabled it and false positives dropped noticeably.
- Independently reworked the C++ announcement program (message queue, de-duplication, 20 s timeout, 3 priority levels) so the robot's detection alerts no longer cut off its spoken answers.
- Selected and integrated an M260C voice module on the Jetson: fixed dropouts from insufficient USB hub power, kept its device name stable across reboots, and deployed speech recognition with the robot SDK.
- Led the build of the initial Vue 3 + TypeScript front end (15 modules, 27 pages), which the team kept extending after the internship.

### [Utopia-campsite](https://github.com/CMPUT301F26utopia/Utopia-campsite) · CMPUT 301 team project, Fall 2026
An Android app for reserving campsites through a lottery: owners list campsites, campers join a waitlist, and winners are drawn once registration closes.

`Kotlin` `Jetpack Compose` `Firebase Firestore` `JUnit`

- Wrote the lottery draw, with unit tests: after a campsite's registration period ends, it picks winners at random from the waitlist and saves them to Firestore. The app has no server, so the draw runs when the app starts.
- Wrote the input checks behind the owner's register-campsite form, with unit tests: required fields, number fields, and the registration and booking periods.
- Created the first versions of the campsite summary row and details screen; wrote the project README, UML class diagram and CRC cards.

### [Autism Edmonton Learning Platform](https://github.com/fyz007/LimitlessMind) · natHacks / natIgnite 2026, 4th place
An accessible learning-platform prototype, built in a 40-hour team hackathon, that presents Autism Edmonton's lecture videos and resources to families affected by autism and ADHD. [Live site](https://limitless-mind-seven.vercel.app)

`Next.js` `React` `TypeScript` `Supabase`

- Implemented video and content pages, site-wide font sizing, read-aloud and a dyslexia-friendly mode.
- Fixed the Supabase login flow (SSR middleware and an auth callback route).

## Skills

- **Languages:** C/C++, Python, TypeScript/JavaScript, Kotlin, SQL
- **Robotics and embedded:** ROS 1/ROS 2, Jetson Orin NX, RK3588, MQTT (EMQX)
- **Computer vision:** YOLO, Grounding DINO, NMS and multi-frame filtering
- **Web and mobile:** Vue 3, React, Next.js, Jetpack Compose, Firebase, Supabase
- **Tools:** Git, Linux, GDB, Valgrind
- **Spoken:** English, Mandarin, Cantonese

## Contact

[aydai@ualberta.ca](mailto:aydai@ualberta.ca) · [LinkedIn](https://www.linkedin.com/in/aidan-dai-32811638a)
