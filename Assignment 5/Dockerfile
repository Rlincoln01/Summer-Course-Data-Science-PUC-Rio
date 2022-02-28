# Load existing image
FROM python:latest

# Install all packages used in the assignment
RUN pip install pandas
RUN pip install matplotlib
RUN pip install datetime

# Copy the necessary files from the folder into the image
COPY plots.py ./

# Run file
CMD ["python","-u","./plots.py"]