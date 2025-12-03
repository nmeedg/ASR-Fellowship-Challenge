## Download Model checkpoints

The fine-tuned model are also available on Google Drive:

[Download finetuned model](https://drive.google.com/drive/folders/11P8TKhTTivboGOkYjsD5PLV-47yRrc76?usp=sharing)
[Download only model.safetensors](https://drive.google.com/file/d/1eqt0hHzBflu-V-iuu88T4reAXf4dQpUR/view?usp=sharing)
**Instructions (for finetuned model):**  
just download model adn load using :
` model_dir = "download model path"
fin_processor = Wav2Vec2Processor.from_pretrained(model_dir,target_lang="kin")
fin_model = Wav2Vec2ForCTC.from_pretrained(model_dir)`


**Instructions (for model.safetensors only):**  
1. Download the file `model.safetensors`.  
2. Place it in a folder named `checkpoints/checkpoints-600`
