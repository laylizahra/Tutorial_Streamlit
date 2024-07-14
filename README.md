# Tutorial_Streamlit
import pandas as pd
import seaborn as sns
import numpy as np 
import matplotlib.pyplot as plt
import streamlit as st

st.set_page_config(page_title='Webiste sederhana')
st.write(""" Hello World! """)

st.markdown(""" Tulisan Markdown """)
st.title("judul")
st.header("Header")
st.subheader("Subheader")
st.text("Text")
st.caption("Caption")
st.code("import streamlit as st")

st.code(""" 
        # Import library streamlit
        import streamlit as st
           """)

st.latex("y = 2x^2 + 3x + 5")
