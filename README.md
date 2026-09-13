[العربية] | [English](README.en.md)

# A2kliDis Scoop Bucket

حزمة Scoop لتثبيت تطبيقات Windows وإدارتها بسهولة. يحتوي المستودع حاليا على
manifest لتطبيق [Mangayomi](https://github.com/kodjodevf/mangayomi).

[![CI](https://github.com/A2kliDis/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/A2kliDis/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/A2kliDis/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/A2kliDis/scoop-bucket/actions/workflows/excavator.yml)

## التثبيت

تأكد من تثبيت [Scoop](https://scoop.sh)، ثم أضف هذا المستودع وثبّت Mangayomi:

```powershell
scoop bucket add a2klidis https://github.com/A2kliDis/scoop-bucket
scoop install a2klidis/mangayomi
```

## التحديث

لتحديث التطبيق يدويا:

```powershell
scoop update
scoop update mangayomi
```

يتم فحص إصدارات Mangayomi الجديدة تلقائيا كل أربع ساعات بواسطة GitHub Actions.
يمكن متابعة عمليات الفحص والتحديث من تبويب [Actions](https://github.com/A2kliDis/scoop-bucket/actions).

## المساهمة

الـ manifests موجودة في مجلد `bucket`. يجب أن يحتوي أي manifest على رابط تحميل
صالح وبصمة SHA256 صحيحة، مع إعداد `checkver` و`autoupdate` عند توفرهما.
