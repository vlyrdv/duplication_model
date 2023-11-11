# duplication_model


Решение команды **P2P team**

### Структура проекта

1. model.ipynb - основной код проекта
2. lip-sync.ipynb - модель для создание реалистичного lip-sync
3. state - папка с видео

### Running the project
Перед запуском надо установить все необходимые библиотеки
```   !pip install spleeter
      !pip install ffmpeg
      !pip install -U openai-whisper
      !pip install git+https://github.com/openai/whisper.git
      !pip install --upgrade --no-deps --force-reinstall git+https://github.com/openai/whisper.git
      !pip install setuptools-rust
      !pip install translators
      !pip install scipy
      !pip install nltk
      !pip install torch
      !pip install transformers
      !pip install bark
      !pip install torch==2.0.0 torchvision==0.15.1 torchaudio==2.0.1
      !pip install colorama
      !pip install gTTS
      !pip install pydub
      !pip install playsound
      !pip install ffmpeg-python
      !pip install spleeter
      !pip install audio-effects
      !pip install moviepy
      !pip install TTS
      !git clone https://github.com/coqui-ai/TTS
      !pip install -e all
```



# Инструкция по работе с model.ipynb

1. запустите библиотеки

2. подгрузка моделей

3. выбор языка для перевевода

4. загрузите видео, которое хотите перевести и пропишите его название      

```uploaded = 'name_your_video.mp4' ```<br /><br />



# Пример работы


<h2> Исходное видео</h2>

https://github.com/vlyrdv/duplication_model/assets/95037700/8f663860-06d2-4246-b9ee-972f7a2f4666

<h2> Видео без lip-sync </h2>

https://github.com/vlyrdv/duplication_model/assets/95037700/98070cce-83be-4ee7-a1d9-cf0b070de700

<h2> Видео с lip-sync </h2>

https://github.com/vlyrdv/duplication_model/assets/95037700/17fe745c-c2e8-4c51-9380-97c2d35fc7d4

# Архитектура

![Group 2](https://github.com/vlyrdv/duplication_model/assets/95037700/4097702e-a20e-4352-ab7d-dd7f51720242)
<br>
<h2>В проекте участвовали </h2>
<h3><a href="https://github.com/vlyrdv">Урядов Валерий</a></h3>
<h3><a href="https://github.com/abrikosmna">Мокийчук Никита</a></h3>
<h3><a href="https://github.com/GermanKek-lab">Кек Герман</a></h3>
