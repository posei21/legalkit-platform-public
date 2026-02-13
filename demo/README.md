# LegalKit Demo

Two high-resolution demo loops using `www.unbound-labs.com`.

## Demo 1: Scan to Deploy

<video src="demo_pipeline.mp4" autoplay loop muted playsinline controls width="100%"></video>

Shows the main product pipeline:
- scan website services
- review compliance findings
- generate policies
- move to deploy checklist

## Demo 2: Live Site Verification

<video src="demo_live.mp4" autoplay loop muted playsinline controls width="100%"></video>

Shows the deployed result on the real site:
- consent banner appears and stores consent
- live policy routes are available:
  - `/privacy`
  - `/terms`
  - `/cookies`

If autoplay is blocked by your browser, press play once and loop continues.

## Screenshots

![Scan Input](screenshots/01_scan_input.png)
The workflow starts by scanning `https://www.unbound-labs.com` and detecting services that require consent.

![Deploy Status](screenshots/02_deploy_status.png)
After generation, the deploy checklist confirms hosted policies, live banner, and active monitoring.

![Live Banner](screenshots/03_live_banner.png)
The live site shows the consent banner once, then stores consent after acceptance.

![Live Privacy Policy](screenshots/04_live_privacy.png)
The deployed privacy policy is live at `https://www.unbound-labs.com/privacy`.

![Live Terms](screenshots/05_live_terms.png)
The deployed terms page is live at `https://www.unbound-labs.com/terms`.

![Live Cookies](screenshots/06_live_cookies.png)
The deployed cookie policy is live at `https://www.unbound-labs.com/cookies`.
