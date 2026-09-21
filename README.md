<p align="center">
  <img src="banner/banner.png" alt="Parham-01 Panel" width="100%">
</p>

<h1 align="center">⚡ Panel - VPS</h1>

<p align="center">
  <b>Parham - 01</b>
</p>

<p align="center">
  <a href="#-english">🇬🇧 English</a> &nbsp;•&nbsp;
  <a href="#-فارسی">🇮🇷 فارسی</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-18+-green?style=for-the-badge&logo=node.js" alt="Node">
  <img src="https://img.shields.io/badge/Platform-Katabump%20%7C%20VPS-blue?style=for-the-badge" alt="Platform">
  <img src="https://img.shields.io/badge/Panel-Glass%20UI-red?style=for-the-badge" alt="Panel">
</p>

---

# 🇬🇧 English

### 📖 About the Project

**Panel - VPS** is a lightweight, standalone control panel for managing multi-protocol proxy configs on **Katabump** containers and Linux VPS.

> 🆓 Designed especially for **Katabump free servers**.

Built for speed, clean UI, and easy one-file deployment.

| Feature | Description |
|--------|-------------|
| 🎨 Glass UI | Modern dark glassmorphism panel |
| 🔗 Multi Protocol | VLESS, Hysteria2, Trojan, Shadowsocks, WireGuard & more |
| 📱 Responsive | Works on desktop & mobile |
| ⚡ One File | Just upload `index.js` + `package.json` |
| 🔄 Auto Status | Live uptime, host, port & core status |

---

### 🚀 How to Run

#### 1️⃣ Requirements
- Node.js **18+**
- A Katabump container **or** any Linux VPS

#### 2️⃣ Upload Files
Upload these files to your server path (for example `/home/container/` on Katabump):

```text
index.js
package.json
```

#### 3️⃣ Start
After upload, the panel starts automatically.

⏳ Wait a few seconds until Node finishes loading.

When it is ready, the console shows the panel address, for example:

```text
http://YOUR_IP:PORT/parham-confing
```

Open that link in your browser — the panel is online.

> ✅ No need to type extra commands. Upload → wait → open the panel.

---

### ♾️ Unlimited (Auto Renew on Katabump)

This panel is made for **Katabump free servers**.  
Free servers usually need **Renew** about every 4 days. You can automate it with GitHub Actions.

#### 📄 Where are the codes?
Open this file and copy from there:

**[Auto-Renew-Guide.txt](Auto-Renew-Guide.txt)**

Above each code you will see the **exact file name**.

#### 📂 Files you must create

| File name | Full path in the new repo |
|-----------|---------------------------|
| `renew.py` | `renew.py` |
| `renew.yml` | `.github/workflows/renew.yml` |

Meaning:
1. In the new repo, create a file named **renew.py** (next to README if you have one)
2. Create folder **.github**
3. Inside it create folder **workflows**
4. Inside workflows create file **renew.yml**

#### ✅ Step by step

**Step 1 — New repository**  
Create a new repo on GitHub (can be private).

**Step 2 — File renew.py**  
Create `renew.py` → open Auto-Renew-Guide.txt → copy the code under `renew.py` → paste and save.

**Step 3 — File renew.yml**  
Create path `.github/workflows/renew.yml` → copy the code under that name from the guide → paste and save.

**Step 4 — Secrets (very important)**  
Go to: **Settings → Secrets and variables → Actions → New repository secret**

Add these three one by one:

| Secret name | What you type |
|-------------|----------------|
| `KATABUMP_EMAIL` | Your Katabump login email |
| `KATABUMP_PASSWORD` | Your Katabump password |
| `SERVER_ID` | Server ID from the server page URL on Katabump |

**Step 5 — Test once**  
Open **Actions** tab → select **Parham Confing Auto Renew** → **Run workflow**.

If it works, it will run automatically every **3 days**.

#### 🌐 Katabump website
https://control.katabump.com

---

### 📁 Project Structure

```text
📦 Panel - VPS
 ┣ 📜 index.js
 ┣ 📜 package.json
 ┣ 📜 Auto-Renew-Guide.txt     ← renew guide + copy codes
 ┗ 📁 banner
    ┗ 🖼️ banner.png
```

---

### 🛠️ Tips

- ✅ After updates, use **Hard Refresh** (`Ctrl + Shift + R`)
- ✅ Check port and firewall if the panel does not open
- ✅ Configs are in the **Configs** and **Subs** tabs
- ✅ Use subscription links in v2ray / Hiddify / Clash Meta

---

### 📣 Telegram

<p align="center">
  <a href="https://t.me/parham_ste01">
    <img src="https://img.shields.io/badge/Telegram-Channel-blue?style=for-the-badge&logo=telegram" alt="Channel">
  </a>
  &nbsp;
  <a href="https://t.me/+SchgZ4s1dGU4N2Y0">
    <img src="https://img.shields.io/badge/Telegram-Group-blue?style=for-the-badge&logo=telegram" alt="Group">
  </a>
</p>

**Channel:** [https://t.me/parham_ste01](https://t.me/parham_ste01)  
**Group:** [https://t.me/+SchgZ4s1dGU4N2Y0](https://t.me/+SchgZ4s1dGU4N2Y0)

---

<br>

# 🇮🇷 فارسی

### 📖 درباره پروژه

**Panel - VPS** یک پنل سبک و یک‌فایلی برای مدیریت کانفیگ‌های پروکسی روی سرورهای **Katabump** و VPS لینوکس است.

> 🆓 مخصوص **سرور رایگان کاتابامپ** طراحی شده.

ظاهر شیشه‌ای، سریع، مناسب موبایل و دسکتاپ.

| قابلیت | توضیح |
|--------|--------|
| 🎨 رابط شیشه‌ای | پنل تیره و مدرن Glass |
| 🔗 چند پروتکل | VLESS، Hysteria2، Trojan، Shadowsocks، WireGuard و بیشتر |
| 📱 واکنش‌گرا | دسکتاپ و اندروید |
| ⚡ یک فایل | فقط `index.js` و `package.json` |
| 🔄 وضعیت زنده | آپتایم، هاست، پورت و هسته‌ها |

---

### 🚀 آموزش اجرا

#### 1️⃣ پیش‌نیاز
- Node.js نسخه **۱۸ به بالا**
- کانتینر Katabump **یا** هر VPS لینوکس

#### 2️⃣ آپلود فایل‌ها
این فایل‌ها را روی سرور آپلود کنید (مثلاً مسیر `/home/container/` در کاتابامپ):

```text
index.js
package.json
```

#### 3️⃣ اجرا
بعد از آپلود، پنل **خودکار** راه می‌افتد.

⏳ چند ثانیه صبر کنید تا Node کامل لود شود.

وقتی آماده شد، آدرس پنل در کنسول دیده می‌شود، مثلاً:

```text
http://IP_سرور:پورت/parham-confing
```

همان لینک را در مرورگر باز کنید — پنل آنلاین است.

> ✅ لازم نیست دستوری تایپ کنید. آپلود → صبر → باز کردن پنل.

---

### ♾️ نامحدود کردن (تمدید خودکار Katabump)

این پنل برای **سرور رایگان کاتابامپ** ساخته شده.  
سرور رایگان معمولاً حدود هر ۴ روز یک‌بار نیاز به **Renew** دارد. می‌توانید با GitHub Actions خودکارش کنید.

#### 📄 کدها کجا هستند؟
این فایل را باز کنید و از آنجا کپی کنید:

**[Auto-Renew-Guide.txt](Auto-Renew-Guide.txt)**

بالای هر کد، **اسم دقیق فایل** نوشته شده است.

#### 📂 فایل‌هایی که باید بسازید

| اسم فایل | مسیر کامل داخل ریپوی جدید |
|----------|---------------------------|
| `renew.py` | `renew.py` |
| `renew.yml` | `.github/workflows/renew.yml` |

یعنی:
1. تو ریپوی جدید یک فایل به اسم **renew.py** بسازید
2. یک پوشه به اسم **.github** بسازید
3. داخلش پوشه **workflows** بسازید
4. داخل workflows فایل **renew.yml** را بسازید

#### ✅ مراحل دانه‌دانه

**مرحله ۱ — ریپوی جدید**  
یک ریپازیتوری جدید در گیت‌هاب بسازید (می‌تواند Private باشد).

**مرحله ۲ — فایل renew.py**  
فایل `renew.py` را بسازید → فایل Auto-Renew-Guide.txt را باز کنید → کد زیر اسم `renew.py` را کپی کنید → داخل فایل بچسبانید و ذخیره کنید.

**مرحله ۳ — فایل renew.yml**  
مسیر `.github/workflows/renew.yml` را بسازید → کد مربوط به همان اسم را از راهنما کپی کنید → بچسبانید و ذخیره کنید.

**مرحله ۴ — Secrets (خیلی مهم)**  
بروید به: **Settings → Secrets and variables → Actions → New repository secret**

این سه تا را یکی‌یکی اضافه کنید:

| نام Secret | چه چیزی بنویسید |
|------------|------------------|
| `KATABUMP_EMAIL` | ایمیل ورود کاتابامپ |
| `KATABUMP_PASSWORD` | رمز کاتابامپ |
| `SERVER_ID` | آیدی سرور از آدرس صفحه سرور در کاتابامپ |

**مرحله ۵ — یک‌بار تست**  
تب **Actions** را باز کنید → **Parham Confing Auto Renew** را بزنید → **Run workflow**.

اگر درست باشد، بعد از آن هر **۳ روز** خودکار تمدید می‌شود.

#### 🌐 سایت کاتابامپ
https://control.katabump.com

---

### 📁 ساختار پروژه

```text
📦 Panel - VPS
 ┣ 📜 index.js
 ┣ 📜 package.json
 ┣ 📜 Auto-Renew-Guide.txt     ← راهنمای تمدید + کد آماده کپی
 ┗ 📁 banner
    ┗ 🖼️ banner.png
```

---

### 🛠️ نکات مهم

- ✅ بعد از آپدیت یک بار **Hard Refresh** بزنید (`Ctrl + Shift + R`)
- ✅ اگر پنل باز نشد، پورت و فایروال را چک کنید
- ✅ کانفیگ‌ها در تب **Configs** و **Subs** هستند
- ✅ لینک ساب را در v2ray / Hiddify / Clash Meta وارد کنید

---

### 📣 تلگرام

<p align="center">
  <a href="https://t.me/parham_ste01">
    <img src="https://img.shields.io/badge/Telegram-Channel-blue?style=for-the-badge&logo=telegram" alt="Channel">
  </a>
  &nbsp;
  <a href="https://t.me/+SchgZ4s1dGU4N2Y0">
    <img src="https://img.shields.io/badge/Telegram-Group-blue?style=for-the-badge&logo=telegram" alt="Group">
  </a>
</p>

**کانال:** [https://t.me/parham_ste01](https://t.me/parham_ste01)  
**گپ:** [https://t.me/+SchgZ4s1dGU4N2Y0](https://t.me/+SchgZ4s1dGU4N2Y0)

---

<p align="center">
  <b>Made with ❤️ by Parham - 01</b>
</p>
