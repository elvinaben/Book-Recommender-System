Streamlit link : https://book-recommender-system-dpbhh9puiwfnx9j5jsgz3q.streamlit.app/

Pakai env python 3.11 (FastAPI) 


==== CARA RUN YG GA ERROR 
1. Activate venv 
    source env/bin/activate
    (Nanti prompt menjadi : (env) elvinabenedicta@Elvinas-MacBook-Air-2 Book Recommender System %)
2. Run streamlit on local
    python -m streamlit run streamlit_app.py

Jika perlu sblm step 2: 
    pip install -r requirements.txt


--- Video part 9
Create venv (virtual env)
    conda create --prefix ./env python==3.7 -y
    conda activate ./env/


Ini env bikinnya bisa pake (Cara bikin & activate env, beda kyk vid) -- opsi klo yg di atas error (DI PROJECT INI PAKE INI)
python3 -m venv env
source env/bin/activate



Activate (ada 2 opsi)
1. conda activate ./env/
2. conda activate "/Users/elvinabenedicta/Desktop/Holiday/Book Recommender System/env"

Deactivate
    conda deactivate


--- Video part 10
Making Set-up (di terminal)
    touch setup.py          # touch buat bikin file
    touch README.md
    touch requirements.txt  
    mkdir src
    touch src/__init__.py

Set-up Packages
    pip install -r requirements.txt

--- Video part 11
Cara akses Streamlit
    streamlit run app.py


# Book-Recommender-System
# Book-Recommender-System
# Book-Recommender-System
