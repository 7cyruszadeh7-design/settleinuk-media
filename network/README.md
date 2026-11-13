# شبکه‌ی SettleInUK — اتاق کنترل Mr Nolan

مدیر شبکه: **Mr Nolan** (تعریف نقش: `.claude/agents/mr-nolan.md`)

| پوشه / فایل | کاربرد |
|---|---|
| `managers.md` | فهرست مدیران ارشد و برنامه‌هایشان |
| `comms/<manager-id>/inbox` | پیام مدیر → Mr Nolan |
| `comms/<manager-id>/outbox` | پاسخ / دستور Mr Nolan → مدیر |
| `templates/` | قالب پیام‌ها (بریف، درخواست آپلود، درخواست تبلیغ، گزارش هفتگی) |
| `schedule/publishing-calendar.md` | تقویم مرجع انتشار |
| `youtube/upload-checklist.md` | چک‌لیست اجباری قبل از هر آپلود |
| `youtube/ads-tracker.md` | بودجه و نتایج تبلیغات |
| `reports/` | گزارش‌های هفتگی |

## اضافه کردن یک مدیر جدید
```bash
cp -r network/comms/_template network/comms/<manager-id>
```
سپس یک ردیف در `managers.md` اضافه کنید.

## فراخوانی Mr Nolan
در Claude Code: «Mr Nolan، صندوق‌ها را بررسی کن» — یا ایجنت `mr-nolan` را صدا بزنید.
