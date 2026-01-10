layout: post
title: "🔐 Element Lock – Customize websites your way Live design changes, customize any website your way without code"
date: 2026-01-07 16:10:00 +0530
thumbnail: https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_thumbnail.png
---

Have you ever thought —

> “What if this website had a different color…”  
> “What if this text was bigger…”  
> “What if this box could be hidden…”

But you don’t know CSS,  
or you don’t have a PC / Laptop,  
or the client is sitting in front of you saying –  
“Make it look a bit nicer…”

That’s when Tools Browser’s Element Lock becomes your life saver 😎

---

## 🧠 What is Element Lock?

Element Lock is a Live Design Tool of Tools Browser  
with which you can change any part of any website —

Change colors  
Make text bigger/smaller  
Change background  
Hide divs  
Fix layout  

👉 **Without writing CSS**

It works only on your mobile for your view.  
No change happens on the website server.  
It is completely **Safe & Legal**.

---

## 🎯 Why was it made?

Suppose you are a Web Developer.  
The client said —

> “This design looks a bit boring, I want a more premium look”

But you are outside,  
no PC,  
no Photoshop,  
no VS Code 😵

Then you —

1. Opened Tools Browser  
2. Opened the client’s site  
3. Turned on Element Lock  
4. Changed the design live  
5. Showed the screenshot to the client  

The client said —  
“Wow 😍 That’s what I want”

Later you went home and made the same design in real code.

👉 Time saved  
👉 Less hassle  
👉 Happy client  

---

## 🛠️ How does Element Lock work?

Element Lock works in two ways —

1️⃣ By Position / ID  
2️⃣ By Tag  

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img1.jpg)
---

They are for two different purposes.

---

## 🧩 What is 1️⃣ By Position / ID?

When you click on any element,  
Tools Browser first checks —

Whether that element has an **ID**  

If there is an ID —  
that becomes the perfect target.

If there is no ID —  
then it works by that element’s **DOM position**.

👉 This works very well on normal websites.  
👉 But on dynamic sites like Facebook, YouTube, Amazon the DOM changes.

That’s where problems happen.

---

## 🧩 What is 2️⃣ By Tag?

It works by the element name.

For example —

| What you clicked | Tag |
|------------------|-----|
| Link | `<a>` |
| Image | `<img>` |
| Text | `<p>` |
| Button | `<button>` |
| Box | `<div>` |

If you lock the `<a>` tag,  
all links on that page will get the same design.

👉 This is the safest for dynamic websites.

---

## 🧪 Real example

Suppose you opened W3Schools.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img2.jpg)
---

Now —

1. Menu → Turn on Element Lock
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img3.jpg)
---
2. You will see — “Tools Running” on top  
---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img5.jpg)
---
3. Click on any element  
4. I clicked on **Learn to Code**

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img6.jpg)
---

As soon as you click,  
a **dialog will appear** —  
Now choose how you want to lock that element.  
I selected **position** because W3Schools does not change its DOM dynamically.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img7.jpg)
---

Then click continue and the Element Lock page will show.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img8.jpg)
---

Now from the Element Lock page choose:

1. Color  
2. Background  
3. Size  
4. Hide  
5. Border  
6. Font  

Everything will change live.

I want to change the **background color of the Learn to Code element**,  
so I selected **Change background color**  
and chose green.

Now click the **Apply button**.  
Look at the screenshot below.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img9.jpg)
---

After clicking **Apply** you will see the live design has changed.  
Because I changed the background color,  
the **Learn to Code** element is now green.

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img10.jpg)
---

---

## 💾 Will it go back to normal after reload?

No 😏

Tools Browser saves all Element Lock changes  
locally

So —

Even if you reload the page  
Even if you close the app and open it again  

Your design will remain.

---

## 😱 “I hid an element – now it is not visible!”

This is the most common problem 😄

But there is a solution.

1. While the page is still loaded, open **Element Lock page**  
2. Click on any element  
3. From menu → **All Hidden Elements**

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img11.jpg)
---

3. **Select** the one you want back  
4. I hid only one element so I see only one  
5. You will see all that you hid  
6. Press **Show**

---
![Thumbnail](https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/element-lock/blog5_img12.jpg)
---

The **Page will reload**  
and the element will come back 🎉

## ⚠️ Limitations (Very important)

When using Element Lock, remember one thing —

**To bring any design back to default you must reload the page.**  
Otherwise the DOM will show the old design.

Suppose —

You changed an element’s background color.  
Later you want to use  
the default color that the website owner had set.

So you went to Element Lock  
and removed the tick (✓) from background color —  
meaning you removed your custom color.

But after clicking **Apply**, if you see  
the element still has background color  
and there is no tick on Element Lock page,

That means —

The old design is still in the DOM,  
even though your custom design was removed.  
**If you don’t reload, the DOM will stay old.**  
So the browser still shows the old view.

👉 Solution is simple:  
**Reload the page.**

Whenever you remove any custom design and click apply,  
Tools Browser **auto reloads**.

After reload,  
the website’s original default design will come back.

---

## 📏 I set size to 0 by mistake – nothing is visible!

Don’t worry.

1. Element Lock → Menu  
2. **All Resized Elements**  
3. Tap the broken one  
4. **Reset Size**  
5. Just like All Hidden Elements.

Done 😎

---

## ⚠️ Position vs Tag is very important

| How you locked | Recovery must be the same |
|----------------|---------------------------|
| By Position | All Hidden (Position) |
| By Tag | All Hidden (Tag) |

Otherwise nothing will show.

---

## 🚫 Will it work on all websites?

No.

Some websites —

Block **JavaScript Injection**  
Use **iFrame**  
Use **Shadow DOM**

Element Lock may not work there.  
This is not a limitation of Tools Browser,  
it is website security. Tools Browser does not help break security.  
Stay away from such things.

---

## ❤️ This was not made for bad purposes

Element Lock is made for —

Web Developers  
UI Designers  
Learning  
Practice  

❌ Hack  
❌ Fake design  
❌ Scam  

Not for these.

---

## 📥 Tools Browser download link

👉 **Download Tools Browser from here:**  
🔗 *[Download from Play Store](https://play.google.com/store/apps/details?id=com.soumitra.toolsbrowser)*

---

## 🤝 Join our Community

If you —

Find any bug  
Have trouble understanding  
Want to give new ideas  

Then join us —

📌 Facebook Page  
📌 Facebook Group  
📌 Telegram Group  

---

## 🌟 Final words

Your feedback makes Tools Browser stronger.

If you like it,  
please support us with ⭐⭐⭐⭐⭐ on Play Store ❤️

Stay healthy,  
stay well,  
and customize the web your way with Tools Browser 😎🔥

---

If you want, I can also make  
Thumbnail text,  
SEO title,  
Meta description 🚀
