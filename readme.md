# Fake Sub Controller

---

### Steps to reproduce

1. Add Code To Tracking Code Of Funnel On Order Page
2. Give The Title Of 'fake-sub' To The Subscription Bump Or Change Line 58 To Match Bump Title

```
 const fSub = () => document.querySelector('[data-title="fake-sub(CHANGE)"] input');
```
