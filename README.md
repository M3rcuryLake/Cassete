# Cassette

Cassette is a Python program designed to create 30-second explanatory videos suitable for Instagram Reels or YouTube Shorts. It offers multiple customization options for creating personalized videos. The program utilizes various APIs and libraries, including GPT-3.5-turbo model for transcript generation, AssemblyAI API for subtitle generation, UnrealSpeech API for voiceover generation, and ffmpeg along with moviepy for video editing.
The 'seewav' module in the given codebase is a modified version of a [pull request](https://github.com/adefossez/seewav/pull/7) by @Phoenix616 at the github page of the base seewav module

Also, you may call this a indirect **free** python interpretation of [Brainrot.js](https://www.brainrotjs.com/) (Also an inspiration)

Example : [Generated By Cassatte ~>]()


## Before Execution

Before running Cassette, follow these steps:

1. **Sign Up at AssemblyAI and UnrealSpeech**: Visit [AssemblyAI](https://www.assemblyai.com/) and [UnrealSpeech](https://unrealspeech.com/) to create accounts. Replace the variables `assembly_ai_api` and `urs_api` in the code with your respective API keys.

2. **Clone the Repo**: Clone The repo with `git clone https://github.com/M3rcuryLake/Cassete.git` 

3. **Quick Setup**: Ensure that Python and pip are installed on your system. Then open a terminal in the directory where 'main.py' is located and run `python3 setup.py` then `python3 main.py`
    if you are on windows, just use `python` instead of `python3`
   
    Or ensure that Python and pip are installed on your system. Install additional dependencies by running:
    ```bash
    sudo apt-get install -y python3-dev libasound2-dev ffmpeg
    pip install -r requirements.txt
    ```

5. **Install Font**: The program uses the "Permanent Marker" font located in the `./assets/` directory. Make sure to install it on your system before proceeding.



## Customisation Options

1. **Background Music Options**: Cassette allows you to add background music to your videos. Choose one of the following options:
    - Minecraft
    - Subwoofer Lullaby 
    - Moog City 2

2. **Choose a Voice**: Select a voice for the voiceover generation:
    - Dan: Young Male 
    - Will: Mature Male 
    - Scarlett: Young Female 
    - Liv: Young Female 
    - Amy: Mature Female 

3. **Choose a Background Game**: Decide on the background game for your video:
    - Minecraft 
    - GTAV 
    - Forza Horizon 5 

4. **Choose a Character Image**: Lastly, choose a character image for your video:
    - Denn 
    - Jed 
    - Jess 
    - K-11 
    - Kee 
    - Kell
    - Ron 

Once these steps are completed, you can execute Cassette to generate your customized 30-second explanatory videos. Enjoy creating engaging content with Cassette!


## Common problems/errors :
- dependencies are not resolved
- unrealspeech free tier API limit exeeded (250000 chars / 6 hrs cap on API) 
- g4f not responding to API calls (common)
- Correct options not chosen
- Fonts not installed