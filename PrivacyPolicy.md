AdSkip — Privacy Policy

Last updated: 30 October 2026

AdSkip is a browser extension for Chrome and Firefox that skips sponsored segments in videos and blocks advertising and tracking content. This policy explains exactly what the extension does with your data. It covers the extension itself; it does not cover any website you visit.

THE SHORT VERSION
- AdSkip has no accounts, no sign-in, no analytics and no telemetry.
- Your settings, statistics and blocking rules are stored only in your browser.
- The only data that leaves your device goes to the community SponsorBlock API, and only to fetch or submit segment times for the video you are watching.
- Nothing is sold, rented or shared with anyone.

WHAT ADSKIP STORES ON YOUR DEVICE
Stored locally in your browser's extension storage, and never transmitted to us:
- Your preferences: which segment categories to skip or mute, your per-site whitelist, fast-forward speed, and notification settings.
- Your local statistics: how many segments were skipped, how many ads were handled, and the estimated time saved.
- Your own blocking rules: elements you hid with the element picker, areas you masked, and any custom filters you wrote.
- Your word list: the words and phrases you asked AdSkip to hide, the display mode and colour you chose, and the list of sites where words are switched off.
- Your per-site lists: sites where AdSkip is paused and sites where word filtering is off.
- Diagnostics: a rolling log of at most 400 recent technical events, described below.
- A randomly generated private ID, used only to attribute segment submissions that you choose to make.

You can export or delete all of this at any time from the extension's settings.

WHAT LEAVES YOUR DEVICE, AND WHERE
AdSkip contacts one third-party service: the community-run SponsorBlock API at sponsor.ajay.app. There are two cases.

1. Fetching segment times. When you open a video, AdSkip asks the API for the community-submitted sponsor segments for that video. By default the request contains only the first four characters of a SHA-256 hash of the video id, which is not enough to identify the specific video. You can switch this privacy mode off in settings, in which case the video id itself is sent.

2. Submitting segment times. Only when you explicitly press "Submit" in the on-page editor. A submission contains the video id, the segment start and end times, the category, a generic user-agent string identifying the extension, and the random private ID described above. That ID is not linked to your name, your email address, or any account — AdSkip has no accounts.

No other network requests are made. In particular, the filter lists AdSkip blocks with are included in the package; they are never downloaded at runtime.

DIAGNOSTICS ARE LOCAL ONLY
AdSkip keeps a small technical log on your device so problems can be diagnosed: extension lifecycle, whether an ad was detected or skipped, how long an operation took, and errors. Each entry can include the site hostname (for example "example.com"), never the full URL, the path, the query string or any page content. Cookies, tokens, authorisation headers, passwords and e-mail addresses are stripped before an entry is written, and site hostnames can be switched off entirely in Settings, Diagnostics.

This log is never uploaded. There is no telemetry endpoint, no account and no server that receives it. You can read it, export it as a JSON file, or delete it at any time from Settings, Diagnostics. Nothing is sent anywhere unless you export the file and choose to share it yourself.

WHAT ADSKIP DOES NOT COLLECT
AdSkip does not collect, store or transmit:
- your name, email address, or any account details;
- your browsing history, or the list of sites you visit;
- the content of the pages you view;
- your location;
- any advertising identifier, analytics event, or telemetry.

AdSkip contains no analytics, no advertising and no tracking of any kind.

FIREFOX DATA-COLLECTION DECLARATION
On Firefox, AdSkip declares one category of required data collection, "browsing activity", because the video id is transmitted to the SponsorBlock API to fetch and submit segment times. That declaration is shown to you when you install the add-on. The other categories — personal information, location, health, financial and payment information, authentication information, personal communications, and website content — are not collected.

CHROME WEB STORE DATA DISCLOSURE
AdSkip does not collect personal data, does not sell data, and does not use data for purposes unrelated to its single purpose. The video id transmitted to the SponsorBlock API, as described above, is the only data that leaves the device.

THIRD PARTIES
The only third party involved is the SponsorBlock API (sponsor.ajay.app), a community project. Segments you choose to submit become publicly visible to other users of that service. Please refer to the SponsorBlock project for its own data practices. AdSkip does not sell, rent or share your data with anyone else.

REMOTE CODE
AdSkip does not download or execute remote code. All of its code is included in the extension package.

CHILDREN
AdSkip is not directed at children and does not knowingly collect data from anyone.

CHANGES TO THIS POLICY
If this policy changes, the updated version will be published at the same URL.

CONTACT
br19shc39@gmail.com
