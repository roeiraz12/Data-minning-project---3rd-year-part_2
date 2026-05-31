# Data-minning-project---3rd-year-part_2
Creating a Python Elastic Net &amp; RF models to predict movies IMDB's rating.


------------------------------------רשימת דרישות להרצת המודל:
------------------------------------שמירת הקובץ dataset.csv בשם הזה בתיקייה בה נריץ את הקוד.
------------------------------------שמירת הקובץ title.crew.tsv.gz בשם הזה בתקייה בה נריץ את הקוד.
הקוד שנכתב מייבא ספריות באופן עצמאי ועובד לפי גרסאות אלו:




asttokens==3.0.1
beautifulsoup4==4.14.3
Boruta==0.4.3
Bottleneck==1.4.2
brotlicffi==1.2.0.0
certifi==2026.4.22
cffi==2.0.0
charset-normalizer==3.4.4
colorama==0.4.6
comm==0.2.3
contourpy==1.3.1
cycler==0.12.1
debugpy==1.8.16
decorator==5.2.1
et_xmlfile==2.0.0
exceptiongroup==1.3.0
executing==2.2.1
fonttools==4.62.1
idna==3.11
ipykernel==7.2.0
ipython==8.30.0
jedi==0.19.2
joblib==1.5.3
jupyter_client==8.8.0
jupyter_core==5.9.1
kiwisolver==1.4.9
matplotlib-inline==0.2.1
matplotlib==3.10.8
mkl-service==2.5.2
mkl_fft==2.1.1
mkl_random==1.3.0
nest-asyncio==1.6.0
numexpr==2.14.1
numpy==2.2.5
openpyxl==3.1.5
packaging==26.0
pandas==2.3.3
parso==0.8.5
patsy==1.0.2
pillow==12.1.1
pip==26.0.1
platformdirs==4.9.4
ppscore==1.3.1
prompt_toolkit==3.0.52
psutil==7.0.0
pure_eval==0.2.3
pycparser==3.0
Pygments==2.20.0
pyparsing==3.2.5
PyQt5==5.15.11
PyQt5_sip==12.17.0
PySocks==1.7.1
python-dateutil==2.9.0.post0
pytz==2026.1.post1
pywin32==311
pyzmq==27.1.0
requests==2.33.1
scikit-learn==1.7.2
scipy==1.15.3
seaborn==0.13.2
setuptools==82.0.1
sip==6.12.0
six==1.17.0
soupsieve==2.5
stack_data==0.6.3
statsmodels==0.14.6
threadpoolctl==3.6.0
tomli==2.4.0
tornado==6.5.5
tqdm==4.67.3
traitlets==5.14.3
typing_extensions==4.15.0
tzdata==2025.3
urllib3==2.6.3
wcwidth==0.2.14
wheel==0.46.3
win_inet_pton==1.1.0



------------------------------------------------------תיאור המודל--------------------------------------------------


המודל מקבל dataset נקי ומוכן לעיבוד וללמידה ולצורך כך משתמש בעמודות ספציפיות אשר עברו סינון פילטר Boruta. הנתונים מחולקים לנתוני אימון ומבחן 80-20.

Elastic Net - מנסה למצוא ישר הממזער את השגיאה הממוצעת

HGB- מודל מבוסס יער רנדומלי המשפר את דיוקו בכל איטרציה














