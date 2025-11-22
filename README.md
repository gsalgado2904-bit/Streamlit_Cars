# 🚗 Visualización Dinámica de Inventario de Vehículos con Streamlit

## 🎯 Breve Descripción del Propósito

Este proyecto presenta una **aplicación interactiva** desarrollada con **Streamlit**, diseñada para facilitar la **toma de decisiones estratégicas** sobre la gestión y el precio del inventario de vehículos. La plataforma permite a los usuarios explorar la distribución, el estado y la valoración de los vehículos a través de tres gráficos dinámicos y seleccionables.

**Enlace a la Aplicación:** [https://proyecto-7-gso.onrender.com](https://proyecto-7-gso.onrender.com)

---

## 📈 Análisis de los Gráficos (Valor para el Negocio)

La aplicación ofrece al usuario la flexibilidad de generar los gráficos de forma simultánea o individual, según sus necesidades de análisis:

### 1. Distribución de Tipo de Vehículo por Marca (Vehicle Type and Brand)

* **Propósito:** Ofrece una **base de inventario sólido** al visualizar cómo se distribuyen la **cantidad** y los **tipos de vehículos** a lo largo de las diferentes marcas disponibles para la venta.
* **Valor Agregado:** Permite a los gestores identificar rápidamente las marcas con mayor *stock* y la diversidad de tipos de carrocería ofrecidos, informando sobre la **concentración del portafolio**.

### 2. Condición del Vehículo vs. Año (Vehicle Model vs. Condition)

* **Propósito:** Evalúa la **condición** física y el estado de conservación de los vehículos en relación con su **antigüedad**.
* **Valor Agregado:** Sirve como una **referencia de calidad y durabilidad**, permitiendo inferir el **diferente trato o mantenimiento** que ha recibido el vehículo a lo largo de su tiempo de uso.

### 3. Precio vs. Kilometraje (Vehicle Price vs. Mileage)

* **Propósito:** Muestra la relación directa entre el **precio de venta** y el **kilometraje** real del vehículo, reflejando el **uso verdadero** que se le ha dado.
* **Valor Agregado:** Es fundamental para **detectar anomalías o *outliers*** (como vehículos con precios simbólicos), que requieren una inspección manual para validar la tasación de mercado.

---

## 🛠️ Tecnologías Usadas

* **Frontend y Visualización:** **Streamlit** (Python) para la creación de la interfaz de usuario interactiva y la generación de *dashboards*.
* **Análisis y Gráficos:** **Plotly** (o la librería de Python que hayas usado) para generar los gráficos dinámicos y personalizables.
* **Lenguaje:** Python.
