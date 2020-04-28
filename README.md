# Chatbot-Development-using-RASA-Framework-and-Zomato-API---PGD-IIITB-Assignment

Developed by:
1. [Deepa Kushwaha](https://github.com/deepakush)
2. [Prateek Ralhan](https://github.com/prateekralhan)

## Usage:
1. You need to navigate to the directory where you have all the components of this entire folder
listed together and then activate your virtual environment.

2. You can install the dependencies using : **pip install -r requirements.txt**

3. Run the command - **rasa run actions** to initialise your actions server in one terminal.

4. Run the command - **rasa shell** in another terminal to test the functionality of rasa core model of the bot.

5. In case you wish to train your NLU and core models together from scratch, run the command:
**rasa train -vv -dump-stories --force** to train both the models together which can be tested further.

6. For testing the NLU, run **rasa shell nlu**,whereas for testing the core, run the command **rasa shell**.

7. Check out the [command line demo](https://www.youtube.com/watch?v=xigRtLG6U8k&t=26s).

8. You can also integrate your bot with other environments/workspaces. I have integrated it with Slack. Check out the [Slack Integration based demo](https://www.youtube.com/watch?v=b5_2RveqxDA&t=38s) and provide your feedback.


