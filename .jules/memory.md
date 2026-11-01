## Archived: 2026-10-31

* Binner is a free open-source parts inventory tracking system designed for makers, hobbyists, or professionals to keep track of their parts inventory.
* It is built on .Net Core / C# with a React js front end and runs on Windows, Unix, and embedded devices like Raspberry PI.
* Features include:
  * Standard inventory management input
  * Import orders from Digikey, Mouser, Arrow
  * Customizable nested category placement
  * Track parts by Project
  * Automated datasheet retrieval / Datasheet search
  * Automated part lookup on Digikey/Mouser/Arrow/Octopart/Nexar/TME
  * Export data to CSV / Excel
  * Proprietary file-based database (or providers like SQL Server, Postgresql, MySql, Sqlite)
  * No web server installation required, uses standalone Kestrel service API
  * Simple web-based UI
  * Barcoding support and Label printing (e.g., Dymo LabelWriter 450 series)
  * KiCad HTTP Library support
  * Custom fields support
* The free version supports up to 3 users. Paid license unlocks more features/users.
* Default login credentials: Username: `admin`, Password: `admin`.
* Can be run via Docker, Windows installer, Ubuntu tarball, or Raspberry Pi OS tarball.
* Supports integrations via APIs for Digikey, Mouser, Octopart/Nexar, Arrow, and TME. These must be configured in `appsettings.json` with appropriate API keys/Client IDs.
* Storage providers are configured in `appsettings.json` under `StorageProviderConfiguration`.
