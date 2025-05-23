# 💬 Wegap Widget for Electron / ویجت ویگپ برای Electron

This repository contains the official Electron version of the Wegap widget.  
این مخزن شامل نسخه رسمی ویجت ویگپ برای اپلیکیشن‌های دسکتاپ مبتنی بر Electron است. با استفاده از این ویجت می‌توانید قابلیت‌هایی مانند **چت، تماس صوتی/تصویری، دانشیار هوش مصنوعی و مرکز تماس** را به برنامه‌های دسکتاپ خود اضافه کنید.

---

## 📦 Installation / نصب

```bash
npm install @wegapnet/widget-electron
```

---

## 🚀 Quick Usage / استفاده سریع

در فایل `renderer.js` یا بخشی از React/Vue در UI:

```js
import { WegapWidget } from '@wegapnet/widget-electron';

WegapWidget.init({
  authKey: 'YOUR_AUTH_KEY',
  theme: 'light',
  position: 'bottom-right',
  language: 'fa'
});
```

> در صورتی که از فریم‌ورک‌هایی مانند React در بخش رابط کاربری استفاده می‌کنید، تابع `init` را در `useEffect` فراخوانی نمایید.

---

## ⚙️ Config Options / تنظیمات

| Prop Name | Type   | Description EN                                      | توضیح فارسی |
|-----------|--------|------------------------------------------------------|--------------|
| authKey   | string | Your unique authentication key                      | کلید احراز هویت شما |
| theme     | string | Theme mode: `light` or `dark`                       | تم: روشن یا تیره |
| position  | string | Widget position: `bottom-right`, `bottom-left`, etc | موقعیت ویجت |
| language  | string | Default widget language (fa, en, ar, ...)           | زبان پیش‌فرض |

---

## 📄 Documentation / مستندات کامل

- [See full guide in Wegap Wiki](https://wegap.net/wiki/electron/نصب-و-راه-اندازی/راهنمای-ویجت-ویگپ/دانشیار-ویگپ-id-8918)
- مشاهده راهنما در ویکی ویگپ ↑
