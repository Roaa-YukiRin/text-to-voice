# text-to-voice
تحويل النص الى صوت
![image](https://github.com/user-attachments/assets/09695002-8b7f-4a19-a734-ecb9734c083b)
![image](https://github.com/user-attachments/assets/ce2635cf-fbf1-4444-95fb-7d2c512868dd)
![image](https://github.com/user-attachments/assets/9d1ba592-4389-40ff-b239-89f14fc3f3b0)
![image](https://github.com/user-attachments/assets/64d2660c-d07a-4556-a5aa-0881b506c3dc)
![image](https://github.com/user-attachments/assets/9eab3949-0373-4bb2-acde-e72ea782d1f5)
![image](https://github.com/user-attachments/assets/3438e68c-e41d-46c1-949d-67846f312bd3)
![image](https://github.com/user-attachments/assets/173cca35-52c2-4c42-852c-c8785dc071c6)
![image](https://github.com/user-attachments/assets/33d6e11f-f6b7-477f-bdb7-b5b1fb678e68)
![image](https://github.com/user-attachments/assets/a545e488-3e1c-48c4-91eb-4642fd8ab1ce)
![image](https://github.com/user-attachments/assets/d67d48a1-65fa-492e-bd43-a8098d56f388)
![image](https://github.com/user-attachments/assets/2ec0100b-7ce0-4cad-9e2c-c4001351750c)
![image](https://github.com/user-attachments/assets/0e79937e-04d6-41ef-93f2-f77b80062693)
![image](https://github.com/user-attachments/assets/0b5f8971-2c51-4a33-8089-70ff66edeb0b)
![image](https://github.com/user-attachments/assets/5d084f43-be58-44c2-856d-20c122d3de65)
![image](https://github.com/user-attachments/assets/b32f6f5c-e62e-45d9-a1dd-84f364e7c14a)

========
# js
![image](https://github.com/user-attachments/assets/951cc08d-8cb4-4e52-b346-3223f5f046ba)
![image](https://github.com/user-attachments/assets/4198fc81-5973-4b09-b3a4-14af2d85f121)
![image](https://github.com/user-attachments/assets/f4624b08-6f44-4b09-846c-534b2a5c23a2)
====================
# python
![image](https://github.com/user-attachments/assets/1592c61a-c5d8-47de-96cc-9e497adcc019)
![image](https://github.com/user-attachments/assets/c13b9dd4-d50c-4c19-8430-d96b0938a305)
![image](https://github.com/user-attachments/assets/1e9f15ce-34b9-4230-b0a1-b777a1bcb568)

proplem:
![image](https://github.com/user-attachments/assets/ae8ba500-f10e-445f-90e4-3b27d0dbdddd)
![image](https://github.com/user-attachments/assets/df4b727c-a646-422e-8bee-beeac13e221b)

 proplem:
 ![image](https://github.com/user-attachments/assets/f11239f4-0876-4265-811a-f52a0a07db3d)
 يسترد النص من منطقة النص.
يرسل طلب POST إلى نقطة نهاية /tts بالنص.
عند تلقي الاستجابة، فإنه ينشئ عنوان URL صوتيًا من بيانات الكائن ويضبط سمة src لمشغل الصوت، ثم يقوم بتشغيل الصوت.
![image](https://github.com/user-attachments/assets/cceb59c3-936f-4c01-8e4a-56e275af1316)
يتلقى مسار /tts طلب POST مع النص المراد تحويله إلى كلام.
يتم تمرير النص إلى مكتبة gTTS، التي تولد ملف MP3 وتحفظه في "output.mp3".
ثم يعيد مسار /tts استجابة JSON مع عنوان URL لملف الصوت الناتج (/audio).
مسار /audio مسؤول عن تقديم ملف "output.mp3".
proplem : it dosent work!!!


