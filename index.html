import streamlit as st
import pandas as pd
import numpy as np

# Cargar el DataFrame
df = pd.read_csv('/path/to/your/df_filtered_clean.csv')  # Cambia la ruta al archivo real

# Título de la aplicación
st.title("Búsqueda de Propiedades Disponibles")

# Sidebar para los filtros
st.sidebar.header("Filtros")

# Filtro de precio
min_price, max_price = st.sidebar.slider("Rango de Precio", float(df['price'].min()), float(df['price'].max()), (float(df['price'].min()), float(df['price'].max())))

# Filtro de número de habitaciones
min_bedrooms, max_bedrooms = st.sidebar.slider("Número de Habitaciones", int(df['numberofbedrooms'].min()), int(df['numberofbedrooms'].max()), (int(df['numberofbedrooms'].min()), int(df['numberofbedrooms'].max())))

# Filtro de área total
min_area, max_area = st.sidebar.slider("Área Total (m²)", float(df['totalarea'].min()), float(df['totalarea'].max()), (float(df['totalarea'].min()), float(df['totalarea'].max())))

# Filtro de distrito
districts = st.sidebar.multiselect("Distrito", df['district'].unique(), df['district'].unique())

# Aplicar los filtros al DataFrame
filtered_df = df[
    (df['price'] >= min_price) & 
    (df['price'] <= max_price) & 
    (df['numberofbedrooms'] >= min_bedrooms) & 
    (df['numberofbedrooms'] <= max_bedrooms) & 
    (df['totalarea'] >= min_area) & 
    (df['totalarea'] <= max_area) & 
    (df['district'].isin(districts))
]

# Mostrar el DataFrame filtrado
st.write("### Propiedades Disponibles")
st.write(f"Mostrando {len(filtered_df)} propiedades")
st.dataframe(filtered_df)
