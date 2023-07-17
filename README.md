# Fall Detection
Задание в рамках направления CV интенсива ШИФТ от ЦФТ.

## Датасет
[Fall Detection](https://universe.roboflow.com/roboflow-universe-projects/fall-detection-ca3o8/dataset/1) (3.1k изображений) в формате YOLOv5. 

## Код
[Ноутбук в Google Colab](https://colab.research.google.com/drive/1OkyIWzUBo2p_53AHqUMD0Sek4OlJj_Hb#scrollTo=WtJwIMZN-FJi)

## Модель
VGG19 + регрессия на 4 числа.  
[Веса модели](https://drive.google.com/drive/folders/1UNzfhx8gGIfSehoYAZIB0b5oqMVB8TxV)

## Аугментации
1. Horizontal Flip
2. Britness, Contrast, Saturation, Hue
3. Motion Blur
4. Emboss
5. Pixel dropout
6. Sepia
