# notes/
# lib/
# ├── core/                     # يحتوي على الأكواد المشتركة
# ├── data/                     # يحتوي على الطبقة الخاصة بتوفير البيانات
# │   ├── datasources/          # الوصول لقاعدة البيانات
# │   ├── models/               # نماذج البيانات
#    └── repositories/         # تنفيذ واجهات المستودعات
# ├── domain/                   # يحتوي على المنطق الأساسي للتطبيق
# │   ├── entities/             # الكيانات الأساسية
# │   ├── repositories/         # واجهات المستودعات
# │   └── usecases/             # حالات الاستخدام (الوظائف)
# ├── presentation/             # كل ما يخص واجهة المستخدم
# │   ├── pages/                # صفحات التطبيق
# │   ├── providers/            # إدارة الحالة (State Management)
# │   └── widgets/              # Widgets القابلة لإعادة الاستخدام
# ├── main.dart                 # نقطة دخول التطبيق
