❄️ Snowflake — Complete Course Notes

Every session from S01 to S55, distilled into 22 readable modules — plain explanations, a picture to remember each concept by, working syntax, and the point an interviewer actually wants to hear.

🌐 Live Site: https://aitechs-lvr.github.io/snowflake-course-notes/

📌 About

These are personal course notes covering Snowflake end to end — architecture, security, data loading, and the surrounding tooling (dbt, Azure Data Factory, AWS, Cortex AI) — rewritten so they're actually useful to revisit, not just a transcript of the sessions.

Every module follows the same shape: a plain-English explanation first, then the working SQL/config you'd actually type, then the one line that answers what an interviewer is really asking. It's a single static page, so it works offline and loads instantly.

📊 At a Glance

| Stat | Value |
|---|---|
| 🎓 Sessions covered | S01 – S55 |
| 🗂️ Modules | 22 |
| 🧰 Tooling covered | Snowflake, dbt, Azure Data Factory, AWS, Cortex AI |
| 📶 Works offline | Yes |
| 🖥️ Format | Single-page static site |

🗂️ Modules

**Foundation**

| # | Module | Covers |
|---|---|---|
| 1 | Account & Editions | Editions compared, ways to connect |
| 2 | Roles & Users | System-defined roles |
| 3 | Architecture | Cloud services, query processing, storage layers, micro-partitions |
| 4 | Warehouse, Cache, Monitor | Scale up vs scale out, the three caches, resource monitors |
| 5 | Database, Schema, Tables | Table types |

**Core Features**

| # | Module | Covers |
|---|---|---|
| 6 | Time Travel & Cloning | Time Travel, zero-copy cloning |
| 7 | JSON & XML | Semi-structured data types, loading JSON, XML |
| 8 | Stages & Loading | Stage types, file formats, `COPY INTO`, unloading |
| 9 | Snowpipe & External Tables | Continuous loading, querying files you never load |
| 10 | Masking & Row Access | Data masking policies, row access policies |

**Pipelines**

| # | Module | Covers |
|---|---|---|
| 11 | Streams & Tasks | Change tracking, task scheduling/chaining |
| 12 | Views & Dynamic Tables | Views vs dynamic tables |
| 13 | Sharing & Clustering | Data sharing, clustering keys |
| 14 | UDF & Stored Procedures | User-defined functions, stored procedures |

**Tools**

| # | Module | Covers |
|---|---|---|
| 15 | dbt Setup & Models | Project setup, models |
| 16 | dbt Snapshots & Tests | Snapshots, tests |
| 17 | dbt Macros, Hooks, Seeds | Macros, hooks, seeds, exposures |
| 18 | AWS & Azure Data Factory | Cross-cloud integration, ADF pipelines |

**Apply**

| # | Module | Covers |
|---|---|---|
| 19 | Medallion Architecture | Bronze/silver/gold layering |
| 20 | Sample Projects | End-to-end worked examples |
| 21 | Cortex AI | Snowflake's built-in AI functions |
| 22 | Quick Revision | Condensed recap of every module |
| 23 | Self Check | Self-test questions |

✨ Features

- 🧭 Sticky sidebar navigation — jump straight to any module
- - 🖼️ A visual/analogy for every hard concept, not just a definition
  - - 💻 Working, copy-pasteable SQL for every topic
    - - 🎯 Interview-angle callouts — the line that actually gets asked
      - - 📶 Works fully offline — no build step, no dependencies
        - - 📱 Responsive — readable on mobile and desktop
         
          - 🚀 Run Locally
         
          - ```
            git clone https://github.com/AiTechs-LVR/snowflake-course-notes.git
            cd snowflake-course-notes
            # Open index.html directly, or serve it:
            python3 -m http.server 8000
            # Then visit http://localhost:8000/
            ```

            No build step required — it's a single static HTML file.

            📁 Project Structure

            ```
            index.html → the full course notes (all 22 modules)
            README.md  → this file
            ```

            🤝 Contributing

            Spotted an error, an outdated syntax example, or a module that could be clearer? Contributions are welcome.

            Open an issue or a pull request with:

            - 📍 Which module the change belongs to
            - - ✏️ What's wrong or missing
              - - ✅ A corrected/working example, where relevant
               
                - 📄 License
               
                - These notes are shared for learning purposes. Please open an issue first if you'd like to reuse or adapt the content.
               
                - Curated with ❄️ by AiTechs_LVR
