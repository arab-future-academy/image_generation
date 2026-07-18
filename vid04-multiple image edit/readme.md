يتناول هذا الفيديو كيفية إنشاء صورة واحدة انطلاقًا من عدة صور باستخدام نموذجي **Qwen Image Edit** و**FireRed Image Edit**.

## الملفات المرفقة

- [`image_firered_image_edit1_1.json`](image_firered_image_edit1_1.json): سير عمل جاهز في ComfyUI لتحرير صورة بالاستعانة بعدة صور مرجعية باستخدام **FireRed Image Edit 1.1**.
- [`image_qwen_image_edit_2511.json`](image_qwen_image_edit_2511.json): سير عمل جاهز في ComfyUI لإنشاء صورة من عدة صور باستخدام **Qwen Image Edit 2511**.
- [`nodes_qwen.py`](nodes_qwen.py): نسخة معدّلة من عقد Qwen في ComfyUI، توسّع عقدة **TextEncodeQwenImageEditPlus** لتقبل ما يصل إلى ست صور مُدخلة.

## روابط FireRed Image Edit

- [المستودع على GitHub](https://github.com/FireRedTeam/FireRed-Image-Edit)
- [النموذج على Hugging Face](https://huggingface.co/FireRedTeam/FireRed-Image-Edit-1.1)
- [الورقة البحثية على arXiv](https://arxiv.org/pdf/2602.13344)

## روابط Qwen Image Edit

- [النموذج على Hugging Face](https://huggingface.co/Qwen/Qwen-Image-Edit-2511)
- [مستودع Qwen Image على GitHub](https://github.com/QwenLM/Qwen-Image)
- [دليل Qwen Image Edit 2511 في ComfyUI](https://docs.comfy.org/tutorials/image/qwen/qwen-image-edit-2511)

