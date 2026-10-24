# مشروع التنبؤ بإعادة إدخال المريض خلال 30 يومًا

## الملفات
- `readmission_prediction_project.ipynb`: المشروع كاملًا بخلايا شرح وكود منفصلة.
- `diabetes_dataset.zip`: ملف البيانات الذي نستخدمه في المشروع.
- `requirements.txt`: المكتبات المطلوبة.

## التشغيل
1. ثبتي Python وJupyter Notebook أو استخدمي Google Colab.
2. ثبتي المكتبات: `pip install -r requirements.txt`
3. افتحي `readmission_prediction_project.ipynb`.
4. شغّلي الخلايا بالترتيب من الأعلى إلى الأسفل.
5. اتركي `diabetes_dataset.zip` في المجلد نفسه بجانب الـ Notebook؛ سيستخرج الكود `diabetic_data.csv` تلقائيًا.

## الهدف
التنبؤ بما إذا كانت قيمة `readmitted` تساوي `<30`. القيمة 1 تعني إعادة إدخال خلال أقل من 30 يومًا، والقيمة 0 تعني `NO` أو `>30`.

## ملاحظات مهمة
- هذه بيانات تاريخية من مستشفيات أمريكية للفترة 1999–2008، وليست بيانات يمنية.
- المشروع تعليمي وليس أداة طبية.
- استخدمنا تقسيمًا بحسب `patient_nbr` لتقليل تسرب بيانات المريض نفسه بين التدريب والاختبار.
- اذكري مصدر البيانات في تقريرك: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008
