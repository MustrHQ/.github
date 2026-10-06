# Contributing to MustrHQ

Thanks for helping. Each application has its own, more detailed guide — start there:

- [Rota contributing guide](https://github.com/MustrHQ/rota/blob/main/CONTRIBUTING.md)
- [Stock contributing guide](https://github.com/MustrHQ/stock/blob/main/CONTRIBUTING.md)
- [Recipes contributing guide](https://github.com/MustrHQ/recipes/blob/main/CONTRIBUTING.md)

The same ground rules apply across every MustrHQ project:

- **Plain PHP and MySQL.** No frameworks, no Composer, no Node, no build step — it must run
  when uploaded to ordinary cPanel shared hosting.
- **PHP 7.4 or newer** must keep working.
- **Nothing phones home.** No telemetry, no third-party scripts in the applications.
- **Security first.** Prepared SQL, escaped output, CSRF tokens on every form.
- **Upgrades never touch data.** Schema changes add tables and columns; they never drop or rewrite.

Report bugs with the issue templates, and security problems privately as described in
[SECURITY.md](SECURITY.md). By contributing you agree your work is licensed under the
GNU AGPL-3.0, like the projects themselves. Everyone taking part follows the
[Code of Conduct](CODE_OF_CONDUCT.md).
