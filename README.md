# منصة ثانويا - Thaneya

منصة تعليمية حديثة وشاملة لطلاب الثانوية العامة المصريين.

## 🌟 المميزات

- ✅ تصميم حديث وسريع وسلس
- ✅ 11 مادة دراسية متكاملة
- ✅ محاضرات فيديو منظمة
- ✅ ملفات وملخصات
- ✅ نظام المفضلات
- ✅ لوحة تحكم للطالب
- ✅ بحث ذكي وسريع
- ✅ وضع ليلي احترافي
- ✅ تصميم متجاوب 100%
- ✅ SEO محسّن

## 🛠️ التقنيات المستخدمة

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, Framer Motion
- **State Management**: Zustand
- **Database**: Supabase
- **Deployment**: Vercel
- **Icons**: Lucide React
- **Animations**: Framer Motion

## 📦 المتطلبات

- Node.js 18+ أو Bun
- npm أو yarn أو bun

## 🚀 البدء السريع

### 1. تثبيت المكتبات

```bash
npm install
# أو
yarn install
# أو
bun install
```

### 2. إعداد متغيرات البيئة

انسخ ملف `.env.example` إلى `.env.local`:

```bash
cp .env.example .env.local
```

### 3. تشغيل التطبيق محليًا

```bash
npm run dev
# أو
yarn dev
# أو
bun dev
```

افتح [http://localhost:3000](http://localhost:3000)

## 📁 هيكل المشروع

```
src/
├── app/                 # صفحات التطبيق (Next.js 14 App Router)
│   ├── page.tsx         # الصفحة الرئيسية
│   ├── subjects/        # صفحات المواد
│   ├── search/          # صفحة البحث
│   ├── dashboard/       # لوحة التحكم
│   ├── favorites/       # الصفحة المفضلة
│   └── layout.tsx       # التخطيط الرئيسي
├── components/          # المكونات القابلة لإعادة الاستخدام
│   ├── Button.tsx       # مكون الزر
│   ├── Card.tsx         # مكون البطاقة
│   ├── Navbar.tsx       # شريط التنقل
│   ├── ThemeProvider.tsx # توفير المظهر
│   └── Loading.tsx      # مكونات التحميل
├── lib/                 # الدوال والثوابت المساعدة
│   ├── constants.ts     # الثوابت العامة (المواد، المسارات)
│   └── supabase.ts      # إعدادات Supabase (اختياري)
├── store/               # إدارة الحالة (Zustand)
│   └── useStore.ts      # المتجر الرئيسي
├── styles/              # الأنماط العامة
│   └── globals.css      # CSS عام مع RTL
├── types/               # أنواع TypeScript
│   └── index.ts         # تعريفات الأنواع
└── utils/               # الدوال المساعدة
    └── cn.ts            # دالة دمج CSS
```

## 🎨 تخصيص المشروع

### تغيير الألوان

عدّل ملف `tailwind.config.ts`:

```typescript
colors: {
  primary: {
    600: '#0284c7', // غيّر اللون هنا
  },
}
```

### إضافة موضوعات جديدة

أضف مواد جديدة في `src/lib/constants.ts`:

```typescript
{
  id: 'new-subject',
  name: 'new_subject',
  displayName: 'New Subject',
  arabicName: 'الموضوع الجديد',
  color: '#8b5cf6',
  icon: '📚',
  description: 'وصف الموضوع',
}
```

## 🚀 النشر على Vercel

### 1. دفع الكود إلى GitHub

```bash
git add .
git commit -m "Initial commit"
git push origin dev/educational-platform
```

### 2. الربط مع Vercel

1. اذهب إلى [vercel.com](https://vercel.com)
2. انقر "New Project"
3. اختر مستودع GitHub
4. أضف متغيرات البيئة
5. انقر "Deploy"

## 📝 الترخيص

هذا المشروع مرخص تحت MIT License

## 👨‍💻 المساهمة

نرحب بالمساهمات! الرجاء:

1. اعمل Fork للمشروع
2. أنشئ فرع جديد (`git checkout -b feature/AmazingFeature`)
3. اعمل Commit (`git commit -m 'Add AmazingFeature'`)
4. اعمل Push (`git push origin feature/AmazingFeature`)
5. افتح Pull Request

## 🎯 الرؤية

نهدف لتكون ثانويا المنصة الأولى والموثوقة للطلاب المصريين، توفر كل المحتوى التعليمي في مكان واحد.

---

صنع بـ ❤️ لطلاب الثانوية العامة
