# 모바일, 무선 통신의 구조를 알아보자


## 64. 모바일 네트워크

### 모바일 네트워크는 휴대 전화나 이동 통신 등에 이용되는 광역 무선 네트워크를 의미한다.
#### 휴대 전화나 스마트폰 등에서 이용하는 모바일 네트워크는 휴대 단말기, 기지국, 교환국 등 세 가지 노드로 구성된다.
#### 휴대 단말기와 기지국은 무서능로 연결되어 음성이나 데이터를 주고 받고 기지국과 교환국 사이는 일반적으로 전용 회선(유선)으로 연결된다.
#### 모바일 네트워크에서는 휴대 단말기가 어떤 기지국과 통신할 수 있는지 조사해야 하고, 교환국은 이 정보를 이용하여 연결을 설정한다.
#### 단말기는 이동하기 때문에 기지국을 적절히 전환할 필요가 있는데 이 기술을 핸드 오버라고 한다.
### 휴대 단말기의 모든 통신은 디지털화 되어있다.(초기 자동차 전화등 1세대 이동통신시스템의 모바일 네트워크 제외)
#### 통신 방식
> 1. FDMA(주파수 분할 다중 접속): 반송파를 특정 주파수 대역의 채널마다 분할하여 신호를 송신하는 방식.
> 2. TDMA(시간 분할 다중 접속): 시간별로 채널을 분할하여 다수의 패킷을 전송하는 방식. 상하 방향으로 같은 주파수 대역을 사용하는 방식을 TDMA/TDD, 다른 주파수 대역을 구분하여 사용하는
                            방식을 TDMA/FDD라고 한다.
> 4. CDMA(코드 분할 다중 접속): 동일한 주파수 대역에서 다수의 신호를 전송하는 방식이다. 스펙트럼 확산으로 노이즈나 간섭 등을 받기 어렵다는 특징이 있다.       

     
## 65. 4G/5G

### 4G와 5G는 스마트폰 등 통신 규격을 의미한다. G는 Generation의 머리글자로, 통신 방식이나 기술 차이를 나타낸다.
> - 1세대 이동통신시스템(1G): FDMA를 이용한 아날로그 통신 방식의 모바일 네트워크. 자동차 전화 등이 여기에 속한다.
> - 2세대 이동통신시스템(2G): 해외에서는 GSM, 일본에서는 PDC(TDMA/FDD)를 이용한 모바일 네트워크. 2G 부터 패킷 교환방식을 사용한다.
> - 3세대 이동통신시스템(3G): 주파수나 전송 속도 등을 개선한 모바일 네트워크. TDMA에 더해서 CDMA도 이용되었다. 3G를 진화시킨 HSPA나 LTE도 있다.
> - 4세대 이동통신시스템(4G): 주파수나 변조 방식 등을 개선하여 더울 빠르고 대용량화된 모바일 네트워크
> - 5세대 이동통신시스템(5G): 10Gbps의 전송 속도, 1밀리초 이내의 통신지연, 100만 대의 동시 다수 접속을 실현한 모바일 네트워크

#### 4G와 5G는 통신 방식이나 기술 등이 발달하면서 각 세대의 모바일 네트워크 성능을 판단하는 지표로도 사용된다.
#### 5G는 휴대 단말기를 이용한 4K/8K 콘텐츠 시청, 로봇 연격 조작, IoT 기기나 센서  네트워크 등에 응용하는 것을 전제로 고속, 대용량, 저지연,     동시 다수 접속을 실현하는 모바일 네트워크로 전개되고 있다.




## 66. 로컬 5G

### 5G에는 일반 모바일 네트워크 이외에 IoT기기나 로봇 제어 등에 응용 가능한 사업자를 위한 '로컬 5G'가 있다.
#### 5G는 높은 주파수 대역을 사용하여 고속 및 대용량 전송을 실현하지만 높은 주파수 전파는 장애물에 약하고 송수신에 높은 전력이 필요하므로 기지국(안테나)을 4G보다 세밀하게 설치해야 한다.
#### 5G의 저지연 특성은 실시간 로봇 제어, 자율 주행, 공장 내 기계 제어 등에도 효과적이다. 이런 용도로는 5G 안테나를 공장 안에 설치하는 것으로 충분하다.
#### 로컬 5G는 사업자별로 모바일 네트워크를 구축할 수 있어 보안을 강화할 수 있다는 장점도 있다.


## 67. 이동 통신

### 이동 통신은 이동하면서 스마트폰이나 노트북 등을 사용할 때 필요한 통신 서비스를 의미하기도 하지만, 휴대 단말기 자체를 의미하기도 한다.
#### 넓은 의미에서 이동 통신이란 단말기나 기지국 중 어나 하나 또는 양쪽이 이동할 수 있는 통신 기술을 의미한다.   좁은 의미에서는 휴대 단말기를 사용하는 통신 서비스를 가리키며, BWA등이 있다.
#### BWA에는 5G와 로컬 5G처럼 통신 사업자를 대상으로 하는 광역 서비스와 특정 구역에 한정되는 서비스 등 이렇게 두가지가 있다.
#### 전자는 모바일 WiMAX라고 한다.
#### 후자는 지역 WiMAX라고 하며 공공 서비스의 향상이나 전파가 도달하기 어려운 지역의 대체 네트워크로서 통신 서비스를 제공하고 있다.
#### BWA는 모두 2.5GHz 대역폭을 이용하며, 통신 방식은 LTE나 OFDMA의 확장 기술을 사용한다. 또 핸드오버 기능도 필요하다.
#### 모바일 WiMAX는 현재 주로 스마트폰이나 노트북용 모바일 Wi-Fi 라우터로 이용되고 있다. 터널이나 지하, 건물 내부 등에서는 전파가 어렵다는 단점이 있지만    연결만 되면 안정적인 통신 속도와 품질을 기대할 수 있다.


## 68. Wi-Fi

### Wi-Fi는 IEEE 802.11 시리즈의 규격에 따라 무선으로 네트워크에 연결하는 기술이다.
#### Wi-Fi 규격은 이용하는 주파수의 대역이나 통신 속도 등에 따라 'a','b'같은 접미사를 붙여서 구분한다.
#### Wi-Fi 장치는 통신에 전파를 사용한다. 무선 연결에서는 일반적으로 주파수가 높아질수록 많은 양의 데이터를 전송할 수 있지만 전파 도달 거리가 짧아지고 수분이나 차폐물등 영향을 쉽게 받는다.
#### 또 주파수가 높아지면 소비 전력이나 발열량도 커진다.
#### 높은 주파수 대역에서는 다중화 효율이 좋아진다. IEEE 802.11n이나 ac 등 규격에서는 여러 개의 안테나를 채널별로 할당할 수 있다.
#### MIMO라는 기술은 안테나를 묶어 고대역 채널을 만들어 전송 속도를 높인다. 
#### 또, 2차원으로 배치된 안테나별로 출력과 위상을 조정하면 특정 방향의 전파 강도를 변경할 수 있다. 이 기술을 빔 포밍이라고 한다.


## 69. 공중 무선 LAN
### 공공시설이나 점포에서 이용할 수 있는 무선 LAN
#### 공중 무선 LAN은 공항 등 공공시설이나 호텔, 쇼핑몰, 카페 등에 설치된 액세스 포인트다.
#### 이용자 편의를 위해 무료로 인터넷에 접속할 수 있는 경우가 많지만, 유료 서비스도 있다.
#### 무료로 제공하는 액세스 포인트라도 무단으로 사용할 수 없도록 이용할 때 계정을 등록해야 하는 경우도 있다.
#### 현재 공중 무선 LAN은 스마트폰에 의한 인터넷 트래픽을 분산하는데 이용하는 경우가 많아졌다.
#### 무선 LAN의 보안은 안전하지 않다. 공중 무선 LAN을 이용할 때는 관리자가 명확하지 않은 액세스 포인트에는 연결하지 않는 편이 좋고,    정상적인 액세스 포인트라도 공격자 때문에 오염되어 있을 가능성을 고려해야 한다.


## 70. LPWA
### LPWA는 저소비 전력과 장거리 통신을 특징으로 하는 무선 통신 기술이다.
#### 소비 전력을 억제하는 것은 노트북이나 스마트폰 등 이외의 IoT기기나 임베디드 기기 등 무선 접속이나 인터넷 접속을 용이하게 하기 위해서이다.
#### 통신 범위도 수 km에서 수십 km 정도를 상정한 규격이 존재한다.
#### LPWA는 실외에서 넓은 지역으로 전파를 발생시키기 때문에 면허가 필요한 것과 그렇지 않은 것이 있다. 이 차이는 주파수 대역과 출력으로 겨렂ㅇ된다.
#### 면허가 필요한 것을 라이선스 밴드라고 하고 반대를 언라이선스 밴드라고 한다.
#### 라이선스 밴드의 통신 거리는 모바일 네트워크의 사업자의 기지국 범위 내로 제한된다. 언라이선스 밴드는 수 km에서 수십 km까지 규격에 따라 차이가 있다.
#### LPWA 응용 사례로는 무선으로 가스나 수도 계량기를 검침하기, 원격 감시 및 조작을 수행하는 스마트 미터, 공원이나 농장의 감시 등이 있다.


## 71. 블루투스/NFC
### 블루투스와 NFC는 각각 별개의 규격이지만, 근거리 무선 통신을 이용하여 단말기를 연결하는 기술이라는 점은 공통적이다. 블루투스는 스마트폰과 주변 기기 간 연결에 사용되며, NFC는 비접촉식 IC 카드 통신에 주로 사용된다.
#### 블루투스는 Wi-Fi와 같은 2.4GHz의 무선 주파수 대역을 사용하는 무선 네트워크 기술이다.
#### NFC는 블루투스와 마찬가지로 근거리 통신 기술이다. 사용하는 전파는 13.56MHz이며, 블루투스에 비해서 대역폭이 낮다.
#### NFC는 더 가까운 거리에서 통신을 가정하고, 전원이 필요하지 않는 등 특징이 있다.
#### 블루투스는 페어링 작업으로 기기끼리 연결을 설정하여 여러 번 연결하는 것을 전제로 한 기술이지만, NFC는 임시 연결이나 통신에 적합하다.


## 72. 센서 네트워크
### 센서 네트워크란 IoT 기기 등을 비롯하여 다양한 센서를 연결해서 구성한 네트워크를 의미한다. 규격에는 IEEE 802.15.4가 있으며, 그 구현 예로 ZigBee가 있다.
#### 센서 네트워크란 온도계, 카메라, 압력 센서, 가속도 센서, 적외선 센서 등을 연결하여 구성한 네트워크다. 센서 자체는 측정 데이터 등을 네트워크로 내보내고, 이를 호스트 장치나 중앙 관리 호스트가 수집한다.
#### 네트워크 연결 형태는 스타형이 대부분이다. 그러나 IoT 기기를 연결하면 말단 노드가 인텔리전트하게 자율적으로 작동하는 센서 네트워크도 있습니다.
#### 블루투스처럼 2.4GHz 대역 주파수를 이용한다. 센서 데이터의 변조나 도청을 방지하고자 통신은 암호화 된다.
#### ZigBee는 인텔리전트 빌딩이나 공장 등 센서 네트워크에 활용되고 있으며, NASA의 화성 탐사차와 드론의 통신에도 사용되는 기술이다.
#### ZigBee 네트워크에는 네트워크 관리 기능을 가진 ZigBee 코디네이터를 포함해서 각 노드가 자율적으로 연결되는 메시형과 ZigBee 라우터를 중심으로 하는 스타형이 있으며, 용도에 따라 연결 형태를 선택할 수 있다. 각 노드는 소비전력을 줄이려고 신호가 없을 때는 슬립 모드로 대기하고, 신호가 있으면 몇 초 안에 복귀한다.
