# yologui

1. 새폴더 만들고 CMD 에서 (또는 vscode 터미널에서) 소스코드를 복사
```
git clone 해당 레포 주소
```
2. 새로운 개발환경 만들고
```
conda create -n yologui2 python=3.9
```
3. 콘다 Activate 또는 vscode 에서 개발환경 연결해주고
```
conda activate yologui2
```
4. 개발환경 Package 설치 하고
```
pip install -r requirements.txt
```
5. yolov5를 클로닝해 오고(REPO에서는 보이지 않지만)
```
git clone https://github.com/ultralytics/yolov5.git
```
6. cmd 에서
```
code .
```
7. 다음과 같은 Tree 구조가 만들어지면 오케이
## 폴더구조는
![캡처](https://github.com/jysung1122/aiModel/assets/56614779/acb2af41-d7d9-4dde-99a3-616bf8a6ee7f)

8. shift+ctrl+p Select python interpreter에서 가상환경과 연결해주고 새 터미널 열기

9. 실행은 windowAPP.py
## 프로그램 실행 결과는
![캡처](https://github.com/jysung1122/aiModel/assets/56614779/5b564b3b-8782-468e-985a-b185f6611d10)
