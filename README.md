# Setup
1. Add import to `config/_default/module.yaml`:
```
imports:
  ...
  - path: github.com/rewisoft-llc/blox-rewisoft
```

2. Run Maintenance step for your site.

# Maintenance
After pushing changes to main branch, you need to update each downstream application to pull in latest changes:
1. Open terminal from the app's root directory
2. Run `hugo mod get github.com/rewisoft-llc/blox-rewisoft`

# Configuration
### Landing CTA Simple
![Landing CTA Simple](/img/landing-cta-simple.png)
```
- block: landing-cta-simple
  id: <HTML element id>
  content:
    title: "Let's Get To Work"
    subtitle: "We're looking forward to hearing from you"
    button:
       label: "Contact Us"
       url: "/contact"
```
---
### Landing Grid Cards
![Landing Grid Cards](/img/landing-grid-cards.png)
```
- block: landing-grid-cards
  id: best-fit
  content:
    title: Right Choice for Us?
    subtitle: With its bespoke nature, Unity is good fit for anyone but certain companies will find more value in our services.
    items:
      - title: New to the Industry?
        text: 'Most vendors push their own niche products, which can overwhelm newcomers. We learn your business, design a solution that removes complexity, and keep you focused on growth. When it’s time to scale or upgrade, we’ll help you choose the right vendors, manage the transition, and ensure everything runs seamlessly from start to finish.'
        feature_icon: check
        features: []
        image: img/good-fit-section/overwhelming.png
      - title: Longstanding company ready to modernize?
        text: AdTech’s growing complexity can force businesses to change processes that already work. Unity bridges your current workflows with modern AdTech, letting you adapt without a full overhaul. When you’re ready to integrate more deeply, we ensure a smooth, strategic transition—helping you modernize at your own pace without sacrificing what makes your business successful.
        feature_icon: bolt
        features: []
        image: img/good-fit-section/modernize.png
```
---
### Landing Stats
![Landing Stats](/img/landing-stats.png)
```
- block: landing-stats
  content:
    title: "Proven Success"
    text: "Our client success team brings years of experience building, launching, and maintaining AdOps solutions for large DOOH networks. "
    items:
      - statistic: "$200m"
        description: "Revenue"
      - statistic: "30k+"
        description: "Venues"
      - statistic: "120k+"
        description: "Screens"
```
---
### Landing Timeline
![Landing Timeline](/img/landing-timeline.png)
```
- block: landing-timeline
  content:
    title: What to Expect
    subtitle: Our process is designed to minimize risk, speed up delivery, and ensure long-term maintainability
    items:
      - title: MVP Development
        description: The dirty work begins. We implement your product using modern web technologies — with clean, maintainable code, scalable architecture, and full version control.
      - title: Testing and Deployment
        description: Before launch, we validate that everything performs as expected under real conditions — across browsers, devices, and traffic scenarios.
      - title: Post-Launch Support
        description: After a successful MVP launch, we continue to support your platform’s growth with proactive maintenance, feature updates, and performance monitoring.
    footer_message: MVPs are typically ready for go-live within 9 months
    link:
      label: Learn More
      url: "/docs/overview/what-to-expect/"
```
