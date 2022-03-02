# Fake Sub Controller

### Steps to reproduce

1. Add Code To 'Tracking Code Section' Of Funnel On Order Page
2. Give The Title Of 'fake-sub' To The Subscription Bump Or Change Line 58 To Match Bump Title

```javascript
const fSub = () =>
  document.querySelector('[data-title="fake-sub(CHANGE)"] input');
```

3. If Adding An Order Summary Element Either Give It A Title Of 'order-summary' Or Match The Title In Line 60

```javascript
const orderSummary = () =>
  document.querySelector('[data-title="order-summary(CHANGE)"]');
```

4. If Fake Bump Is Selected, It Will Store It In Local Storage Under OrderStorage
