# Simplecast
We use Simplecast to host and syndicate all of the shows on the network through a single feed.  

## Requirements before publishing on Simplecast
- filling out the [trello card](./trello)
  - excluding the `embed code` and the `direct download` link

## Items you can retrieve from Simplecast
- episode embed links
- episode .mp3 download links
- download episode recasts
- statistics on episodes

## `PUBLISHING` an episode to The Bitcoin Podcast Network publication
- Create a `DRAFT`
- Schedule or Publish that draft

## Creating a `DRAFT` episode to The Bitcoin Podcast Network publication
- go to https://simplecast.com
- click `Sign In` in navigation bar and sign in with your credentials
- click `Add Episode` in navitation bar
- add `title` from [trello card](./trello) to the `TITLE` section
  - format: `<show> #<show number> - <guest(s)> - <company>
  - shows:
    - The Bitcoin Podcast
    - Hashing It Out
    - HIO Panels
    - Dose of Ether
    - Annoucements
    - Just the Headers
    - Blocked By Design
- let `EPISODE URL` self populate
- upload finished .mp3 file from [trello card](./trello)
- leave `EPISODE TYPE` as `Full` and change `EPISODE NUMBER` to show number in `title`
- `EPISODE SUMMARY` is the description without links from [trello card](./trello)
- `EPISODE NOTES` is the description + links **in markdown format**
  - you should add the donate page and patreon links to this
  - watch the preview pane to make sure the formatting looks good as you enter it in
- uncheck `CONTAINS EXPLICIT LANGUAGE` if you didn't use any this episode
- fill in `EPISODE CONTRIBUTORS` with anyone who spoke in the episode, as well their companies
  - you can add anyone that was mentioned as well, the little info box has a description of what is good to add
- fill in `SEARCH KEYWORDS` with anything you talked about, this helps the episode searchability
- `EPISODE ART` will default to the network logo, but you should add the default thumbnail art for the show
  - TODO: add location of default thumbnail photos
- leave `EPISODE PRIVACY` unchecked
- check `ALTERNATE EPISODE URL` and enter the page link for the website:
  - format: `https://thebitcoinpodcast.com/<show>-<number>`
  - shows:
    - `the-bitcoin-podcast`
    - `hashing-it-out`
    - `hio-panels`
    - `dose-of-ether`
    - `announcements`
    - `just-the-headers`
    - `blocked-by-design`
- change the `RECAST ART` to the show banner found in the [trello card](./trello)
- hit `SAVE DRAFT` at the top right of the site in the navigation bar

## Things to do with a `DRAFT`ed episode
Once an episode has been drafted, you can do the following things

- Add items to the [trello card](./trello)
  - click on `EMBED LINK` and add the appropriate code to the [trello card](./trello).
    - we use the `Standard` option for episode embeds.
    - this is used for episode pages on the [wordpress](./wordpress.md) site.
  - click on `COPY DIRECT MP3 DOWNLOAD LINK` and add it to the [trello card](./trello).
    - thisis used for both streaming and downloading on the slide pages on the [wordpress](./wordperss.md) site.
  - schedule the episode to be published at a later date
    - times are in Eastern time (EST)
  - publish an episode immediately by clicking the `PUBLISH NOW`
    - you can edit details after publication and it will re-syndicate to all places
  - edit the details before/after publishing/scheduling
