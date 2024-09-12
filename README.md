# React Tailwindcss Datepicker

Fork of https://github.com/onesine/react-tailwindcss-datepicker with
https://github.com/onesine/react-tailwindcss-datepicker/pull/275 and
https://github.com/onesine/react-tailwindcss-datepicker/pull/278 applied. We should go back to the original repo if/when
those are merged.

To make additional changes to this repo, run `npm install; npm run build` after applying the changes. We commit `dist`
to git so we can install the package directly from github without additional build steps. Then in the `tyba` repo, do
`yarn remove react-tailwindcss-datepicker; yarn add Tyba-Energy/react-tailwindcss-datepicker --save` so that the commit
hash in `yarn.lock` gets updated.
