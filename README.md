<div align="center">

# ZimaBoard 2: The Honest Review
### From easily scratched metal to a missing terminal.

![Hardware](https://img.shields.io/badge/Hardware-ZimaBoard_2-blue?style=flat-square&logo=server)
![Review](https://img.shields.io/badge/Category-HomeLab-orange?style=flat-square&logo=linux)
![Author](https://img.shields.io/badge/Author-Hugo_Valters-black?style=flat-square)

<br>

[![Watch the Full Review on YouTube](https://img.youtube.com/vi/LgbqukWUEjg/maxresdefault.jpg)](https://youtu.be/LgbqukWUEjg)
*Click the image above to watch the full video review including the sound test!*

</div>

---

As a HomeLab enthusiast, I am always chasing the next best piece of hardware to power my home server test lab setup. My shelf is already home to the original **ZimaBoard** and the **ZimaBlade** (yes, the one where I have strape SSDs on with Velcro — don't judge, it works!).

But a few weeks ago, I got my hands on the new **ZimaBoard 2** (or simply Zima 2). Is it a worthy successor? Does it offer more than just a futuristic aesthetic?

I fired it up for a “first boot” review to find out. Here are my honest impressions — the good, the bad, and the slightly disappointing.

<div align="center">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/14m2sexcfkwszk52jvzd.png" width="48%">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ej1enrad6by0zaylx9xd.png" width="48%">
</div>

---

## 🏗️ The First “Ouch”: Build Quality

Taking the device out of the box, it undeniably looks premium. The industrial metal design feels solid and substantial in the hand. However, I noticed a significant issue almost immediately.

> **It scratches. Easily.**

My unit was simply sitting on a shelf and was moved around a few times, yet the casing already shows visible scuffs and scratches. If you plan to display this on a desk as a showpiece, you need to handle it with extreme care.

On the bright side, Zima included a screwdriver kit in the box, which came in handy for the next step.

<div align="center">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nzs897qufh8agtsshhhh.png" width="48%">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/dsv5nzn02weq40638w6i.png" width="48%">
</div>

---

## ❄️ Cooling: The Sound of Silence

Unlike its passive-cooled Raspberry Pi, the Zima 2 packs enough power to require active cooling. I’ll admit, I was worried. The golden rule of a HomeLab in a living space is silence. Would this fan sound like a jet engine taking off?

After a quick installation (kudos for the included tools) and booting the system, I was pleasantly surprised. The fan is **whisper quiet**. For a home server that might sit near your TV or on your desk, this is a massive win.

<div align="center">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ltm3tqxsrad5sx7eet6s.png" width="48%">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lv9nqiwdug9r44qs99vp.png" width="48%">
</div>

---

## 💻 ZimaOS: Dude, Where’s My Terminal?

I plugged in the HDMI and waited for the boot sequence. The screen greeted me with the standard CLI prompt. Since I didn’t have a mouse and keyboard attached, I hopped onto my laptop to access the Web UI.

The system immediately recognized the **2.5GbE ports** (a standard we should all demand in 2024) and the interface felt very familiar. It looks and feels just like **CasaOS** — clean, simple, and very beginner-friendly.

**But then, I went looking for the WEB Terminal.**

In previous iterations, the **Web Terminal** was one of the best features. It allowed you to quickly pop “under the hood” to fix permissions or run specific commands without needing an SSH client.

> ⚠️ **In ZimaOS v1.5.3? It’s gone.**

I dug through every setting, even the Developer Mode, but the native Web Terminal button is missing. Sure, SSH access still works fine, but removing that quick-access feature feels like a step backward for a “tinkerer’s” device.

<div align="center">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r9h305r36cbcel8p0i98.png" width="48%">
  <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rg7dd2j9dpwlpn5i96qe.png" width="48%">
</div>

---

## 🚀 Performance & Apps

The App Store is stocked with the usual Docker suspects: *Home Assistant, Jellyfin, Cloudflare, Pi-hole, KASM*, etc. Everything is just one click away.

With the upgraded CPU and **16GB of RAM** (on my specific model), the Zima 2 feels significantly snappier than the ZimaBlade. It’s not just for file storage anymore; this thing has the overhead to do some serious lifting.

![App Store](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/affw289v8fsodb3q7km9.png)

---

## ⚖️ The Verdict: Is It Worth It?

The ZimaBoard 2 is a powerful beast in a small (albeit easily scratched) package.

| **The Pros ✅** | **The Cons ❌** |
| :--- | :--- |
| **Performance:** Massive jump in power (3x CPU, 16GB RAM). | **Durability:** The case scratches if you look at it wrong. |
| **Silence:** The active cooling is surprisingly quiet. | **Software:** ZimaOS is missing the Web Terminal. |
| **Connectivity:** Dual 2.5GbE ports are perfect for firewall builds. | **IO:** I really wish it had one more USB port. |
| **Ease of Use:** Simple setup process. | |

### Will I keep running ZimaOS?
**Probably Yes.**

My plan is to wipe it and install **Proxmox**. With this much CPU power and RAM, the Zima 2 is destined to be a virtualization host for multiple VMs, not just a simple Docker container runner. However, I hope to get another device with CasaOS/ZimaOS for my own use and to cluster Proxmox, Rancher, and KASM for home experimental cluster creation.

---

<div align="center">

### 📺 Watch the full setup & scratch test

What do you think? Is the missing terminal a deal-breaker for you, or would you install Proxmox on day one anyway?

[![Youtube Video](https://img.youtube.com/vi/LgbqukWUEjg/0.jpg)](https://youtu.be/LgbqukWUEjg)

<br>

_All rights reserved by Hugo Valters_

[![X (formerly Twitter)](https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/hugovalters)
[![BlueSky](https://img.shields.io/badge/BlueSky-Follow-0085ff?style=for-the-badge&logo=bluesky&logoColor=white)](https://bsky.app/profile/hugovalters.bsky.social)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@hugovalters)
[![Website](https://img.shields.io/badge/Website-Visit-4CAF50?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.valters.eu)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hugovalters)
[![Medium](https://img.shields.io/badge/Medium-Blog-black?style=for-the-badge&logo=medium&logoColor=white)](https://blog.valters.eu)

</div>
