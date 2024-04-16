Example showing no warnings for missing peer dependencies in `npm 10.2.4`

```bash
cd t-marts-package
npm i #no warning
npx check-peer-dependencies #missing peer dependency found - ❌  react 18.2.0 is required by bob-jane-package@1.0.0 (react is not installed)
```
