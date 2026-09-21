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
Upload these files to your server path (e.g. `/home/container/` on Katabump):

```text
index.js
package.json
```

#### 3️⃣ Install & Start

```bash
npm install
node index.js
```

Or with npm:

```bash
npm start
```

#### 4️⃣ Open the Panel
After start, open:

```text
http://YOUR_IP:PORT/parham-confing
```

You will see the panel address in the console when it starts.

---

### ♾️ Make It Unlimited (Katabump Renew)

Katabump free servers usually need **Renew** every ~4 days.

#### Option A — Manual
1. Go to [Katabump Panel](https://control.katabump.com)
2. Login → open your server
3. Click **Renew** when available

#### Option B — Auto Renew (GitHub Actions)
1. Create a GitHub repo and add `renew.py` + workflow file
2. Add secrets:
   - `KATABUMP_EMAIL`
   - `KATABUMP_PASSWORD`
   - `SERVER_ID`
3. The workflow runs every 3 days and clicks Renew automatically

> 💡 Keep your server online so the panel stays accessible.

---

### 📁 Project Structure

```text
📦 Panel - VPS
 ┣ 📜 index.js          → Main panel + proxy engine (standalone)
 ┣ 📜 package.json      → Dependencies
 ┗ 📜 Time Ultimited.txt → Renew helper notes
```

---

### 🛠️ Tips

- ✅ Use **Hard Refresh** (`Ctrl + Shift + R`) after updates
- ✅ If panel doesn't open, check the port and firewall
- ✅ Configs appear in the **Configs** and **Subs** tabs
- ✅ Copy subscription links into v2ray / Hiddify / Clash Meta

---

### 📣 Telegram Channel

<p align="center">
  <a href="https://t.me/parham_ste01">
    <img src="https://img.shields.io/badge/Telegram-Parham_01-blue?style=for-the-badge&logo=telegram" alt="Telegram">
  </a>
</p>

**Channel:** [https://t.me/parham_ste01](https://t.me/parham_ste01)

---

<br>

# 🇮🇷 فارسی

### 📖 درباره پروژه

**Panel - VPS** یک پنل سبک و یک‌فایلی برای مدیریت کانفیگ‌های پروکسی روی سرورهای **Katabump** و VPS لینوکس است.

ظاهر شیشه‌ای، سریع، و مناسب موبایل و دسکتاپ.

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

#### 3️⃣ نصب و اجرا

```bash
npm install
node index.js
```

یا:

```bash
npm start
```

#### 4️⃣ باز کردن پنل
بعد از اجرا آدرس پنل این شکلی است:

```text
http://IP_سرور:پورت/parham-confing
```

آدرس دقیق در کنسول هم نمایش داده می‌شود.

---

### ♾️ نامحدود کردن (تمدید Katabump)

سرورهای رایگان کاتابامپ معمولاً هر حدود **۴ روز** نیاز به **Renew** دارند.

#### روش ۱ — دستی
1. برو به [پنل کاتابامپ](https://control.katabump.com)
2. لاگین کن و سرورت را باز کن
3. وقتی دکمه **Renew** فعال بود بزن

#### روش ۲ — تمدید خودکار (GitHub Actions)
1. یک ریپو بساز و فایل `renew.py` و workflow را بگذار
2. این Secretها را اضافه کن:
   - `KATABUMP_EMAIL`
   - `KATABUMP_PASSWORD`
   - `SERVER_ID`
3. ورک‌فلو هر ۳ روز یک‌بار خودکار Renew را می‌زند

> 💡 سرور را آنلاین نگه دارید تا پنل در دسترس بماند.

---

### 📁 ساختار پروژه

```text
📦 Panel - VPS
 ┣ 📜 index.js          → پنل + موتور پروکسی (یک‌تکه)
 ┣ 📜 package.json      → وابستگی‌ها
 ┗ 📜 Time Ultimited.txt → راهنمای تمدید
```

---

### 🛠️ نکات مهم

- ✅ بعد از آپدیت یک بار **Hard Refresh** بزن (`Ctrl + Shift + R`)
- ✅ اگر پنل باز نشد، پورت و فایروال را چک کن
- ✅ کانفیگ‌ها در تب **Configs** و **Subs** هستند
- ✅ لینک ساب را در v2ray / Hiddify / Clash Meta وارد کن

---

### 📣 کانال تلگرام

<p align="center">
  <a href="https://t.me/parham_ste01">
    <img src="https://img.shields.io/badge/Telegram-Parham_01-blue?style=for-the-badge&logo=telegram" alt="Telegram">
  </a>
</p>

**کانال:** [https://t.me/parham_ste01](https://t.me/parham_ste01)

---

<p align="center">
  <b>Made with ❤️ by Parham - 01</b>
</p>
