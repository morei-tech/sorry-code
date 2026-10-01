# Sorry Card ❤️

A mobile-first apology website recreated from the supplied screen recording.

## Files

- `index.html` — all sections/content
- `style.css` — design, animations and responsive layout
- `script.js` — navigation, forgiveness meter, hearts and music playlist
- `songs/` — put your MP3 files here
- `assets/` — reference images extracted from the supplied recording

## Add your songs

1. Put your MP3 files in `songs/`.
2. Open `script.js`.
3. Change:

```js
const SONGS = [
  { title: "Your song 1", file: "songs/song1.mp3" },
  { title: "Your song 2", file: "songs/song2.mp3" },
  { title: "Your song 3", file: "songs/song3.mp3" }
];
```

to your actual filenames.

Example:

```js
const SONGS = [
  { title: "Our Song", file: "songs/oursong.mp3" },
  { title: "Another Song", file: "songs/another.mp3" }
];
```

The first tap on "Listen to my heart" starts the playlist. When a song ends,
the next song starts automatically.

## Change the name/message

Open `index.html` and search for:

- `Vaishnavi`
- `I'm really sorry`
- `Get Well Soon`
- `I love you. Always.`

Replace them with your own text.

## Important

The final "Make your own sorry card" Moonlinky button is NOT included.

The final screen is customized to say:

**Get Well Soon ❤️**

## Test locally

The simplest option is VS Code + Live Server.

Or use Python:

```bash
python -m http.server 5500
```

Then open:

http://localhost:5500

## Deploy

This is a static website, so it can be deployed to Vercel, Netlify,
GitHub Pages, or Cloudflare Pages.

For Vercel:

1. Put the project in a GitHub repository.
2. Import the repository into Vercel.
3. Deploy.
4. Vercel gives you a public HTTPS URL.
5. Generate a QR code pointing to that URL.

## Mobile recommendation

Open the deployed URL on a phone and test the entire flow before giving
the QR code to anyone. Mobile browsers intentionally restrict autoplay,
which is why the music starts after the first user tap.


## Visual assets

Two small visual assets are cropped from the screen recording you supplied:
`assets/crying-bear.png` and `assets/couple-bears.png`. They are used to make
the recreation closer to the recording. You can replace them with your own
images at any time.
