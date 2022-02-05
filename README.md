## Vision Transformers для Сегментации

[How it works on DemoPanel](https://demo.neural-university.ru/interior-nodepth.html)

run.py


'''Принимает директорию с изображениями, отдаёт карты сегментации в указанную директорию
Вход:
	-i строка с адресом дирекории с изображениями (jpeg)
Выход:
	-o строка с адресом директории с картами сигментации (png)
Веса:
	-m строка с адресом директории с файлом весов модели

(run.py -i pics4segm -o output_hibrid -m weights/dpt_hybrid-ade20k-53898607.pt)
  
	
1) Download the model weights and place them in the `weights` folder:


[Weights link](tps://cloud.degoo.com/share/4nlK0XRlD7TsXJagixXe1A)

2) Set up dependencies:

Есть зависимости

    ```shell
    pip install -r requirements.txt
    ```

Код тестировался с Python 3.7, PyTorch 1.8.0, OpenCV 4.5.1, и timm 0.4.5
### Acknowledgements
This modul was build based on [this repo](https://github.com/isl-org/DPT)


My work builds on and uses code from [timm](https://github.com/rwightman/pytorch-image-models) and [PyTorch-Encoding](https://github.com/zhanghang1989/PyTorch-Encoding). We'd like to thank the authors for making these libraries available.
### License

MIT License 
