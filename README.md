## Vision Transformers для Сегментации

run.py
'''Принимает директорию с изображениями, отдаёт карты сегментации в указанную директорию
Вход:
	-i строка с адресом дирекории с изображениями (jpeg)
Выход:
	-o строка с адресом директории с картами сигментации (png)
Веса:
	-m строка с адресом директории с файлом весов модели

(run.py -i pics4segm -o output_hibrid -m weights/dpt_hybrid-ade20k-53898607.pt)
  
Есть зависимости

    ```shell
    pip install -r requirements.txt
    ```

Код тестировался с Python 3.7, PyTorch 1.8.0, OpenCV 4.5.1, и timm 0.4.5

### License 

MIT License 
