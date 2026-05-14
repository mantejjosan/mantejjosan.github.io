# Mantej Singh Josan
2nd year CS · GNDEC Ludhiana · [mantejjosan@gmail.com](mailto:mantejjosan@gmail.com) · [GitHub](https://github.com/mantejjosan) · [LinkedIn](https://www.linkedin.com/in/mantej-singh-josan-048661275)

Hello there! I am a Computer Science student. I enjoy approaching technology from first principles, breaking complex systems into understandable components, and learning by building, experimenting, and documenting along the way. 




## Projects

### [Apex Engagement Tracker](https://apexgne.vercel.app)
`Nextjs` `QR` `Session Auth` `Postgres` `Supabase`

Every stall at my college fair was told to record visitor names and activity choices on paper. I thought that was embarrassing for an engineering college, so I built an alternative in two days without telling anyone.

Each activity at each stall got its own printed QR code. College students just scanned any QR once — a middleware route set a session cookie good for 8 hours, so even if they closed the browser and came back, one scan from the camera was enough. No app, no login screen, no typing. School students attending without phones got a physical QR tag from a counter I set up. The tag mapped to an empty row in the database. When a stall volunteer scanned it, they could register the person once — after that, scanning the same tag at any other stall just asked which activity they played, no re-registration.

The volunteer interface was designed around how people actually show up — in groups. Scanned visitors queued up as small circles below the camera feed. The volunteer could tap each one, mark the activity, tick a box if everyone played the same game, and move on. The system also tracked a live leaderboard — top students by activities, and which club attracted the most visitors overall.

It ran through the morning and went down after 1pm. I had pre-generated 500 QR tags with student names from an attendee list, but had no table or place to distribute them. When I switched to blank tags printed on the spot, the calls came in faster than I could manage and the whole thing collapsed. The code worked. The operation didn't. That distinction stuck with me.



### [SGPA Calculator](https://sgpa-calculator-e69b.onrender.com)
`Flask` `Python` `Render`

Built on the day results came out, deployed the same evening. By the next morning half my batch was using it. I had never deployed anything before — I used Render, which was the wrong call (slow cold starts, free tier limitations), but it taught me more about the gap between running something locally and putting it in front of real users than any tutorial would have.



### [Bulk Certificate Generator](https://github.com/mantejjosan/automailcertificates)
`Python` `PIL` `CSV` `Pandas` `Reportlab`

A friend needed to generate certificates for 100 participants but didn't have Canva Pro for bulk export. I didn't know about mail merge or any proper tooling at the time, so I built something from scratch. You paste your certificate template image into MS Paint, hover over where the name should go, and note the pixel coordinates. The tool takes those coordinates, a CSV of participant details, and a column mapping — then stamps every name onto every certificate and spits them all out. She ran it once and was done in seconds. Probably overkill, but it worked.



### [Jupyter Practical Formatter](https://github.com/mantejjosan/pracfile)
`Python` `Typst` `Zebra Plugin` `Bash Scripting`

For our AI subject, practicals had to be submitted as formatted documents. Writing the content in Jupyter and then manually fixing the formatting every time was tedious. This tool takes your Jupyter notebook, wraps it in a Typst template, uses the Zebra plugin for syntax-highlighted code blocks, and outputs a clean PDF — proper headings, consistent layout, no manual work. You just write the practical. Everything else is handled.



### [Snake Game](https://mantejjosan.github.io/snake-game/game-intro)
`JavaScript` `HTML Canvas`

Classic snake built from scratch in vanilla JS. Where it all started.



## Hackathons

| Place | Event | Details |
|-------|-------|---------|
| 2nd | CGC Parivartan Hackathon | Inter-college · Rs. 4,000 cash prize (duo) |
| 2nd | GNA University Hackathon | Inter-college · Phagwara |
| Participant | Smart India Hackathon (SIH) | National level |
| Various | Other inter-college hackathons | Multiple wins and losses |



## Skills

**Programming & Scripting** — Python, C++, SQL, JavaScript, Bash

**Development & Systems** — React, Flask, REST APIs, Linux/WSL environments, Git & GitHub, web application workflows

**Documentation & Technical Communication** — Markdown, Jekyll, Typst, tutorial writing, technical documentation, structured knowledge presentation

**Platforms & Tools** — Frappe/ERPNext, GitHub Pages, Mermaid, LaTeX-based workflows

**Core Computer Science Concepts** — Data Structures & Algorithms, DBMS, normalization, concurrency concepts, graph theory fundamentals, session-based authentication systems, modular arithmetic foundations



## Education

**B.Tech Computer Science & Engineering**  
Guru Nanak Dev Engineering College, Ludhiana · 2024 – 2028



## Blogs

[My Tech Blogs on Obscure Topics](https://mantejjosan.github.io/tutorials/)



## Contact

- Email: [mantejjosan@gmail.com](mailto:mantejjosan@gmail.com)
- GitHub: [mantejjosan](https://github.com/mantejjosan)
- LinkedIn: [mantej-singh-josan](https://www.linkedin.com/in/mantej-singh-josan-048661275)
