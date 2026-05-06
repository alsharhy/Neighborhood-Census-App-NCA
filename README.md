# Neighborhood Census App (NCA)

## Overview

تطبيق أندرويد مخصص لإجراء التعداد السكاني على مستوى الأحياء، حيث يتم توزيعه على عُقّال الحارات ليقوم كل عاقل بإدخال بيانات السكان ضمن نطاقه الجغرافي بطريقة منظمة وسريعة.

A dedicated Android application for conducting neighborhood-level population censuses, distributed to neighborhood leaders (Aqel Al-Harat) to enable each leader to enter resident data within their geographical scope in an organized and efficient manner.

## Project Goal

إنشاء نظام رقمي بسيط وفعال لتجميع بيانات السكان بدقة، بهدف:

*   تسهيل عمليات الإحصاء السكاني
*   دعم الجهات المحلية ببيانات محدثة
*   تحسين التخطيط للخدمات (الصحية، التعليمية، الأمنية)

To create a simple and effective digital system for accurately collecting population data, aiming to:

*   Facilitate population census operations
*   Support local authorities with updated data
*   Improve planning for services (health, education, security)

## How it Works

*   يتم تسليم التطبيق لكل عاقل حارة
*   يقوم العاقل بإدخال بيانات كل فرد داخل الحارة
*   يتم حفظ البيانات محليًا أو رفعها إلى قاعدة بيانات مركزية

*   The application is delivered to each neighborhood leader.
*   The leader enters data for each individual within the neighborhood.
*   Data is saved locally or uploaded to a central database.

## Key Features

**تسجيل بيانات السكان:**

*   الاسم الكامل
*   رقم الهاتف
*   العنوان
*   الصورة الشخصية

*   واجهة بسيطة وسهلة الاستخدام
*   دعم العمل بدون إنترنت (Offline Mode)
*   مزامنة البيانات عند توفر الإنترنت
*   إدارة السجلات (إضافة / تعديل / حذف)
*   ربط كل عاقل بمنطقة محددة

**Resident Data Registration:**

*   Full Name
*   Phone Number
*   Address
*   Personal Photo

*   Simple and easy-to-use interface
*   Offline Mode support
*   Data synchronization when internet is available
*   Record management (add / edit / delete)
*   Linking each leader to a specific area

## Technologies Used

*   Flutter أو Android Native (Java / Kotlin)
*   SQLite (للتخزين المحلي)
*   Firebase (اختياري للمزامنة السحابية)
*   Image Picker لرفع الصور

*   Flutter or Android Native (Java / Kotlin)
*   SQLite (for local storage)
*   Firebase (optional for cloud synchronization)
*   Image Picker for photo uploads

## Application Structure

*   Login Screen: تسجيل دخول العاقل
*   Dashboard: عرض عدد السكان المسجلين
*   Add Resident Screen: إضافة بيانات شخص
*   Residents List: عرض جميع السكان
*   Profile Screen: بيانات العاقل

*   Login Screen: Leader login
*   Dashboard: Display registered resident count
*   Add Resident Screen: Add person's data
*   Residents List: Display all residents
*   Profile Screen: Leader's data

## System Requirements

*   Android 6.0 أو أحدث
*   إذن الوصول للكاميرا
*   إذن الوصول للتخزين

*   Android 6.0 or newer
*   Camera access permission
*   Storage access permission

## Usage Steps

1.  تسجيل الدخول من قبل عاقل الحارة
2.  الدخول إلى شاشة إضافة السكان
3.  إدخال البيانات المطلوبة لكل فرد
4.  التقاط أو رفع صورة شخصية
5.  حفظ البيانات
6.  تكرار العملية لباقي السكان

1.  Leader logs in.
2.  Access the Add Resident screen.
3.  Enter required data for each individual.
4.  Capture or upload a personal photo.
5.  Save data.
6.  Repeat the process for other residents.

## Security and Privacy

*   تخزين البيانات بشكل مشفر (إن أمكن)
*   تقييد الوصول حسب المستخدم
*   عدم مشاركة البيانات بدون صلاحيات

*   Data storage with encryption (if possible)
*   Access restriction based on user
*   No data sharing without authorization

## Future Development Ideas

*   إضافة نظام تحديد الموقع (GPS)
*   ربط التطبيق بلوحة تحكم (Dashboard Web)
*   تقارير وإحصائيات تلقائية
*   دعم البصمة أو التعرف على الوجه لتسجيل الدخول
*   تصدير البيانات بصيغة Excel أو PDF

*   Adding GPS tracking system
*   Linking the application to a web dashboard
*   Automatic reports and statistics
*   Fingerprint or facial recognition support for login
*   Exporting data in Excel or PDF format

---
