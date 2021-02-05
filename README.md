# HAN-DA
[SW중심대학 공동해커톤] 


## Motion-Estimate

```mediapipe```라이브러리 사용한 모션 인식


### requirements
```python
pip install python==3.7.4
pip install mediapipe==0.8.2
pip install opencv-python==4.5.0
```
### 실행하기
```
python main.py
```
## 🧘작업하기🧘
### 추가 기능
- 앉은 자세 판별
- 앉은 상태에서 정자세 판별 및 각도 추출
- 거북목 진단
- Timer 추가 (앉은 시간 판별 후 📢 ALERT)

## 🤸운동하기🤸

### 추가 기능
- **[운동 횟수] COUNT**
- **[운동 자세 교정] VOICE**

#### SQUAT
- 무릎 각도와 엉덩이 각도를 내적을 통하여 연산
- 무릎 사이와 어깨사이의 길이 연산

#### PUSH UP
- 팔꿈치 각도를 이용하여 연산

#### SIDE LEGRAISES
- 다리 각도 연산
