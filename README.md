# M-BOIS website

Landing page and privacy policy for [M-BOIS](https://github.com/khrlanamm/M-BOIS), the Android companion app for an educational card game about East Javanese culture. The app placed in the Top 50 of the student category at BudayaGO! 2025.

Live at [m-bois.web.app](https://m-bois.web.app). The app is on [Google Play](https://play.google.com/store/apps/details?id=com.kuartet.mbois).

## Pages

- `public/index.html`: app introduction, features, and download links
- `public/privacy-policy.html`: privacy policy for the Google Play listing

Plain HTML and CSS, hosted on Firebase Hosting.

## Deploy

```sh
npm install -g firebase-tools
firebase login
firebase deploy --only hosting
```

## License

All rights reserved. The source code is public for reference only. See [LICENSE](LICENSE).
