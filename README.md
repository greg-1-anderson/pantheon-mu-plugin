# Pantheon Must-Use Plugin

[![Unsupported](https://img.shields.io/badge/Pantheon-Unsupported-yellow?logo=pantheon&color=FFDC28)](https://pantheon.io/docs/oss-support-levels#unsupported)

Workflow
--------
Integrates WordPress with Pantheon Flow. Encourages updating plugins and themes in the Development environment and using Pantheon's git-based upstream core updates.

Edge Cache
-----------
Facilitates communication between Pantheon's Edge Cache layer and WordPress. It allows you to set the default cache age, clear individual pages on demand, and it will automatically clear relevant urls when the site is updated. Authored by [Matthew Boynes](http://www.alleyinteractive.com/).

## Installation
Install via Composer: `composer require pantheon-systems/wp-main`.
