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