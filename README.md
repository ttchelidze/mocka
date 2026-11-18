# MOCKA – Practice Exams

Free, offline practice exams in an exam-center style screen.
Free for personal, non-commercial use. Not affiliated with or endorsed by PMI, Pearson VUE or any course provider.

## Use it

Open the MOCKA link in **Chrome** or **Edge** on a computer and click **Install app** in the toolbar
(or the install icon in the address bar). MOCKA then opens from the Start menu, taskbar or desktop
with its own icon, in its own window, and works offline. Open **User guide** in the app to get started,
or click **Try demo exams** to see how it works.

Your exams and results stay on your own computer. Nothing is uploaded. Use **Export backup** to keep a copy.

## Publish it on GitHub Pages (free)

1. Create a free account at github.com. Your username becomes part of the link
   (`https://<username>.github.io/mocka/`), so pick one you're happy to share.
2. Click **+** (top right) → **New repository**. Name it `mocka`, keep it **Public**, click **Create repository**.
3. On the new page click **uploading an existing file**. Drag in everything from this folder:
   `index.html`, `manifest.webmanifest`, `sw.js`, `favicon.ico`, `README.md` and the `icons` folder.
   Click **Commit changes**.
4. Go to **Settings** → **Pages**. Under *Build and deployment* choose **Deploy from a branch**,
   branch **main**, folder **/ (root)**, and click **Save**.
5. Wait one or two minutes and refresh the page. It shows *Your site is live at …*. That's your MOCKA link.

## Update it later

Upload the new `index.html` the same way (same file name, it replaces the old one) and commit.
People get the new version the next time they open MOCKA while online.
If you ever change the icons, also edit `sw.js` on GitHub and change the `VERSION` line (for example to today's date).

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Name, colours and icons for installing |
| `sw.js` | Offline support |
| `icons/`, `favicon.ico` | MOCKA icons |

Includes SheetJS Community Edition (Apache License 2.0); the license text is in the app under *About & licenses*.
