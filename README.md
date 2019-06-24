# orsocr

hOpital Regional de Saint-louis Object Character Recognition (orsocr)

# Description

# Dependencies

    opencv
    pytesseract

# Usage

    git clone https://github.com/sapienscube/orsocr
    cd orsocr
    python orsocr/main.py

or

    from orsocr.recognizer import recognize

    filename = './orsocr/three.png' # some file name
    text_list = recognize(filename)
    print(text_list)
