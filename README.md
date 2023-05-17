# Sem8_Grid_Stability
Steps to run our web app on colab 
0. First clone the repo using ! git clone https://github.com/cremento/Sem8_Grid_Stability.git
1. ! pip3 install -r /content/grid_stability_app/requirements.txt
2. ! pip install -q streamlit
3. ! npm install localtunnel
4. ! pip3 install streamlit (any one of 2 or 4)
5. ! streamlit run /content/Sem8_Grid_Stability/grid_stability.py & npx localtunnel --port 8501

You may need to reinstall numpy 
1. ! pip3 uninstall numpy
2. ! pip3 install -U numpy
