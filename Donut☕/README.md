# 🍩 Spinning ASCII Donut – Java Edition

Welcome to the tastiest terminal experience you've ever seen — a **rotating 3D ASCII torus** rendered right in your console using nothing but math, characters, and the magic of Java!

Inspired by the legendary [Donut.c](https://www.a1k0n.net/2011/07/20/donut-math.html), this project gives your terminal a wild spin — literally.

---

## 🎬 What It Looks Like

When you run it, you'll see something like this (animated):

     .,-~:;=!*#$@
 -=~:;=!*#$@.


Yes, that's a spinning donut... in ASCII. 🍩  
Shaded with different characters based on how the light hits it. 😎

---

## 🧠 How It Works

- Think of a **donut (torus)** in 3D space.
- Rotate it using two angles `A` and `B` (like spinning a plate in the air).
- Project its 3D surface onto your 2D terminal using math.
- Calculate light and depth with trigonometry and a **z-buffer**.
- Use characters like `.`, `-`, `=`, `@` to simulate brightness.

It’s basically OpenGL with a potato — and it works.

---

## ⚙️ How to Run It

1. **Compile the code:**
   ```bash
   javac Donut.java

💡 Fun Fact
This animation went viral as donut.c — only ~200 lines of C code.
Now it's reborn in Java so the JVM can enjoy donuts too.

✍️ Author
Crafted with ❤️ by Me!!
Fueled by coffee ☕ and geometry 📐

