---
layout: post
title: "Ads Blocker, Firewall-Style Protection: Complete Guide to Control Redirect, Popup & Banner Ads with Tools Browser"
date: 2026-01-15 16:10:00 +0530
pinned: true
thumbnail: https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_thumb.png
---

Today on the internet, we all face the same problems —  
Popup ads, auto-open tabs, adult banners, fake download buttons, casino links.

Especially when  
you are reading a good website  
and suddenly a family member or child is beside you —  
adult or misleading ads become very embarrassing 😓

Tools Browser was built specifically to solve this problem.

---

## 🧠 How does Tools Browser work?

Tools Browser does not remove ads from inside any website.  
It does not harm any publisher.

It works using **User-side URL Protection**.

That means —

> Which servers (URLs) will load on your phone  
> and which will not  
> is completely under your control.

This works exactly like a **firewall or antivirus**.

---

## 🔐 Smart Protection — Master Switch

First, open Tools Browser:

1. Go to App Settings →
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img1.jpg)
---

3. Go to Site Settings →
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img2.jpg)

---
  
5. Enable Smart Protection (tick mark)
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img3.jpg)

---

When this is turned ON ✅

Redirect ads block  
Popup ads block  
Fake download block  
Adult site redirect block  
Tracking & malicious script block  

Everything gets blocked at once.

---

**⚠️ Very Important Rule**

Smart Protection = Master Switch

If Smart Protection is **OFF**, then:

Custom Block List  
Ads Block  
Redirect Block  

**Everything stays OFF.**

Simply put:

> **If the engine is off, the steering will not work 🚗**

So always keep:  
Smart Protection → ON

---

## 🧱 Custom Block List – Block Ad Companies Your Way

Suppose you notice these URLs loading:

ads.network.com  
pop.redirect.xyz  
adult-cdn.site  

Now you think —  
these URLs are not useful at all.  
Instead, they are the source of popup ads, adult banners, fake download buttons, redirects 😓  
If these could be permanently blocked,  
browsing would become clean, peaceful, and safe — right? 🔐

To solve this, Tools Browser provides a powerful feature —  
> Custom Block List

To use it:

**1. App Settings » Custom Block List**  
> Enable Custom Block List  
> Then tap on Custom Block List text
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img4.jpg)
---

From the Custom Block List page:

1. Go to **Menu**
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img5.jpg)

---
2. Tap **Add new**
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img6.jpg)
---

Enter only the domain or full URL path:

**Example:**  
ads.network.com  
or  
https://ads.network.com/djjdbm

3. Tap the **Add** button.
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img7.jpg)
----

Now reload the site.  
Nothing will load from that URL anymore —  
> no ads  
> no popup  
> no redirect  
> no adult content

---

**Many times it happens —**  
we do not even know  
which **domain** or **company** these annoying ads are coming from 😕  
and which one to block  
to stop the ads.

For these situations,  
**Tools Browser has a smart system**  
that shows exactly which Ads Company  
is sending content to your phone.

## 🔍 If You Don’t Know Which Ads Company

**Method 1 — Inspect Tool**

Load the website you want to block ads from, then →

i. **Tools →**
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img8.jpg)
---
ii. **Inspect →**
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img9.jpg)
---

Now search in the inspect page:

> ads  
> banner  
> iframe  
> redirect  
> .js  

You may find something like:  
https://ads.somecompany.com/script.js  
or similar.  
Confirm which URL is actually serving ads.

---

**Method 2 — ChatGPT (Easiest)**

Copy the full page source  
Paste it into ChatGPT  
And write:

> **“Which URLs are loading ads or popups on this website?”**

ChatGPT will tell you which **domain is serving ads**.

Then add that domain to the Custom Block List.

---

## 🎯 Hide Banner Ads (Visible Ads on Page)

Sometimes —  
> No redirect  
> No popup  
> but large **banner ads** exist.

These ads do not open new tabs,  
but they ruin the page layout  
and make reading uncomfortable.

The good news is —  
these banner ads can also be hidden using Tools Browser.

This is done by modifying the **HTML parent container**  
where the ads are placed.

Let’s see how 🚀

---

**Step 1:**

Load the website where you want to hide banner ads.  
I loaded a random site.  
See the banner ads in the image below.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img10.jpg)
---

i) Tap **Tools**
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img11.jpg)
---
ii) From Tools page, tap **Edit Element**  
(or inspect manually to find the parent ID).  
I’ll show the easy method.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img12.jpg)
---

Now tap on the banner ad you want to hide.

Important note —  
If the banner ad is inside an iframe or shadow DOM,  
direct tapping may not work.

In that case,  
tap near the banner or its background area  
so Tools Browser can detect the correct parent container 🎯

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img13.jpg)
---

**Step 2:**

From the returned HTML,  
find the banner ad’s **Parent Container**.

Ads usually come from iframe or dynamic scripts —  
those cannot be modified.

But the container where the ad is placed  
(div or iframe) can be hidden.

Common examples:
```html
<div id="ads-container">  
<div class="banner-ad">
<iframe id="banner-ad">
```

Copy the ID or Class.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img14.jpg)
---

**Step 3:**

Now the main work.

Open App Menu → Local JavaScript page.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img15.jpg)
---

Enable **✔ Entire Site**  
Then from menu tap **→ Create new**

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img16.jpg)
---

Paste the following JS  
(use ID or Class based on what you found):

```javascript
// Hide by ID
var adById = document.getElementById("ads-container");
if (adById) {
  adById.style.display = "none";
}
```

```javascript
// Hide by Class
var adsByClass = document.getElementsByClassName("banner-ad");
for (var i = 0; i < adsByClass.length; i++) {
  adsByClass[i].style.display = "none";
}
```

Replace `"ads-container"` or `"banner-ad"`  
with the value you copied from Inspector.

Save it.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/ads-blocker/blog6_img17.jpg)
----

**Step 4:**

Reload the website 🔄  
Banner ads gone 😌

If it doesn’t work,  
you selected the wrong parent —  
> with the correct parent, it works **100%**.

---

## ⚠️ Warning

If you mistakenly hide a wrong ID or Class,  
not only the banner  
but other elements using the same ID/Class  
may also be hidden.

Sometimes the entire page may appear broken or blank 😨

No need to panic.

Go back to the page  
where you added the JS script  
and remove that script.

The page will return to normal ✅

---

## 🌍 Real Life Example

Suppose you are using:

Education sites  
Job portals  

and suddenly **adult** or **casino banners** appear.

Using Tools Browser:

Banner hide  
Redirect block  
Popup block  

while the main website works perfectly.

---

## ⚖️ Why Is This 100% Legal?

Tools Browser:

Does not hack any website  
Does not delete ads  
Does not harm publishers  

It only says:

> “This URL will not load on my phone.”

Exactly like a firewall.

---

## 📥 Use Tools Browser

With Tools Browser you get:

Safe browsing  
Clean websites  
No embarrassment  
Full control  

All control is in your hands.  
This level of control exists only in Tools Browser.

---

## Tools Browser – Latest Version Download

👉 **Download Tools Browser here:**  
🔗 [Download from Play Store](https://play.google.com/store/apps/details?id=com.soumitra.toolsbrowser)

---

## 💡 Final Advice

Separating good content from bad ads is very important on the internet.

Tools Browser gives you that control.
