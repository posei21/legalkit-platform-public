# LegalKit Demo

Full walkthrough of the scan-to-compliance pipeline using `https://www.unbound-labs.com`.
This run includes compliance workflow plus hosted **Privacy**, **Terms**, and **Cookies** policy verification.

![LegalKit Demo](demo.gif)

[Download MP4](demo.mp4)

## Flow (in order)

1. Scan `www.unbound-labs.com` and detect compliance gaps.
2. Review issues and queue one-click remediation.
3. Generate policy content from scan context.
4. Complete deploy/compliance steps in the wizard.
5. Verify hosted policy routes: Privacy, **Terms**, Cookies.
6. Verify live consent behavior on production.

## Key screenshots

![Scan Input](screenshots/01_scan_input.png)
Scan begins with target site input and service detection.

![Deploy Status](screenshots/02_deploy_status.png)
Deploy checklist confirms hosted docs, banner setup, and monitoring.

![Live Banner](screenshots/03_live_banner.png)
Live site after deploy with consent controls visible.

![Live Privacy Policy](screenshots/04_live_privacy.png)
Hosted privacy policy generated from scan + form inputs.

![Live Terms of Service](screenshots/05_live_terms.png)
Hosted Terms page rendered and verified in the flow.

![Live Cookies](screenshots/06_live_cookies.png)
Hosted cookie policy route live on production.
