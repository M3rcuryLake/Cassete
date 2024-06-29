# Cassette

Cassette is a Python program designed to create 30-second explanatory videos suitable for Instagram Reels or YouTube Shorts. It offers multiple customization options for creating personalized videos. The program utilizes various APIs and libraries, including GPT-3.5-turbo model for transcript generation, AssemblyAI API for subtitle generation, UnrealSpeech API for voiceover generation, and ffmpeg along with moviepy for video editing.
The 'seewav' module in the given codebase is a modified version of a [pull request](https://github.com/adefossez/seewav/pull/7) by @Phoenix616 at the github page of the base seewav module

Also, you may call this a indirect **free** python interpretation of [Brainrot.js](https://www.brainrotjs.com/) (Also an inspiration)


![Usage](https://github.com/M3rcuryLake/Cassette/blob/main/assets/usage.gif)

Tested Only on Linux (Ubuntu 22.04, Fedora 40)



## Before Execution

Before running Cassette, follow these steps:

1. **Sign Up at AssemblyAI and UnrealSpeech**: Visit [AssemblyAI](https://www.assemblyai.com/) and [UnrealSpeech](https://unrealspeech.com/) to create accounts.


2. Replace the variables `AssemblyAI_API` and `UnrealSpeech_API` in `api_keys.json` with your respective API keys.


3. **Clone the Repo**: Clone The repo with `git clone https://github.com/M3rcuryLake/Cassete.git` 


4. **Install Prerequsites**: Ensure that Python and pip are installed on your system. Install additional dependencies and the Fonts by running:

    ```bash
    sudo apt-get install -y python3-dev libasound2-dev ffmpeg
    pip install -r requirements.txt
    mkdir ~/.local/share/fonts 
    cp fonts/* ~/.local/share/fonts/ && fc-cache -f -v

    ```


    if you are using windows, make sure python-pip and winget is already installed and set to path, then open any terminal (git-bash, powershell or cmd) and type in the following commands :

    ```bash
    winget install ffmpeg
    pip install -r requirements.txt
    ```


    Then install the fonts in the /Fonts/ directory manually. 


Once these steps are completed, you can execute Cassette with `python3 main.py` or `python main.py` to generate your customized 30-second explanatory videos. Enjoy creating engaging content with Cassette!



## Customisation Options

1. **Background Music Options**: Cassette allows you to add background music to your videos.

2. **Choose a Voice**: Select a voice for the voiceover generation.

3. **Choose a Background Gameplay**: Decide on the background gameplay for your video.

4. **Choose a Character Image**: Lastly, choose a character image for your video.

5. **Subtitle styles** : It allows customised timestamps (word or sentance)

6. **Choose Custom Fonts** : Select from multiple fonts and colours for your subtiltes.

7. **Choose your own Background Colours** : Allows you to choose from multiple options for background colours


## Common problems/errors :
- dependencies are not resolved
- unrealspeech free tier API limit exeeded (250000 chars / 6 hrs cap on API) 
- unrealspeech not responding to API Calls (common)
- g4f not responding to API calls (common)
- Correct options not chosen
- Fonts not installed
