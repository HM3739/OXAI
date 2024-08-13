To set up this project follow the steps listed here: https://aijson.com/docs ( if running on Windows the second command it .\venv\Scripts\activate.bat ).

If you get a Windows error 126 see this SO thread: https://stackoverflow.com/questions/78114412/import-torch-how-to-fix-oserror-winerror-126-error-loading-fbgemm-dll-or-depen
(Yes you have to download the sketchy DLL)

Any pytorch installation issues, see this page: https://pytorch.org/get-started/locally/

You will need to set up a .env file which should contain the secrets you use to connect to an LLM - see this page: https://aijson.com/docs/guides/using_any_language_model

Improvements: 
Create a folder to put all your manuals in and make sure to name them appropriately for ease of search. 
Make sure the LLM searches through them to find the manual that matches your device.
Build a front end so that the user has a ChatGPT style interaction.

How to run:
In the filepath field put: "LTV-Manual.pdf"
In the message field put in the relevant query - e.g. "how to turn on an LTV mechanical ventilator" in any language
