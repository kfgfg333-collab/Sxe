# Костюмный референс Веры

## Исследование костюма
| Элемент | Решение для эпохи | Источник |
|---|---|---|
| Нижняя/верхняя одежда | | |
| Обувь | | |
| Головной убор / причёска | | |
| Материалы и цвета (винный акцент) | | |
| Аксессуары (брошь-компас как фибула/застёжка?) | | |
| Социальный статус «легенды» | | |
| Где спрятан прибор | | |

## Что загрузить (ingredients)
- `references/vera_face_reference.png` — лицо (источник идентичности)
- `references/vera_body_reference.png` — тело и пропорции
- (опц.) изображение исторического костюма/музейного предмета как референс одежды

## Промпт 1 — полный рост (Nano Banana во Flow или Gemini)
```
Use the uploaded face and body images as the strict identity reference for the same woman, Vera. Keep exactly the same face, age (mid-twenties), eye shape and grey-green eye color, the small mole under the eye, light freckles, dark-brown shoulder-length wavy slightly messy hair with an asymmetric strand, and the same slim athletic natural adult proportions. Change only the clothing and hairstyle to [EPOCH COSTUME DESCRIPTION]. Full-body front view, standing in a relaxed neutral pose, arms slightly away from the body so the costume reads clearly, plain light warm-grey studio background, soft even lighting, high detail on fabrics and fastenings. Semi-realistic cinematic 3D/2.5D animation style with a subtle painterly texture; not cartoonish, not photorealistic. Single character only, no text, no logos, no watermark, no props except [PROPS].
```

## Промпт 2 — портрет (по необходимости: головной убор, причёска)
```
Same woman, Vera, from the uploaded face reference: identical face, grey-green eyes, mole under the eye, freckles, dark-brown hair. Head-and-shoulders portrait, three-quarter view, wearing [HEADWEAR / NECKLINE DETAILS]. Plain light warm-grey background, soft key light. Semi-realistic cinematic animation style with painterly texture. No text, no logos.
```

## Отбор
Лицо узнаётся? Родинка на месте? Пропорции не «кукольные»? Костюм без анахронизмов? → сохранить как `refs/costume.png` и ассет Flow `vera_EPNN_costume`.
