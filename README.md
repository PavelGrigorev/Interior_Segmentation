## Vision Transformers ��� �����������

run.py
'''��������� ���������� � �������������, ����� ����� ����������� � ��������� ����������
����:
	-i ������ � ������� ��������� � ������������� (jpeg)
�����:
	-o ������ � ������� ���������� � ������� ����������� (png)
����:
	-m ������ � ������� ���������� � ������ ����� ������

(run.py -i pics4segm -o output_hibrid -m weights/dpt_hybrid-ade20k-53898607.pt)
  
���� �����������

    ```shell
    pip install -r requirements.txt
    ```
[Weights link](tps://cloud.degoo.com/share/4nlK0XRlD7TsXJagixXe1A)

��� ������������ � Python 3.7, PyTorch 1.8.0, OpenCV 4.5.1, � timm 0.4.5
### Acknowledgements
This modul was build based on [this repo](https://github.com/isl-org/DPT)


My work builds on and uses code from [timm](https://github.com/rwightman/pytorch-image-models) and [PyTorch-Encoding](https://github.com/zhanghang1989/PyTorch-Encoding). We'd like to thank the authors for making these libraries available.
### License

MIT License 
