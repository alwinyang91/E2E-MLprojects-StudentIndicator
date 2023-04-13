## 1. Copy the E2E-MLprojects-Setup repositry

Include:

```python
src/
requirements.txt
setpu.py
```



## 2. Create an environment 

Step 1:

```python
python -m venv yourEnvNmae
# or 
virtualenv venvE2E2 -p python3.9
```

Step 2:

```python
source venvE2E2/bin/activate
```

Step 3: check your python version if you want to

```python
python --version
```



## 4. Change project name in setup.py

```python
setup(
    name="E2E_MLprojects-StudentIndicator",
```



## 5. Run `requirements.txt`

```python
pip install -r requirements.txt
```

## 6. EDA and First Training in the Notebook

- EDA
- Model Training

## 7. Complete the src/components

- Data Ingestion
- Data transformation
- Model Training and Evaluation

## 8. Complete the src/pipline

Step1: Flask App
```python
touch app.py
mkdir templates
touch templates/index.html
touch templates/home.html
```

Step2: Complete `pipeline/predict_pipeline.py`
