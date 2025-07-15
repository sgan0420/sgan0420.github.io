# Portfolio Redirect

This repository has been updated to redirect visitors to the new portfolio location.

**New Portfolio URL:** https://shijiegan.vercel.app/

## About

This GitHub Pages site now serves as a redirect to Shijie Gan's portfolio hosted on Vercel. The redirect happens automatically when visitors access sgan0420.github.io.

## Technical Details

- **Redirect Method**: HTML meta refresh + JavaScript fallback
- **Redirect Target**: https://shijiegan.vercel.app/
- **Redirect Delay**: Immediate (0 seconds)

The redirect is implemented using multiple methods to ensure compatibility across all browsers and scenarios:
1. HTML `<meta http-equiv="refresh">` tag for instant redirect
2. JavaScript `setTimeout` as a fallback
3. Manual link for users with JavaScript disabled

Visit the new portfolio at: **[shijiegan.vercel.app](https://shijiegan.vercel.app/)**