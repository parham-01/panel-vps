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

Katabump free servers usually need **Renew** every ~4 days.  
You can automate this with **GitHub Actions**.

#### Full guide + copy-ready codes
📄 **[Auto-Renew-Guide.txt](Auto-Renew-Guide.txt)** ← open this file, copy each code block into its file

#### Quick steps
1. Create a **new GitHub repo**
2. Add **two files** (codes are in the guide above):
   - `renew.py` → repo root
   - `.github/workflows/renew.yml`
3. Add Secrets: `KATABUMP_EMAIL` · `KATABUMP_PASSWORD` · `SERVER_ID`
4. Run once from **Actions** → **Run workflow**

Workflow runs every **3 days** automatically.

#### Katabump panel
🌐 **https://control.katabump.com**

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

سرورهای رایگان کاتابامپ معمولاً هر حدود **۴ روز** نیاز به **Renew** دارند.  
با **GitHub Actions** می‌توانید تمدید را خودکار کنید.

#### راهنمای کامل + کد آماده کپی
📄 **[Auto-Renew-Guide.txt](Auto-Renew-Guide.txt)** ← این فایل را باز کنید، هر بلوک کد را کپی و در فایل خودش بگذارید

#### مراحل سریع
1. یک **ریپوی جدید** در گیت‌هاب بسازید
2. **دو فایل** بسازید (کدها داخل راهنما است):
   - `renew.py` → ریشه ریپو
   - `.github/workflows/renew.yml`
3. Secrets را اضافه کنید: `KATABUMP_EMAIL` · `KATABUMP_PASSWORD` · `SERVER_ID`
4. یک‌بار از **Actions** → **Run workflow** تست کنید

بعد از آن هر **۳ روز** خودکار Renew می‌شود.

#### سایت کاتابامپ
🌐 **https://control.katabump.com**

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
