# Nulavio

**The Linux browser that is protected from the start.**

Nulavio is built from Mozilla's signature-verified Firefox source, with a small set of patches and its own built-in Shell. It runs as a normal browser, with these defaults:

- **Trackers and ads blocked from the first launch:** Strict tracking protection and uBlock Origin. Canvas and WebGL readings differ per site, and extra fonts and the graphics card are hidden from pages.
- **Profiles kept apart and encrypted on disk:** each profile is its own instance. A protected profile opens with a password, a recovery code or your desktop login.
- **The right profile for each site:** links from other apps and addresses you type open in the profile your rules say.
- **No telemetry and no Nulavio account:** there is no Nulavio server to send anything to.
- **AI agents only on your terms:** an agent you connect works in its own profile, with the permissions you give it and an emergency stop.

**Status:** pre-alpha. The first public alpha is for Fedora, through a signed dnf repository. Join the waitlist at **[nulavio.net](https://nulavio.net)**.

**Security reports:** security@nulavio.net. Packages are signed with the OpenPGP key `298A 9093 BAAB B26F 79BB  29F4 BF47 E5FA 9EDB 8DB1` ([public key](https://nulavio.net/keys/nulavio-packages.asc)).

Code under [MPL-2.0](https://www.mozilla.org/MPL/2.0/). "Nulavio" is not affiliated with Mozilla; Firefox is a trademark of the Mozilla Foundation.
