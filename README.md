# Chrome New Tab Static HTML

Replace Google Chrome's default new-tab page with some html of your choosing.

### Steps to install:
1. Clone repository somewhere sensible.
2. Enable "Developer mode" via the Google Chrome
   [extensions](chrome://extensions/) page. This will allow you to load
   unpacked extensions, which is required so that you can edit `links.html`
   without having to repack and reinstall it each time.
3. Click "Load unpacked extension..." and point it to your local repository.
4. Edit `links.html` to your liking.

### Why this?
There are lots of other extensions that will do the same thing, more or less,
but Google Chrome will not allow extensions to modify the url (for good
reason). So the only way to mimic behavior of the default new-tab page (url
bar blank and with focus upon load) is to include the new-tab page within the
extension itself. This, in turn, makes it hard to edit, so it is loaded as an
unpacked extension in developer mode to avoid this problem. A bit hacky, but
gets the job done.


