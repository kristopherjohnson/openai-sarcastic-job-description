# Using OpenAI to Generate a Sarcastic Job Description

`openai.ipynb` is a Jupyter notebook with a simple example of using the OpenAI
API to generate some text from a prompt.


## Requirements

You will need the Jupyter tools to run the notebook. See
<https://jupyter.org/install> for installation details.

You will also need to install the `openai` and `python-dotenv` modules, which
you can do with this command:

    pip3 install -r requirements.txt

Finally, you need an OpenAI account and an API key.  Go to
<https://openai.com/api/> to create an account.  After creating an account or
logging into an existing account, click the user menu in the upper-right corner
and choose the _View API keys_ item, then click _Create new secret key_ to
create your API key.  Copy the created key and save it somewhere.


## API Key Configuration

The notebook looks at a file named `.env` to read the value of the
`OPENAI_API_KEY` environment variable.  Create a copy of `.env.example` named
`.env`, then add your API key to that file.  It should look something like this:

    OPENAI_API_KEY=ab-cdefghijklmnopqrstuvwxyz
