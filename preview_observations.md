<strong>**COMPLETED**</strong> - This was an interesting exercise whilst there were only a few users of Jason Irwin (& Nozomi's) service.  Now it's nicely-populated, soon to exit the closed beta, with new features being rolled out on a steady basis, and with people *already* writing apps, it's time to stop my puny efforts.

## What is 10Cv4?

[**https://10centuries.org/**](https://10centuries.org/) is a web social and publishing platform with an interesting concept; the user owns the data, the service has the lofty goal of preserving said data for 10 centuries.  It's not my job to sell stuff, the service speaks for itself.

There's a site blog, the earliest post is perhaps the best place to start: [https://blog.10centuries.org/2016/01/26/happy-new-year](https://blog.10centuries.org/2016/01/26/happy-new-year)

---

# 10Cv4 early preview

## Observations sorted by date, most recent first.

Please bear in mind I'm almost exclusively viewing 10Cv4 via my Android phone's Chrome browser.

---

# 2016-02-07

## Profile & UI:

### Avatar & Menu:

* **Broken again:** I cannot change my avatar after one successful change earlier today.  The top-right dropdown menu fails to appear; the Profile image upload fails, displaying a broken image placeholder.  Only deleting browser history allowed the new avatar to show up.

---

# 2016-02-05

## Blurbs:

* **Added:** Blurb delete added inline now.

* Here's an interesting couple of issues:

\1\. I created an expiring post, set for 0.1667 hours, and it was gone not 5 minutes later.    
\1\. Double posting (cleared by a refresh, as before) is back for me. In this case, triple posting.

(This was a Markdown numbered list test, using 1. and 1. Not a biggie if it doesn't work in a Blurb, I'm just curious.  Implementing and maintaining a full Markdown spec. for Blurbs seems overkill.)

---

# 2016-02-04

## Blurbs:

* **Fixed:** *Perverse:* Now: standalone plain text links fail to clickify in a single Blurb, whilst a combination of a Markdown link and a plain text link only clickifies the plain text link!
* **Fixed:** *Still kinda broken:* When I paste a URL into a Blurb - copied directly from the browser address line - it looks fine but the link becomes, e.g.:

`http://http//bazbt3.10centuries.org/2016/01/26/hawaiian`

- and thus fails.

* **Fixed - was observed during files update:** Markdown is visible in previously working Blurbs - `[]()` links and `![]()` image posts.  *My* image post referencing @matigo's HP notebook examination worked but his post and @phoneboy's later image link post both failed.

---

# 2016-02-02

## Login:

* **Fixed:** Login fails repeatedly on mobile.  No error message, the page simply does the respond.  (It's always been a bit slow.)

## Import from service:

* No longer works - blank screen.

---

# 2016-01-30

## Posting:

### Expiring Blurbs:

* **Fixed:** Blurbs don't expire.
* **Fixed (browser refresh):** Blurb expiry input requires YYYY:MM:DD:HH:MM:SS after change to number of hours.

---

# 2016-01-28

# Pages:

## Rendered site:

* **Fixed:** Headings disproportionately large and too large for line spacing.  No ability to change theme and customise CSS.

---

# 2016-01-26

## Timeline:

**Explained - there is a limit in this testing phase.** At 16:20 on January 26th I could scroll back only as far as 'January 25th 2016, 11:48:32 pm'.  Is this limit intentional, new, as a result of an update?  (I've never ***noticed*** a scroll limit before today.)

## Posting:

* **Fixed:** The 'completed' link to Posts is https and fails every time.  Only http pages work (I've been manually deleting the 's' Like a common person.)

---

# 2016-01-24:

## Posting:

### Podcasting:

* Adding an audio file to a blog post generates an embedded player which uses the cover image setup in the RSS feed section for podcasting.  This is a good thing.

## UI:

### Uploading files:

* It's possible to upload files currently, but not possible to view (and link to) them.  Adding a file to a post at least generates a link.  (See Podcasting above.)

## Posts:

### Markdown:

* **Fixed:** Markdown in Posts - at least for `<h#>` tags - seems fixed.
* **Broken:** Markdown in Blurbs - for e.g. `<h#>` is a bit borked, rendering as `<h<span class="hash" data-hash-id=">">#>\``.  Various inexpertly-applied combinations of escaping all fail.

## Blurbs:

* Observation: Hashtags show up clicky now, with tooltip 'Hashtag search not coded yet.'  (10C is going the right way still!) 

## Basic info:

* **Fixed/Implemented - coded:** Looks good, simpler than the first iteration.  *However* I seem to have no sites, message: "Odd. There Are No Sites to List" - yet my site bazbt3(etc) works fine.

---

# 2016-01-23:

## Posting:

### Creating, editing:

* Attempting to view a newly-created or -edited post by pressing the new status link at the top of the page I'm getting "This web page is not available - ERR\_CONNECTION\_REFUSED".  10Cv2 works fine.  The posts are viewable from my main v4 site.

## Account/UI:

### Passwords:

* **Explained:** I can't change my password yet, the Save button does nothing.
* **Explanation:** My password is 'too weak' - the red bar is just that, a bar to progressing.
* The password strength indicator is overwritten by the paragraph following it.  (See this gists's image 'Screenshot_2016-01-23-09-27-18.png')

## Posting:

### Blurbs:

* **Fixed:** Frequent apparent double-posting, resolved by page refresh.

## Meta:

* In lieu of tidying this document I've added 'Fixed' & 'Implemented' where things I've mentioned previously now work.  Lazy Baz.

---

# 2016-01-22:

## Profile & UI:

### Avatar & Menu:

* **Fixed:** I now have an avatar and the top-right dropdown menu works in mobile Chrome on my Android phone. Yay!

### Blurbs:

* **Implemented:** the Mentions view works now.

## Posts:

* **Explained:** I can confirm that escaping Markdown characters (e.g. \\#) works but leaves the backlash visible.
* **The explanation:** One hash is treated as a standalone character, e.g. for a hashtag, not as an `<h1>` HTML tag. 2 or more hashes produce `<h2>` etc.

---

# 2016-01-21:

## Profile:

### Avatar:

* **Fixed/Followup:** Though my avatar isn't uploadable yet would it be possible to add an inout box requesting a URL from which to grab it?  (Not suggesting hotlinking here but a file transfer.)  I know that [http://bazbt3.github.io/images/bazbt3_adn_avatar.png](http://bazbt3.github.io/images/bazbt3_adn_avatar.png) works because it's used in a recent Blurb.  Please don't do it just for me, and especially don't set the avatar; I'd rather be able to test for you. Awkward, me.

## Accounts:

### Username fluidity:

* How difficult a task would it be to change a username once the 10Cv4 account is established, and/or link 2 (or more) usernames to one account such that…  Though not right now, for obvious reasons, I'd like both @bazbt3 and @baz to front identical content, share identical logins.  Ever been done before?  Probably not, it's a bit daft.

---

# 2016-01-20

## Posts:

* **Followup:** Creating a new post a few minutes ago - [Sock monster](http://bazbt3.10centuries.org/2016/01/20/sock-monster) - gave me first a 9-hour-old timestamp and on refresh an 18-hour-old one.
* Editing still works, which saved my blushes with a typo.

## Blurbs:

* **Implemented:** I tried 2 mentions, per your request.  Did it work yet?
* I like Markdown a lot, but I've retained a social networking post mentality of adding a single linefeed and expecting no concatenation.  I daresay it'll come to me soon - unless you decide to implement a hybrid MD flavour where links and images and all the other stuff just works and single linefeeds also just work?

---

# 2016-01-19:

## Profile:

### Avatar:

* **Fixed (storage space/file upload permissions):** Not working yet.  Is there a minimum avatar size (or file specification) or is a user change not coded yet?

## Posts:

* Post dates are off by a long way - are you using Japan time?  If so something's not quite right, my first post yesterday was 39 hours off, the last post 4.  I'll let you know at a reasonable hour for me.

## Blurbs:

### Working:

* Blurbs work, of course.  (I thought I would be the first to post but no, two utter reprobates beat me!)

### Some issues:

* A Blurb Edit button is available but it directs to a Post edit/creation screen.

### Not working:

* The Blurb View button directs one to the 10Centuries.org splash screen but the URL looks as if it should be correct, e.g.:

    http://10centuries.org/posts/61

## Philosophy:

### Start screen:

* Do you have any plans for the landing page - the first thing a user sees a when logging in?  Dependent on a user's focus would a social screen (Blurbs) be perhaps better?  Dunno, a *lot* to consider.

### @ usernames

(I was looking through your timeline.)

* **Implemented:** I'd prefer @ usernames, it's a well-established convention now.  A familiar hook shouldn't  put new users on the back foot.

---

# 2016-01-18:

## Posts:

### Working:

* Post
* View
* Edit
* Delete

### Some issues:

1. Editing isn't Android keyboard text replacement app -capable.  I'm guessing iOS just works, being at the OS level.  I'm also guessing it's just me that'll find this an issue.
2. I struggled with Markdown level 3 heading; it dragged the list below onto the same line which then concatenated the list items.  
3. Attempting a `<pre>` tag to force a block of fixed-width text failed.
4. Within the failing `<pre>` a couple of symbols also failed, the first of which stopped further rendering of text.  (Works here at my GitHub Pages [test blog.](http://baz.bt3.com/))

To be fair items 2-4 above also failed on 10Cv2.  Would a Markdown/Markdown flavour primer be in order, say a help section sticky page?

## Menus:

### Some issues:

* **Fixed:** Despite what I said yesterday, the top right avatar often fails to display - and with it the menu options - subsequent to a run through some of the sidebar menus.  I haven't pinned down *which/when* yet.

## Philosophy:

### Terminology:

* **Explained:** Why a `Post`, why a `Blurb`; what's the difference between the two?

### Importing from:

* Why Twitter and WordPress?  Easy APIs for the stage you're at?
* Why not 10Cv2?  Your work's still in progress? Merging issues for ongoing writers?

---

## Browser:

* When saved as a shortcut and pinned on a white background, the 10C.org site logo fades almost to invisibility.  Maybe a little darker drop shadow/outline is needed?
* Good to see the site logo has a transparent background.

(See this gist's image 'Screenshot_2016-01-17-20-20-58.png' - it seems impossible to link to an image within a gist 'repo' document.)

---

## Login:

* Login and Sign out work well - repeatable.

---

## Menus:

(UI examination only!)

**Fixed:** Pressing a sidebar menu button often directs to a blank body, and drops the avatar below the top bar, with a collapsed menu dropdown, as below

### Working:

* *Home* > Home, New post, New blurb, Profile,
* *Content* > Everything,
* *Settings* > Configure RSS,
* *Transparency* > Balance sheet, Statistics,
* *Drop-down* > Profile Account Sign out.

### Some issues:

* *Content* > Import from file - dropdown source box partially-obscured by lower half of screen.

### Not working:

* *Home* > My statistics,
* *Content* > Import from service,
* *Settings* > Basic info, Themes, Custom CSS,
* *Transparency* > Performance,
* **Fixed but needing explanation (password strength):** *Drop-down* > Password.

---

## Profile:

* **Fixed:** Image upload fails with 'No file chosen', a broken image placeholder.
* No Markdown or html in profile bio (preview pane.)  Would the 10Cv2 rich text formatting bar be useful?
* Not obvious whether user must add '@' before social network username.  (I omitted, assuming 10Cv2 norms.)

---

# Home

## New Post:

### Working:

* Page appears to load fine, editing & preview look good.

### Not working:

* **Fixed:** Publish To list box isn't populated.

***Nothing else tested.***

---

## New Blurb:

### Working:

* Page appears to load fine,
* Editing & preview look good,
* Advanced/Simple section opens & closes.

### Not working:

* (Nothing else tested.)

---

[End]
  
