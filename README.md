# Hangman

A browser Hangman word game presented in two visual variants.

**3D game:** https://joenasriani.github.io/hangman/

## Variants

- `index.html`: **The Enchanted Hangman**, the 3D browser version. It uses A-Frame 1.5.0, the A-Frame Environment component, and Three.js capabilities exposed through A-Frame to render a 3D scene.
- `hangman-2d-index.html`: **The Hangman Game**, a self-contained HTML/CSS/JavaScript word-guessing game with an on-screen keyboard.
- `backup-index.html`: Historical backup retained in the repository.

The 2D and 3D files are alternate presentations of the same Hangman project, not independent game titles.

## Playing

Open `index.html` to use the 3D version, or open `hangman-2d-index.html` for the simpler 2D version. A local HTTP server may be helpful when testing browser restrictions.

The 3D page downloads A-Frame and its environment component from third-party CDNs, so internet access is required to load those libraries unless they are supplied locally. The 2D version has no external script dependency in the inspected file.

## Scope and limitations

- These are browser games, not production multiplayer services.
- Words and gameplay run client-side. No authentication or server-side game account is documented.
- Mobile responsiveness and browser compatibility were not device-tested in this documentation review.
- The project's use of A-Frame and other third-party libraries does not transfer ownership of those libraries or their licenses.

Credit: Joe Nasr

Portfolio: https://joe-nasr-signals.vercel.app/
