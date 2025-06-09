# Desktop-Pal-App-Win64

Desktop Pal App - Native TTS LLM A.I Desktop Companion

Download v0.0.13.0a: https://drive.google.com/file/d/10DlltpqX3shkST-ygmyHHSjodQI8Hvl5/view?usp=sharing

-Fixed a sound issue when app window becomes unfocused, the speech audio could not be heard.

===========================================================

![417135134-2274b4d5-3bef-43b0-a027-7b629d1d4072](https://github.com/user-attachments/assets/3f416172-306e-4ac2-b7fa-a96f9af0003f)

===========================================================

Controls:

Hold T key while talking into microphone to speak to the a.i

F6 & F7 Keys can toggle the UIs on and off.

F11 Key toggles between Fullscreen & Windowed Mode

F2 key makes the app clickable.

F3 key makes you be able to click through the app.

F10 key makes the app window always on top.

F12 key makes the app window disable being on top.

===========================================================

Introducing Desktop Pal, an AI-powered companion that seamlessly integrates into your desktop experience, bringing a new level of interaction to your digital workspace. Powered by native text-to-speech LLM models, Desktop Pal allows you to converse, engage, and get assistance—all while continuing your tasks without interruption.

Your default companion, Riku, is a friendly and intelligent female AI who’s not just here to help, but to connect with you. Whether you need support with your work, want to brainstorm ideas, or simply need someone to talk to, Desktop Pal is always there. With the ability to enter any initial prompt and use any GGUF model downloaded from Hugging Face, you can personalize your companion to suit your needs and make every interaction feel more natural.

More than just an assistant, Desktop Pal is a true companion—working alongside you, enhancing your workflow, and offering companionship in your daily tasks. Say goodbye to boring, impersonal tools, and welcome an AI that truly feels like part of your workspace.

===========================================================

Commands:

Dress her in her regular attire: "Put on your normal clothes"

Dress her in her bikini attire: "Put on your bikini suit"

Dress her in her sleep attire: "Put on your sleep wear"

===========================================================

It is highly recommended to install Cuda 12.2 for use with the LLM and if Cuda is not detected it will use CPU instead.

https://developer.nvidia.com/cuda-12-2-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exe_local

===========================================================

The GGUF LLM model can be replaced in the packaged build of the app to any that you want to use, Just change the new model file name to what the current model file name is and it should work as long as its .gguf file format.

100% offline, NO internet needed to run it, it is completely local only. The A.I's Feature TTS Voices and Speech recognition en-us, everything running 100% offline on your PC with privacy!

work in progress that is currently in the early alpha stage at the moment.

===========================================================

v0.0.12.0 Update:

-Optimized and changed code for saving & loading LLM chat history, now has very fast loading of saved chat history.

-Removed auto saving of chat history, Added a new Save Chat Button so you can decide when you want to save chat.

-Handles larger contexts better now. (faster LLM text generation than before when context becomes big)

v0.0.11.0 Update:

Enabled CUDA support as the defaut, The LLM will generate text much faster & use more GPU layers now.

Applied Updated TTS & Audio Importer.

v0.0.10.0 Update:

Choose from 3 different TTS Voices at runtime in the new dropdown selection options.

-Implemented high quality TTS Kokoro 82M voice model "Jessica" for selection as the A.I's voice

-Implemented high quality TTS Kokoro 82M voice model "Heart" for selection as the A.I's voice

-Implemented fastest TTS "Libritts_R Medium" for selection as the A.I's voice

===========================================================

Recommended System Requirements:

Ram: 16GB

Video Ram: 6GB

SSD/HDD: 10GB

Direct X 11 & Direct X 12

OS: Windows 11 64bit

Requires a CPU that supports AVX, AVX2 and FMA.

The following CPUs should work:

Intel: 4th Generation (Haswell) and above

AMD: All Ryzen series

========================================

AkumaVenom's Discord: https://discord.gg/Uf8Q8usSmk

===========================================================

Save Data Info:

Save data is located in the hidden appdata folder: C:\Users\computername\AppData\Local\DesktopPal\Saved\SaveGames

ChatHistory.sav is all the history of chat you have had with the LLM AI, Delete it to start over with her.

===========================================================

![Screenshot 2025-02-26 152321](https://github.com/user-attachments/assets/c59ebebc-ae50-49da-b546-a1a51b01ed0c)
