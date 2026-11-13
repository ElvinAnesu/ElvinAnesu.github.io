# elvinanesu.github.io

Public developer studio site for **Elvin Kakomo** (with [Startum Africa](https://startumafrica.com)).

This is the Google Play developer website and the host of `app-ads.txt` for AdMob verification. It is a static site (HTML and CSS only, no build step).

## URLs

- Site: https://elvinanesu.github.io/
- Games: https://elvinanesu.github.io/games.html
- Cops &amp; Robbers: https://elvinanesu.github.io/cops-and-robbers/
- About: https://elvinanesu.github.io/about.html
- Contact: https://elvinanesu.github.io/contact.html
- Support / FAQ: https://elvinanesu.github.io/support.html
- Privacy: https://elvinanesu.github.io/cops-and-robbers/privacy.html
- Terms: https://elvinanesu.github.io/cops-and-robbers/terms.html
- app-ads.txt: https://elvinanesu.github.io/app-ads.txt

Support email: appsupport@startumafrica.com

## app-ads.txt

Keep `/app-ads.txt` at the site root, byte-identical, so AdMob can verify the publisher account. Do not move, rename, or reformat this file. In Play Console, set the developer website to `https://elvinanesu.github.io`.

## Enabling the Play Store button

On `cops-and-robbers/index.html`, the store link already points at:

`https://play.google.com/store/apps/details?id=com.elvinkakomo.copsandrobbers`

When the listing is live, remove the `is-disabled` class, remove `aria-disabled` and `tabindex="-1"`, and change the label to “Get it on Google Play”.
