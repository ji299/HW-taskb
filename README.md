電腦硬體設置:
	作業系統:Ubuntu 22.04.5 LTS
	顯示卡:GeForce RTX 4070 super
	CUDA版本:12.4
	cuDNN:8.6
 訓練套件:pythorh

使用說明:訓練資料採用mini-ImageNet dataset，可至以下網站下載: https://cchsu.info/files/images.zip ，解壓縮後內部即有訓練資料切分的文字檔，將資料和文字檔與程式放在同資料夾中，即可執行

各個檔案說明:
resnet34.ipyb:使用原生的resnet34模型(不用預設權重)進行訓練
main.ipyb:選定的最終方案模型
test-A1.ipyb:對應報告中消融實驗的A1版本
test-A2.ipyb:對應報告中消融實驗的A2版本
test-A3.ipyb:對應報告中消融實驗的A3版本
test-A4.ipyb:對應報告中消融實驗的A4版本
