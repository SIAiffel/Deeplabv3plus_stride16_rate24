# Deeplabv3plus_stride16_rate24

* stride (16->8)  aspp rate 변화

![Screenshot from 2021-06-21 14-38-55](https://user-images.githubusercontent.com/76798025/122712222-88fed580-d29e-11eb-9313-b602d8708968.png)


## 데이터 구성
```txt
/data
	/SIA
		/multi
			/gtFine
				/train
				/val
			/leftImg8bit
				/train
				/val
```

gtFine : label<br>
leftImg8bit : image


## Requirements
```bash
pip install -r requirements.txt
```

## Visdom

```bash
visdom -port 28333
```
