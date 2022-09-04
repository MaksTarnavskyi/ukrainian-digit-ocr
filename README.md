### Detect ukrainian words

1. Install tessaract and upload ukrainian module

```bash
    brew install tesseract

    wget https://github.com/tesseract-ocr/tessdata/raw/main/ukr.traineddata
    sudo mv -v ukr.traineddata /usr/local/share/tessdata/

    pip install -r requirements.txt
```

2. Open `ukrainian_ocr.ipynb` 
