FROM jupyter/base-notebook

# Install additional dependencies
RUN pip install pandas numpy matplotlib seaborn scikit-learn

# Copy the Jupyter Notebook into the container
COPY Data analysis.ipynb /home/jovyan/work/

# Set the default command to launch Jupyter Notebook
CMD ["jupyter", "notebook", "--ip='0.0.0.0'", "--port=8888", "--no-browser", "--allow-root"]
