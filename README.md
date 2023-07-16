# The TF2 Auto-Generator
Using ChatGPT and some python code, I've created this TF2 auto-generator which can currently generate a new TF2 weapon card. It's a bit harder to setup than most, but I can assure you it'll be worth it. Scroll down to the setup section for setup instructions.

# Examples
If you don't believe how good this is, here are some examples of the weapon generation (these aren't cherry-picked, I just used the first 5 weapon cards it generated):

<img src="https://github.com/FatalError418/TF2-Auto-Generation/assets/139549531/1942f080-9f01-4e0b-9c23-8dbe5b27d012" width="400"/>

<img src="https://github.com/FatalError418/TF2-Auto-Generation/assets/139549531/34ae155f-c418-4def-8aef-9fdccdfc13e4" width="400"/>

<img src="https://github.com/FatalError418/TF2-Auto-Generation/assets/139549531/9c5be52d-6f5d-41d3-bf85-d8fc71f799f1" width="400"/>

<img src="https://github.com/FatalError418/TF2-Auto-Generation/assets/139549531/65e7a6b6-90db-4cab-b7e9-91c80186ac7e" width="400"/>

<img src="https://github.com/FatalError418/TF2-Auto-Generation/assets/139549531/51572c94-e077-47aa-80bc-a2822cc69dfa" width="400"/>

# How to get an OpenAI API Key
1. First of all, go to the top of this page. You should see 'Code' somewhere there. Click on it, and tap download ZIP. Once it's downloaded, unzip it and we can move onto step 2.
2. We now need to get the OpenAI API key (OpenAI owns ChatGPT). Do do that, log in [here](https://platform.openai.com) and skip to step 4 if you already have an OpenAI account (or ChatGPT account), and otherwise continue to step 3.
3. To create an account, head over to [OpenAI](https://platform.openai.com). You should see a sign in popup. Click on 'Sign Up', and put your details in. You'll need a phone number to verify you are human, so put that in or try to find a working temp phone number, which I have yet to find one that has not been used more than 2 times. Once you sign up, head on to step 4.
4. Now you need to click on the icon in the top right corner, which has text beside it which says 'Personal' or something like that (may be slightly different, it's your organization name). Click on 'View API Keys'. Also, note that this is safe to use the keys in the weapon generator as it's completely on your machine and I don't connect with it in any way (if you don't believe me, look at the code). Now, click 'Create new secret key'. Name it something like 'TF2-Weapon-Generator' and press 'Create secret key again'. Copy the api key by clicking the little copy icon, and close the window. Also, if you run into issues using this down the line, this may be because your free credits expired ($5 for the first few months of the account), if that's so you can feed it some money in exchange for more credits.
5. Now, to actually use the generator. First, go into the extracted folder and edit the 'weapongenerator.py' file with notepad or a code editor. Press 'control + f' and type 'openai.api_key ='. Inside the quotes to the right of it, paste your api key into it, so the final line of code should look like this: openai.api_key = "Paste your API key here"
6. If you have python installed, skip this step. You need to download python. Go to the python [website](https://www.python.org/downloads/) and install the latest version using the install wizard. You have now installed python.
7. Now, press the windows key or OS equivalent and type 'cmd', click the first option and type 'cd location\of\the\extracted\folder'. That would be the folder which houses the weapongenerator.py script. If that fails, make sure to first type 'C:' or whatever drive you downloaded the folder onto. Also, note the '\' should be '/' on a Unix OS (aka on Mac or Linux).
8. Next, type 'venv\Scripts\activate' (or 'venv/Scripts/activate' on a Unix OS, aka on Mac or Linux). You should see a little '(venv)' appear.
9. Finally, you can actually run the script. Type 'py weapongenerator.py'. Wait a moment until you see 'Weapon generated successfully.' appear. If you don't see it or get some errors, try running the command again. Now, go to [this website](https://gamepro5.com/programs/tf2_weapon_card_creator/), scroll down and press 'Load', then find the weapon generator folder. Select 'weapon.weaponcard', and press 'Open'. You are now done, and you should see a weapon card appear! If you see a disguised hat instead of an icon, it's because it couldn't find it for some reason, so just ignore it. If it didn't load the weapon card, repeat this step and hope for the best, this generator can be a bit unpredictable.
10. If you want to learn how to use this in the best way possible, take a look below at the usage section. Hope this setup was worth it!
