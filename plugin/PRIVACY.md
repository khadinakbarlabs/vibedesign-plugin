# VibeDesign privacy and data handling

VibeDesign is a skills-only instruction package published by Khadin Akbar. It includes local design references and templates. It does not operate a server, collect telemetry, create background tasks, store authentication credentials, or receive the user's design project through a VibeDesign service.

The AI host processes prompts, files, and tool results according to that host's settings and policies. Local artifacts remain in the directory the user chooses. The host or operating system may retain its own history and files; VibeDesign does not control those systems.

Live public research is optional. When authorized, the external Apify CLI sends selected public queries/URLs and run settings to Apify and the selected Actor/source provider. Apify handles account authentication, runs, datasets, storage, and billing under its own policies. Users should review https://apify.com/privacy-policy and the relevant source platform's policies. Authentication belongs in Apify's normal CLI flow, not in chat or plugin files.

Import mode analyzes supplied files in the host's working environment without sending those files to Apify. The instructions prohibit sending private product files, customer records, cookies, and credentials to research Actors. The AI host still processes supplied material according to its own data policy.

Research reports should minimize personal data and use source links, short paraphrases, and relevant aggregates. Public reviews can contain personal information; users should avoid retaining unnecessary reviewer profiles or distributing raw personal data.

Users control deletion of local artifacts. Apify run and dataset retention/deletion is managed through the user's Apify account and its settings. Host conversation/file deletion follows the host's controls. This package has no separate account database or deletion endpoint.

Public support issues are handled by GitHub and remain visible under GitHub's policies. Do not include secrets or private data in them. See SUPPORT.md for the reporting route.
