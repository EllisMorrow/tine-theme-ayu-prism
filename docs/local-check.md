# Local check summary

- Theme: Ayu · Prism 0.1.1
- Manifest SHA-256: `be453bc6dfdba0e4318c8e43a074aba5f7c252ca9e25cb15e4514cba2fdb9203`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 6.1:1, title 9.58:1, link 6.09:1, tag 5.16:1, code 5.43:1, mark 5.1:1, chosen 5.08:1.
  - Dark: body 14.08:1, title 14.08:1, link 9.29:1, tag 11.19:1, code 12.61:1, mark 6.76:1, chosen 10.56:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
