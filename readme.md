# Simple Voice Assistant

A simple voice assistant. 

If you are running the code on Apple Silicon, run the following command:

```sh
brew install portaudio
```

Create a virtual environment, update pip, and install the required packages:

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```
Run the assistant:

```sh
python3 assistant.py
```

---
## Resources

- <https://www.youtube.com/watch?v=zVttVCQvACQ>
- <https://github.com/svpino/alloy-voice-assistant>