SWAYAM SHAKYA - PORTFOLIO
=========================

Live site:  https://requiemdoomed.github.io/Portfolio-SwayamShakya/
GitHub:     https://github.com/requiemdoomed


WHAT THIS IS
------------
A one-page portfolio for Swayam Shakya, built to be linked from LinkedIn.
It opens on a 1970s lobby with two doors:

  1. READ THE NOVELS
     A theatre stage with the author's novels as acts, shown with their
     covers in gold frames. Each cover can be turned over to see the back.
     Two novels open in a book reader with two-page spreads, page turns,
     chapter jumps, zoom (Z key) and full screen (F key).
     Pages are rendered at up to 4x the screen resolution.
     "The Lotus Blade and The Empty Hand" is shown as in progress.

  2. SEE THE PROJECTS
     An old computer with an amber screen lists the projects as a DOS-style
     directory, grouped into Thesis, Quantum, AI, Systems and Apps.
     Type HELP at the prompt for commands (dir, open, sites, works,
     github, novels, about, color, cls, exit).
     Below the monitor: the TutorBTL and Manaslu CS Club websites, and the
     GYRO-76 essay.

The intro lists the author's roles and education.


FILES IN THIS REPOSITORY
------------------------
  index.html          The page (everything is in this one file)
  preview.png         1200 x 627 image shown when the link is shared
  covers/             Front and back covers of the novels
  novels/             The two novel PDFs used by the book reader
  sites/              TutorBTL and Manaslu CS Club pages and screenshots
  vendor/             PDF.js 3.11.174 (Mozilla, Apache 2.0), used by the reader
  writing/            Original page of the GYRO-76 essay

Keep the folders together with index.html at the top level. If only
index.html is uploaded, the text shows but images, PDFs and the reader
do not.


HOW TO UPDATE THE SITE
----------------------
1. Upload or replace files in this repository (Add file > Upload files,
   or use GitHub Desktop).
2. Commit the changes.
3. Wait a minute or two, then reload the page (Ctrl+Shift+R or Cmd+Shift+R).


GITHUB PAGES SETTINGS
---------------------
Settings > Pages > Source: Deploy from a branch
Branch: main    Folder: / (root)


LINK PREVIEW
------------
The page's meta tags point to:
  og:url    https://requiemdoomed.github.io/Portfolio-SwayamShakya/
  og:image  https://requiemdoomed.github.io/Portfolio-SwayamShakya/preview.png
If the address changes, update both in index.html.
To refresh a LinkedIn preview, paste the address into
linkedin.com/post-inspector.


LINKEDIN LINK
-------------
In index.html, near the bottom, set:
  const PROFILE = { linkedin: "https://www.linkedin.com/in/your-handle/" };
When set, an "Open my LinkedIn profile" button appears in the About section.


DIRECT LINKS
------------
Add one of these to the end of the address:
  #novels                        The theatre
  #read-the-hanging-lord         The Hanging Lord in the reader
  #read-the-mirage-in-the-mist   The Mirage in the Mist in the reader
  #the-lotus-blade               The Lotus Blade and The Empty Hand
  #projects                      The computer
  #mining-dashboard, #qec-latency, #qnas, #voxbridge, #testyourbrain,
  #geoore, #matecheck            Individual projects
  #energy, #baremetal-rtos, #phyvision, #finai, #swarmforge, #inlearn
                                 Individual projects
  #websites                      TutorBTL and Manaslu CS Club
  #gyro-76                       The GYRO-76 essay
  #about                         About and timeline


PROJECT FILES
-------------
Each project has a FILES line marked "Coming soon". To add project files,
create a files/ folder and replace that line in index.html with links to them.


NOTES
-----
- The book reader needs the page to be served from a web address. Opening
  index.html directly from your computer shows everything except the reader,
  because browsers block the PDFs from loading locally.
- The novel PDFs' copyright pages include an email address and city, and the
  TutorBTL page includes a phone number and email. These are visible to anyone
  who opens the site. Edit those files before uploading if they should not be
  public.
- Some project features, languages and tools are proposed descriptions.
  Check them against the actual work and edit index.html where needed.
