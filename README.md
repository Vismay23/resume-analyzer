## Setup & Installation 👀

To run this project, perform the following tasks 

Download the code file manually or via git
```bash
git clone https://github.com/Vismay23/resume-analyzer.git
```

Create a virtual environment and activate it **(recommended)**

Open your command prompt and change your project directory to ```AI-Resume-Analyzer``` and run the following command 
```bash
python -m venv venvapp

cd venvapp/Scripts

activate

```

Downloading packages from ```requirements.txt``` inside ``App`` folder
```bash
cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

After installation is finished create a Database ```cv```

And change user credentials inside ```main.py```
https://github.com/Vismay23/resume-analyzer/blob/main/App/main.py#L95

Go to ```venvapp\Lib\site-packages\pyresparser``` folder

And replace the ```resume_parser.py``` with ```resume_parser.py``` 

which was provided by me inside ```pyresparser``` folder

``Congratulations your set-up and installation is finished ``

I hope that your ``venvapp`` is activated and working directory is inside ``App``

Run the ```main.py``` file using
```bash
streamlit run main.py

```
