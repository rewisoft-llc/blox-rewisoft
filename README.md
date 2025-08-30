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
