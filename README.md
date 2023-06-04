# text2speech

conda activate <python 3.10>

pip install TTS

pip install git+https://github.com/repodiac/german_transliterate

tts --text "Hallo Mariatta und Peter! Viele Grüße von den Pfälzern aus dem malerischen Kaiserslautern." --model_name "tts_models/de/thorsten/tacotron2-DDC" --out_path output.wav
