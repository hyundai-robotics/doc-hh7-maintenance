# HH4L / HH7 / HH7E / HH8 보수설명서

{% hint style="warning" %}

본 제품 설명서에서 제공되는 정보는 현대로보틱스의 자산입니다.

현대로보틱스의 서면에 의한 동의 없이 전부 또는 일부를 무단 전재 및 재배포할 수 없으며,
제3자에게 제공되거나 다른 목적에 사용할 수 없습니다.

본 설명서는 사전 예고 없이 변경될 수 있습니다.



**Copyright ⓒ 2023 by Hyundai Robotics**

{% endhint %}
# 1. 안전
# 1.1. 서론

본 장의 주된 목적은 산업용 로봇의 사용자와 보수, 조작하는 작업자의 안전에 대한 사항을 기술하는 것입니다.

이 설명서는 UC 기계류 지침 98/37/EC(2006/42/EC)와 USA OSHA의 안전규정을 준수하며, 로봇 본체 및 제어기 부분의 안전에 관련된 사항을 기술합니다. 그리고 로봇 본체 및 제어기는 EN ISO 10218-1:2011 와 ANSI/NFPA 79:2021의 안전기준을 준수하여 제조합니다.

로봇 시스템의 설치, 교체, 조정, 조작, 보전, 보수를 행하는 모든 작업자들은 반드시 조작설명서, 보수설명서를 숙독하여 완전히 이해하여야 하며, 특히 안전과 관련된 가장 중요한 경고 표시인&nbsp;  ![](../_assets/작은주의표시.png)기호가 표시된 부분은 특별한 주의를 필요로 합니다.

로봇 시스템의 설치, 교체, 조정, 조작, 보전, 보수는 이러한 목적을 위해 교육된 작업자에 의해서 지시된 작업 순으로 행해져야 합니다.

당사에서는 이러한 작업을 위하여 보전, 보수, 조작 교육을 계획하여 시행하고 있으니, 로봇 사용자는 로봇 작업자에 대하여 해당 교육을 받을 수 있도록 하여 주십시오. 그리고 반드시 본 교육 과정을 이수한 작업자만이 로봇을 취급하는 작업을 할 수 있도록 하여 주십시오.

당사의 산업용 로봇의 사용자는 해당 국가에서 적용되는 로봇과 관계된 안전관련 법규를 확실히 파악하여 준수하여야 할 책임과 로봇 시스템에서 일하는 작업자를 보호하기 위한 안전장치를 제대로 설계, 설치, 운용할 책임이 있습니다.

로봇 시스템의 위험지역 즉 로봇, 툴(tool), 주변 장치들이 동작하는 지역에서는 ANSI/NFPA 79:2021에 의하여 작업자 또는 작업물 외의 물체가 위험지역으로 진입하는 것을 방지하기 위한 안전장치가 있어야 합니다. 위험을 불구하고 작업자나 물체가 위험지역으로 들어가야 할 때는 비상정지(emergency stop)장치에 의하여 로봇 시스템이 즉시 정지되도록 시스템을 구성하여야 합니다. 이러한 안전장치의 설치, 확인, 운용의 책임은 작업자에게 있습니다.

로봇의 응용분야 및 사용할 수 없는 환경은 아래와 같습니다.


![](../_assets/말머리이미지.png )  <font size = 3> **응용분야** </font><br>

평면 또는 벽면에 설치하여 사용하는 산업용 로봇에 적용합니다(축 추가 가능). 또한 점 구간 또는 연속구간에서 제어하는 작업을 하기에 알맞습니다.

주된 응용분야는 

*   스폿(Spot) 용접
*   아크(Arc) 용접
*   커팅(Cutting)
*   핸들링(Handling) 
*   조립(Assembly) 
*   실링(Sealing)등의 응용 
*   팔레타이징(Palletizing) 
*   그라인딩(Grinding) 

위에 언급한 주된 응용분야 이외의 목적으로 사용하기 위해선 로봇 용도 및 응용가능 여부를 고려하여야 하므로 반드시 당사로 연락바랍니다. 

![](../_assets/말머리이미지.png )  <font size = 3> **사용할 수 없는 환경** </font><br>
당사 로봇은 폭발성이 강한 환경, 기름이나 화학물질이 포함된 지역에서는 사용할 수 없습니다. (설치, 조작 금지) 

# 1.2. 관련 안전 규정

로봇은 산업용 로봇의 안전 규격인 ISO 10218-1:2011에 따라 설계되었으며, 또한 ANSI/NFPA 79:2021규정을 준수하였습니다.

# 1.3. 안전 교육

로봇을 티칭(teaching)하거나 점검하고자 하는 작업자는 로봇을 사용하기 전 로봇 사용 및 안전에 관련된 교육을 이수하여야 합니다. 안전 교육 프로그램은 다음과 같은 사항이 포함되어 있습니다.

* 안전장치의 목적과 기능 
* 로봇을 다루는 안전한 절차 
* 로봇 또는 로봇 시스템의 성능과 내재하는 위험 
* 특정한 로봇의 응용에 관계된 작업 
* 안전의 개념 등
# 1.4. 안전관련 명판
# 1.4.1. 안전기호

본 설명서에서는 작업 지시를 위해 다음의 안전기호를 사용합니다. 



<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-osmi{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-bav5{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:middle}
</style>
<table class="tg">
<caption>표 1-1 안전기호</caption>
<thead>
  <tr>
    <th class="tg-osmi" colspan="2">기호</th>
    <th class="tg-bav5">내용</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">경고</td>
    <td class="tg-nrix"><img src="../../_assets/주의표시.png" width = 100 height = 100></td>
    <td class="tg-0lax">매우 위험한 상태를 나타내며 조작이나 취급을 잘못하였을 경우에 사망 또는 중상의 재해를 입거나 장비에 손상을 가할 수 있음을 의미합니다. 조작이나 취급에 주의를 요하여 주십시오.</td>
  </tr>
  <tr>
    <td class="tg-nrix">강제</td>
    <td class="tg-nrix"><img src="../../_assets/강제표시.png" width = 100 height = 100>  </td></td>
    <td class="tg-0lax">반드시 실시해야만 하는 것을 나타냅니다.</td>
  </tr>
  <tr>
    <td class="tg-nrix">금지</td>
    <td class="tg-nrix"><img src="../../_assets/금지표시.png" width = 100 height = 100></td>
    <td class="tg-0lax">절대로 해서는 안 되는 것을 나타냅니다.</td>
  </tr>
</tbody>
</table># 1.4.2. 안전명판

명판, 경고 표시, 안전 기호는 로봇과 제어반 내, 외부에 부착되어 있습니다. 로봇과 제어반 사이의 와이어하니스(wire harness)와 로봇, 제어기 내, 외에 있는 케이블(cable)에 대하여 명칭 표시물 및 전선 마크(mark)가 제공되어 있습니다.

모든 종류의 명판은 로봇 본체, 제어반의 분명한 위치에 명확히 부착되어 안전 및 그 기능을 다 하도록 되어있습니다.

로봇이 설치된 바닥에 표시되는 로봇영역에 대한 페인트 표시나 위험지역 표시는 로봇시스템이 설치된 시설이나 기계 내에 있는 다른 표시들과는 형태나 색상, 스타일 면에서 확연히 다르게 표시되도록 하여야 합니다. 

<blockquote>
<table border="0">
<thead>
  <tr>
    <td> 
    <div align="center">
     <img src="../../_assets/금지표시.png" width = 60 height = 60> 
    </div>
    </td>
    <td colspan="4">       
      로봇 본체 및 제어기에서 분명하게 보이는 명판, 경고 표시, 안전 기호, 명칭 표시물, 전선 마크(Mark) 등을 옮기거나 커버를 씌우거나 페인트칠 등으로 손상을 주는 일체의 행위를 금합니다.
    </td>
  </tr>
</thead>
</table>  
</blockquote># 1.5. 안전기능의 정의

![](../_assets/말머리이미지.png )<font size = 3> **비상정지기능-IEC 204-1,10,7** </font><br>
제어기와 티치펜던트(Teach Pendant)에 각각 비상정지 버튼이 한 개씩 있으며, 필요에 따라 추가로 비상정지 버튼을 로봇의 안전 체인 회로에 연결할 수 있습니다. 비상정지 기능은 로봇의 모든 제어 기능보다도 우선적으로 적용되는 기능입니다. 로봇 각축 MOTOR에 전원 공급을 중단하여, 가동 중인 상태를 정지시키며, 로봇에 의하여 제어되는 기타 위험한 기능들을 사용하지 못하도록 전원을 제거합니다.

![](../_assets/말머리이미지.png )<font size = 3> **안전 정지 기능-EN ISO 10218-1:2011** </font><br>
안전정지 회로를 구성해야 하며, 각 로봇은 이 회로를 통해 안전장치와 인터록이 연결될 수 있도록 하여야 합니다. 로봇은 안전문, 안전패드, 안전등과 같은 외부의 안전장치와 연결되어 사용할 수 있도록 다수의 전기적 입력신호를 가져야 합니다. 이러한 신호는 로봇자체 및 주변설비 등 모든 설비로부터 행해지는 로봇의 안전 기능을 수행하도록 합니다. 

![](../_assets/말머리이미지.png )<font size = 3> **속도 제한 기능-EN ISO 10218-1:2011** </font><br>
수동조작 모드에서 로봇 속도는 최고 250mm/s로 제한됩니다. 속도의 제한은 TCP(Tool Center Point) 뿐만 아니라 수동조작을 행하는 로봇의 모든 부분에 적용됩니다. 또한 로봇에 장착된 장비의 속도는 모니터링이 가능하도록 해야 합니다.

![](../_assets/말머리이미지.png )<font size = 3> **동작영역의 제한 - ANSI/NFPA 79:2021** </font><br>
각축의 동작 영역은 소프트리미트(Soft limit)에 의해 제한됩니다. 또한 1~3축은 기계적 스토퍼(Stopper)에 의해서도 동작 영역을 제한 받도록 하는 기능입니다.

![](../_assets/말머리이미지.png )<font size = 3> **조작 모드의 선택 - ANSI/NFPA 79:2021** </font><br>
로봇은 수동 또는 자동모드에서 조작할 수 있습니다. 수동모드에서 로봇은 티치펜던트(Teach Pendant)에 의해서만 조작됩니다.# 1.6. 설치# 1.6.1. 안전 보호망

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>
            <td colspan="4"> 로봇 동작 시 로봇과 작업자가 충돌할 위험이 있기 때문에 작업자가 로봇과 가까이 하지 않도록 안전망을 설치하여 주십시오.</td>
        </tr>
    </thead>
</table>  
</blockquote><br>



로봇 동작 시 로봇과 작업자가 충돌할 위험이 있기 때문에 작업자가 로봇과 가까이 하지 않도록 안전망을 설치하여 주십시오. 작업자나 그 밖의 사람이 잘못 진입하여 사고가 발생할 수 있습니다. 로봇이나 용접 치구의점검, 또는 팁 드레싱(tip dressing), 팁교환(tip changing) 을 위해 로봇동작 중에 안전망(fence)의 문을 열고 설비에 접근하면 로봇이 정지하도록 구성하여 주십시오.


![](../../_assets/그림_1.1_권장펜스크기와_출입구크기.png)

그림 1.1 권장 펜스 크기와 출입구 크기(슬롯형 출입구)


![](../../_assets/그림_1.2_권장펜스크기와_출입구크기.png)

그림 1.2 권장 펜스 크기와 출입구 크기(사각형 출입구)

<ol style="list-style-type:decimal" start="1">
		<li>안전망은 로봇 동작영역을 커버하며, 작업자가 티칭(teaching) 작업 및 보수작업 등에 지장이 없도록 충분한 공간을 확보하여야 하며, 쉽게 이동시키지 못하도록 견고하게 하고, 사람들이 쉽게 넘어 들어가지 못하는 구조로 하여 주십시오. </li><br>		
		<li>안전망은 원칙적으로 고정식으로 설치해야 하며 요철 또는 예리한 부위 등의 위험부분이 없는 것을 사용하여 주십시오.</li><br>	
		<li>안전망 안으로 출입이 가능하도록 출입문을 설치하고, 출입문에는 안전플러그를 반드시 취부하여 플러그를 뽑지 않으면 문이 열리지 않도록 합니다. 또 안전플러그를 뽑거나 안전망이 열린 상태에서는 로봇이 운전준비 OFF, 모터OFF 되도록 배선해 주십시오.</li><br>	
		<li>안전플러그를 뽑은 상태에서 로봇을 동작하고자 할 경우에는 저속으로 재생 되도록 배선하여 주십시오.</li><br>	
        <li>로봇의 비상정지 버튼은 작업자가 빠르게 누를 수 있는 곳에 설치하여 주십시오. </li><br>	
        <li>안전망을 설치하지 않은 경우에는 안전플러그를 대신할 수 있도록, 로봇의 동작범위 내에 들어가는 장소 전체에 광전 스위치, 매트스위치 등을 설치하여, 사람이 진입하였을 때 로봇이 자동으로 정지하도록 해주십시오.</li><br>
        <li>로봇의 동작영역(위험영역)은 바닥에 페인트 칠을 하는 것과 같이 식별될 수 있도록 하여 주십시오. </li><br>
</ol># 1.6.2. 로봇 및 주변기기 배치

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>
            <td colspan="4"> 반드시 다음과 같은 방법에 의해 로봇과 주변기기들을 배치하여 주십시오.</td>
        </tr>
    </thead>
</table>  
</blockquote><br>



<ol style="list-style-type:decimal" start="1">
		<li>제어기나 주변장치의 1차전원을 접속할 경우 공급 측 전원이 OFF되어 있는가를 확인한 후 작업을 하시기 바랍니다. 220V, 440V등 고전압을 1차전원으로 사용하므로 감전사고의 위험이 있습니다.  </li><br>		
		<li>안전망의 출입구에 [운전 중 진입금지] 표찰을 부착하고, 작업자에게 그 취지를 주지시켜 주십시오.</li><br>	
		<li>제어기, 인터록반, 기타조작반 등은 전부 안전망 밖에서 조작할 수 있도록 배치하여 주십시오. </li><br>	
		<li>조작 스탠드를 설치할 경우 조작 스탠드에도 비상정지 버튼을 부착하여 주십시오. 로봇을 조작하는 모든 곳에서 비상시에 정지할 수 있도록 하여야 합니다. </li><br>	
        <li>로봇 본체와 제어기, 인터록(Interlock)반, 타이머(Timer) 등의 배선, 배관류가 작업자 발에 걸리거나 포크리프트(Forklift) 등에 직접 밟히지 않도록 하여 주십시오. 작업자가감전 되거나, 배선이 단선되는 사고가 발생할 위험이 있습니다.  </li><br>	
        <li>제어기, 인터록(Interlock)반, 조작스탠드 등은 로봇 본체의 움직임이 충분히 보일 수 있는 곳에 배치하여 주십시오. 로봇의 동작이 보이지 않는 곳에서 로봇에 이상이 발생하고 있거나 작업자가 작업중일 때, 로봇을 조작할 경우 대형 사고가 발생할 위험이 있습니다.</li><br>
        <li>필요로 하는 로봇의 작업영역이 로봇의 동작가능영역보다 좁을 경우 로봇의 동작영역을 제한 하십시오. 소프트리미트(Soft limit), 기계적 스토퍼(Stopper) 등으로 제한 가능합니다. 로봇을 잘못 조작하는 등의 이상조작으로 제한영역을 벗어나는 동작이 발생할 경우에도 사전에 동작영역제한 기능에 의해 로봇이 자동으로 정지합니다. (본체 보수 설명서를 참조하십시오.) </li><br>
        <li>용접 중 스패터(Spatter) 등이 작업자에게 떨어지거나 주변에 떨어져 화상 또는 화재의 위험이 있을 수 있습니다. 로봇 본체의 움직임이 충분히 보이는 범위에 차광판, 커버(Cover) 등을 설치하여 주십시오. </li><br>
        <li>로봇의 운전상태를 나타내는 자동, 수동 상태는 조금 떨어진 곳에서도 인식할 수 있도록 눈에 잘 띄는 장치를 설치해 주십시오. 자동운전을 개시할 경우 부저(Buzzer)나 경보등 등이 유용합니다.  </li><br>
        <li>로봇 주변의 장치에는 돌출부가 없도록 하여 주십시오. 필요하면 커버 등으로 덮어 주십시오. 통상 작업자가 접촉하여 사고가 발생할 위험이 있으며, 갑작스런 로봇동작에 놀란 작업자가 넘어져서 대형 사고가 발생할 위험이 있습니다.  </li><br>
        <li>안전망 안으로 손을 넣어 작업물의 반입, 반출을 실시하는 시스템 설계는 하지 말아 주십시오. 압착, 절단 사고의 위험이 있습니다.  </li><br>
</ol>



![](../../_assets/그림_1.3_LCD용로봇주변장치와_작업자의배치_원통형.png)
(원통형)
![](../../_assets/그림_1.3_LCD용로봇주변장치와_작업자의배치_빔형.png)
(빔형)

그림 1.3 LCD용 로봇 주변장치와 작업자의 배치


![](../../_assets/그림_1.4_산업로봇주변장치와_작업자의배치.png)

그림 1.4 산업용 로봇 주변장치와 작업자의 배치# 1.6.3. 로봇 설치

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 반드시 다음과 같은 방법에 의해 로봇과 주변기기들을 배치하여 주십시오.</td>
        </tr>
    </thead>
</table>  
</blockquote><br>

로봇의 기능을 충분히 발휘하기 위해서는 미리 검토, 계획된 기초 및 배치에 따라 설치합니다. 로봇의 설치상태가 나쁘면, 가동 중에 로봇과 작업물과의 상대위치에 오차가 발생하기도 하고, 진동을 일으켜 로봇의 작업품질을 저하시키기도 하며, 로봇의 수명을 단축시킬 뿐 아니라 위험한 상태를 초래하기도 합니다. 따라서 로봇 설치 시 아래 사항을 주의하여 주십시오.

<br><br>

![](../../_assets/말머리이미지.png )<font size = 3> **일반적 안전사항** </font><br>


<ol style="list-style-type:decimal" start="1">
		<li>
        작업자 등을 보호하기 위해선 로봇을 설치하는 국가의 법규와 규격에서 규정하는 안전요구 사항에 따라 시스템을 완벽하게 설계, 설치하여야 합니다.  </li><br>		
		<li>
        로봇을 사용하는 작업자는 응용, 보조 설명서에 기술된 사항을 숙지하여 산업용 로봇을 능숙하게 조작, 취급하도록 하여야 합니다. 
        </li><br>
        <li>
        로봇을 사용하는 작업자는 응용, 보조 설명서에 기술된 사항을 숙지하여 산업용 로봇을 능숙하게 조작, 취급하도록 하여야 합니다.
        </li><br>	
		<li>
        로봇을 설치하는 작업자는 문제점이 있을 경우 안전 지시사항을 설치 작업 중에 적용할 수 있어야 합니다.  
        </li><br>	
		<li>
        시스템 공급자는 안전기능을 사용하는 모든 회로가 그 기능을 확실하게 수행함을 보장하여야 합니다. 
        </li><br>	
        <li>
        로봇에 공급하는 주 전원은 로봇의 작업영역 밖에서 차단될 수 있도록 설치되어야 합니다. 
        </li><br>	
        <li>
        시스템 공급자는 비상정지 기능을 사용하는 모든 회로가 제 기능을 안전한 방법으로 수행함을 확실하게 보장하여야 합니다. 
        </li><br>
        <li>
        로봇을 급히 정지할 경우를 위하여 비상정지 버튼은 작업자가 접근하기 쉬운 곳에 위치하여야 합니다.
         </li><br>      
</ol>

<br>

![](../../_assets/말머리이미지.png )<font size = 3> **기술적 안전사항** </font><br>

<ol style="list-style-type:decimal" start="1">
		<li>
            본체치수, 동작범위를 고려하여 주변기기와의 간섭이 없도록 합니다. 
        </li><br>		
		<li>
            직사광선이 닿는 장소, 습기가 많은 장소, 기름기나 화학물질이 있는 장소, 공기 중에 금속가루, 폭발성 기체가 많은 곳의 설치는 피하여 주십시오. 
        </li><br>	
		<li>
            주위온도 0~45 ℃의 범위인 곳에 설치하여 주십시오.   
        </li><br>	
		<li>
            분해, 점검이 용이하도록 충분한 공간을 확보하여 주십시오. 
        </li><br>	
        <li>
            안전망을 설치하고, 로봇의 동작범위 안에 사람이 진입하지 못하도록 하여 주십시오. 
        </li><br>	
        <li>
            로봇 동작영역에는 장애물이 없도록 하여 주십시오.
        </li><br>
        <li>
            직사광선이 닿는 장소, 발열체의 부근에 설치할 경우에는 제어기의 열역학 상태를 고려하여 대책을 세워주십시오.
        </li><br>  
        <li>
            공기 중에 금속가루 등의 분진이 많은 곳에 설치할 경우는 별도의 대책을 세워 주십시오.
        </li><br>    
        <li>
            로봇에 용접 전류가 절대로 흐르지 않도록 설치하여 주십시오. 즉, 스폿 건(spot gun)과 로봇 손목 사이는 절연합니다.
        </li><br>   
        <li>
            접지는 노이즈에 의한 오동작 및 감전방지 등의 점에서 중요하므로, 하기와 같이 설치하여 주십시오.
            <ol style="list-style-type:lower-roman" start="1">
                <li>
                    전용 접지단자를 설치하고 제3종 접지 이상으로 합니다. (로봇 제어기의 입력전압이 400 V 이상일 경우에는 특별 제 3종 접지 이상으로 하십시오.) 
                </li>
                <li>
                    접지선은 제어반 내부의 접지 버스바(bus bar)에 접속합니다.  
                </li>
                <li>
                    로봇 본체 설치 시에 앵커(anchor) 등에 의해 바닥에 직접 접지된 경우에는 제어기측과 로봇 본체 측이 2점 접지로 되어 폐회로가 발생, 역으로 노이즈 등에 의한 오동작이 우려됩니다. 이러한 경우에는 로봇 본체의 베이스(base) 부에 접지선을 접속하고 제어기측은 접속하지 않습니다. 또한 로봇 정지 시에 떨림이 있을 경우에는 접지의 불완전 혹은 폐회로 발생의 가능성이 크므로 다시 한번 접지를 살펴주십시오.  
                </li>
                <li>
                    트랜스 내장 건(gun)을 사용할 경우에는 1차 전원 케이블이 직접 스폿 건(spot gun)에 접속되기 때문에 떨어질 위험성이 있습니다. 이 경우에는 제어반의 보호와 감전방지를 위해 로봇 본체의 베이스(base)부에 직접 접지선을 접속하고, 제어기에는 접속하지 말아 주십시오.
                </li>
            </ol>
        </li><br>   
</ol># 1.6.4. 로봇 설치 공간

본체와 제어기 및 다른 주변장치의 보전할 공간을 충분히 확보한 다음 로봇을 설치합니다. 본체와 제어기를 설치하기 위해선 상기 기술한 설치영역을 확보하여 설치하여 주십시오. 로봇본체가 쉽게 보이며, 안전하게 작업할 수 있는 곳으로 안전망 밖에 제어기를 설치하여 주십시오.
제어기의 문을 열었을 때 보수작업이 용이하도록 설치하십시오. 이용할 수 있는 보전 영역을 확보하십시오. 제어기 제원은 제어기 종류에 따라 바뀔 수 있습니다. (자세한 내용은 해당 보수설명서를 참조하십시오.)
# 1.7. 로봇 조작 시 안전 작업

안전사고 예방을 위해 안전작업 절차를 반드시 지켜 주십시오. 어떠한 상황에서도 안전장치나 회로를 변경하거나 무시하지 않도록 하며 감전사고에 유의하여 주십시오.

자동모드에서 모든 정상적인 작업은 안전망 밖에서 행하여야만 합니다. 작업 전에는 로봇의 작업영역 안에 사람이 없는지를 반드시 확인하여 주십시오. 
# 1.7.1. 로봇 조작 시 안전대책

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            <div>
            </td> 
            <td colspan="4"> 
                로봇 조작 시 안전은 매우 중요하므로 다음의 대책을 따라 주십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>



<ol style="list-style-type:decimal" start="1">
		<li>
            로봇을 조작하는 작업자와 조작할 가능성이 있는 작업자 및 감시인은 소정의 교육을 수강하여 안전 및 로봇의 기능에 관해서 충분히 인식한 사람으로 지명된 자 외에는 조작하지 말아 주십시오. 
        </li><br>		
		<li>
            안전모, 보안경, 안전화는 필히 착용하십시오. 
        </li><br>	
		<li>
            반드시 2명이 작업합니다. 1명은 티칭(teaching) 작업, 1명은 조작반에서 감시합니다. 1인은 언제라도 비상정지 스위치를 누를 태세를 갖추고 또 한 사람은 동작영역에서 충분히 주의하여 신속하게 작업을 행합니다. 또한 작업 전에는 미리 대피경로를 확인하여 두십시오.   
        </li><br>	
		<li>
            로봇 동작 영역 내에 작업자가 없는가를 확인 후 전원을 투입합니다. 
        </li><br>	
        <li>
            티칭(teaching) 등의 작업은 원칙적으로 로봇 동작범위 밖에서 합니다. 그러나 장비를 정지하고 동작범위 내에서 작업하는 경우에는 자동운전으로 바꾸기 위한 키 스위치나 안전플러그를 가지고 들어가 주십시오.<p>
            다른 작업자가 잘못하여 자동운전으로 바꾸지 않도록 할 필요가 있습니다. 또한 만일의 경우 로봇의 오 동작, 오 조건에 대비하여 그 동작의 방향에 특히 주의를 기울여 주십시오.
        </li><br>
        <li>
            감시인은 다음의 사항을 준수하여 주십시오. 
            <ol style="list-style-type:lower-roman" start="1">
                <li>
                    로봇 전체를 볼 수 있는 곳에 위치하고 감시의 직무에 전념합니다.
                </li>
                <li>
                    이상이 있을 때 즉시 비상정지버튼을 누릅니다.   
                </li>
                <li>
                    작업에 종사하는 자 외에는 가동범위 내에 있지 않도록 합니다.
                </li>
            </ol>
        </li><br>
        <li>
            수동 조작 시 속도는 최대 250 mm/sec 로 제한됩니다. 
        </li><br>  
        <li>
            티칭(teaching)시에는 [티칭 작업 중]이라는 푯말 붙이고 작업합니다. 
        </li><br>    
        <li>
            안전망 내에 진입할 때는 작업자가 필히 안전 플러그를 뽑아서 갖고 들어가십시오. 
        </li><br>   
        <li>
            티칭(teaching) 작업장소 및 그 주변에 노이즈의 발생원인이 되는 기기를 사용하지 말아주십시오.
        </li><br>   
        <li>
            티칭(teaching) 포인트를 보면서 티치펜던트(teach pendant)의 로봇조작 버튼을 손의 감각으로써만 조작하지 말고 눈으로 확인하며 조작하십시오.
        </li><br>   
        <li>
            <img src="../../_assets/작은주의표시.png">여러 대 구입하는 경우에 준비해야 할 보수 부품입니다.
        </li><br>   
        <li>
            티칭(teaching) 작업 시 발 밑을 충분히 확인하면서 작업합니다. 특히 고소(2 m 이상) 티칭(teaching) 작업 시 발을 디딜 수 있는 안전한 영역을 확보한 후 작업하여 주십시오.
        </li><br> 
        <li>
            <img src="../../_assets/작은주의표시.png">이상 발생시의 조치는 다음과 같이 합니다. 
            <ol style="list-style-type:lower-roman" start="1">
                <li>
                    이상한 동작이 발견되었을 때는 즉시 비상정지 스위치를 누르십시오. 
                </li>
                <li>
                    비상 정지되어 이상확인을 할 때에는 관련설비의 정지상태를 필히 확인하십시오.    
                </li>
                <li>
                    전원의 이상발생으로 로봇이 자동적으로 정지한 경우에는 완전히 로봇이 정지된 것을 확인한 후에 원인을 조사하여 대책을 실시합니다. 
                </li>
                <li>
                    비상정지 장치가 제 기능을 수행하지 않는 경우는 즉시 주 전원을 차단하고 원인을 조사하여 대책을 실시합니다. 
                </li>
                <li>
                    이상의 원인조사는 지명된 사람 외에는 하지 말아야 합니다. 비상 정지된 후 재 기동은 이상의 원인이 확실히 밝혀진 후 대책을 실시하고 나서 순서에 의해 작업을 합니다.. 
                </li>
            </ol>
        </li><br> 
        <li>
            로봇의 가동방법, 조작방법, 이상시의 조치 등에 관하여 설치장소, 작업내용에 따라 적절한 작업규정을 작성해 둡니다. 또한, 그 작업규정에 따라서 작업을 진행하도록 합니다.
        </li><br> 
        <li>
            로봇 정지 시 유의사항 <br>
            로봇이 정지해 있는 것으로 알고, 무작정 접근하는 것은 반드시 피하여야 합니다. 정지해 있다고 생각한 로봇에 접근하였는데, 로봇이 갑자기 움직여서 재해가 발생한 경우가 많습니다. 로봇이 정지해 있는 상태에는 아래와 같은 경우가 있습니다.<br><br>
            <style type="text/css">
                .tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
                .tg caption{caption-side: top;text-align: left;}
                .tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
                overflow:hidden;padding:10px 5px;word-break:normal;}
                .tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
                font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
                .tg .tg-osmi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
                .tg .tg-bb96{background-color:#ccf1bc;color:#000000;text-align:center;vertical-align:middle}
                .tg .tg-nrix{text-align:center;vertical-align:middle}
            </style>
            <table class="tg">
                <caption> 표 1-2 로봇 상태</caption> 
                <thead>
                <tr>
                    <th class="tg-osmi">No.</th>
                    <th class="tg-osmi">로봇상태</th>
                    <th class="tg-osmi">구동원</th>
                    <th class="tg-osmi">출입가능 여부</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td class="tg-bb96">1</td>
                    <td class="tg-nrix">일시 정지 중<br>(가벼운 이상, 일시 정지스위치)</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">2</td>
                    <td class="tg-nrix">비상정지 중<br>(중대한 이상, 비상정지스위치, 안전문)</td>
                    <td class="tg-nrix">OFF</td>
                    <td class="tg-nrix">O</td>
                </tr>
                <tr>
                    <td class="tg-bb96">3</td>
                    <td class="tg-nrix">주변장치에서의 입력신호대기<br>(START INTERLOCK)</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">4</td>
                    <td class="tg-nrix">재생완료 중</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                <tr>
                    <td class="tg-bb96">5</td>
                    <td class="tg-nrix">대기 중</td>
                    <td class="tg-nrix">ON</td>
                    <td class="tg-nrix">X</td>
                </tr>
                </tbody>
            </table><br>
            출입이 가능한 상태에서도 불시의 움직임에 대한 주의를 게을리 해서는 안됩니다. 어떠한 경우든지 긴급상황에 대한 준비 없이 접근하는 것은 절대로 피하여 주십시오.<br><br>            
</ol>

<ol style="list-style-position: outside; list-style-type:square;" start="1">
    <li>
        <b>
        일시 정지 중, 가벼운 이상조치를 위해 출입문을 여는 경우 (노즐접촉과 용착검출, 아크 이상에 의한 경우 등) 에는 티칭(teaching) 작업의 출입과 똑같은 대책을 강구해서 출입합니다.
        </b>
    </li>
</ol><br>

<ol style="list-style-type:decimal" start="17">
    <li>
        로봇 조작을 완료하면 안전망 안을 청소하여 공구, 기름, 이물질 등이 남아 있지 않은지를 확인하여 주십시오. 작업영역이 기름 등으로 더러워지거나, 공구 류가 떨어져 있으면 그것이 원인이 되어 전도 등의 사고가 발생할 경우가 있습니다. 항상 정리정돈을 생활화하기 바랍니다. 
    </li>
</ol># 1.7.2. 로봇 시운전시 안전대책

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                로봇 시운전시 안전은 매우 중요하므로 다음의 대책을 따라 주십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>



시운전을 할 경우는 티칭(teaching)프로그램, 지그(jig), 시퀀스(sequence) 등 전체 시스템에 대하여 설계 오류나 티칭(teaching) 오류, 제작 불량 등이 존재할 가능성이 있습니다. 이로 인하여 시운전 작업에 있어서 한층 더 안전의식을 가지고 작업에 임해야 합니다. 복합요인으로 인해 안전사고가 발생할 경우가 있습니다. 

<ol style="list-style-type:decimal" start="1">
		<li>
            조작에 우선하여 비상정지 스위치, 정지 스위치 등 로봇을 멈추기 위한 스위치 류, 신호 등의 기능을 확인하여 주십시오. 그 후 이상검출관련 동작을 확인하여 주십시오. 먼저 로봇을 정지시키는 모든 신호의 확인이 가장 중요합니다. 사고 발생이 예지될 시 가장 중요한 것이 로봇을 정지시키는 일입니다.
        </li><br>		
		<li>
            로봇을 시운전할 경우는 속도 가변 기능에서 저속(20 % ~ 30 % 정도)으로 가동해서, 1사이클 이상 반복하여 동작을 확인하여 주십시오. 문제점이 발견되었을 경우는 즉시 수정하여 주십시오. 그 후, 순서대로 속도를 올려(50 % → 75 % → 100 %)서, 각각 1 사이클(Cycle) 이상 반복해서 동작을 확인하여 주십시오. 처음부터 고속으로 동작시키면 큰 사고를 발생시킬 수 있습니다. 
        </li><br>	
		<li>
            시운전시에는 어떤 문제점이 발생할지 예상할 수 없습니다. 시운전 중에는 절대로 안전망 안으로 들어가지 말아주십시오. 신뢰성이 낮은 상태이기 때문에 예상하지 못하는 사고가 발생할 가능성이 매우 높습니다. 
        </li><br>	          
</ol>
# 1.7.3. 자동 운전시 안전대책

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                로봇 자동 운전 시 안전은 매우 중요하므로 다음의 대책을 따라 주십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
            안전망 출입구에는 [운전 중 출입금지] 표시를 하는 한편 작업자에게는 운전 중에는 출입을 금할 것을 철저히 당부하여 주십시오. 로봇이 정지하고 있다면 상항을 판단 후 안전망 안으로 들어 갈 수가 있습니다. 
        </li><br>		
		<li>
            <img src="../../_assets/작은주의표시.png">자동운전 개시 때에는 안전망 안에 작업자가 있는지 꼭 확인하여 주십시오. 작업자가 있음을 확인하지 않고 작업할 경우 인명사고를 낼 수 있습니다.
        </li><br>	
		<li>
            자동운전 개시 때에는 프로그램 번호, 스텝 번호, 모드, 기동선택 등이 자동운전 가능 상태임을 확인하고서 개시하여 주십시오. 다른 프로그램이나 스텝이 선택된 상태에서 기동할 경우 로봇이 예상하지 않았던 동작을 하여 사고를 발생시킬 수 있습니다.
        </li><br>	  
        <li>
            자동운전 개시 때에는 로봇이 자동운전 개시할 수 있는 위치에 있는가를 확인하고 개시하여 주십시오. 프로그램 번호나 스텝 번호가 로봇 위치와 맞는지 확인하여 주십시오. 프로그램이나 스텝이 맞더라도 로봇이 다른 위치에 있을 경우 통상과 다른 동작으로 인해 사고가 발생할 수 있습니다. 
        </li><br>	
        <li>
            자동운전 개시 때에는 즉시 비상정지 스위치를 누를 수 있도록 준비해주십시오. 예측하지 않았던 로봇의 동작이나 상황이 발생할 경우 즉시 비상정지를 눌러 주십시오. 
        </li><br>	 
        <li>
            로봇의 동작경로, 동작상황, 동작음 등을 파악하여 이상한 상태는 없는지를 판단할 수 있도록 하여 주십시오. 로봇은 갑자기 고장 등 이상을 일으키는 경우도 있습니다만, 고장이 발생하기 전에 어떤 징조를 나타내는 경우가 있습니다. 이것을 사전에 예지하기 위해서 로봇의 정상 운전 상태를 잘 파악해 두십시오. 
        </li><br>	 
        <li>
            <img src="../../_assets/작은주의표시.png">어떤 이상을 발견하면 즉시 비상정지하고, 이상에 대한 적절한 조치를 취해 주십시오. 적절한 조치 없이 사용시 생산정지뿐만 아니라 중대한 인명사고를 유발할 수 있는 심각한 고장이 발생할 수 있습니다.  
        </li><br>	      
        <li>
            <img src="../../_assets/작은주의표시.png">이상발생 후, 조치를 완료하고 동작을 확인하는 경우 안전망 안에 작업자가 있는 상태에서는 동작시키지 말아 주십시오, 신뢰성이 낮은 상태로 다른 이상이 발생하는 등, 예측하지 못한 사고가 발생할 수 있습니다. 
        </li><br>	 
</ol>
# 1.8. 안전 망 내 진입 시 안전 대책

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../_assets/주의표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                안전 망 내 진입 시에는 안전이 매우 중요하게 되므로 다음의 대책을 따라 주십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>

로봇은 속도가 느린 경우에도 그 무게가 상당히 육중하며 그 힘이 매우 강력합니다. 로봇의 안전영역 안으로 들어갈 때에는 해당국가의 안전 관련 규정을 반드시 준수해야 합니다. 

작업자는 로봇이 예상외의 동작을 할 수 있음을 항상 주지해야 합니다. 로봇은 동작이 잠시 멈추더라도 다음 순간 빠른 속도로 이동할 수 있습니다. 작업자는 외부의 신호에 의하여 로봇이 경고 없이 경로를 바꾸어 움직일 수 있음을 알아야 합니다. 로봇을 티칭(teaching)하거나 시운전시 로봇을 멈추려 할 경우 즉시 티치펜던트(teach pendant)나 제어기 조작반으로 멈출 수 있어야 합니다.

로봇작업 영역 안의 안전 문으로 들어갈 때에는 반드시 티치펜던트(teach pendant)를 가지고 들어가도록 하여, 다른 사람이 로봇을 조작하지 못하게 하십시오. 제어기 조작반에는 반드시 지금 로봇 조작중임을 알릴 수 있는 푯말을 걸어 두십시오.

만약 사람이 로봇 작업영역 안으로 들어갈 때는 다음 사항을 반드시 숙지하여 주십시오. 

<ol style="list-style-type:decimal" start="1">
		<li>
            티칭(teaching)하는 사람 외에 로봇 작업영역 안으로 들어가지 마십시오. 
        </li><br>			
		<li>
            제어기의 조작설정 모드는 제어기 조작반에서 수동모드 위치에 있어야 합니다. 
        </li><br>	  
        <li>
        	늘 인증된 작업복을 입습니다. (느슨한 임의의 옷은 안됩니다.) 
        </li><br>	
        <li>
            제어기를 조작할 때는 장갑을 착용하지 말아 주십시오. 
        </li><br>	 
        <li>
            작업복 밖으로 속옷, 셔츠, 넥타이등이 나오지 않도록 하십시오. 
        </li><br>	 
        <li>
            귀고리, 반지, 목걸이 등과 같은 큰 보석은 착용하지 말아 주십시오. 
        </li><br>	      
        <li>
            안전화, 안전모, 보안경은 꼭 착용하며, 필요에 따라서 안전장갑과 같은 안전장비를 착용합니다. 
        </li><br>	 
        <li>
            로봇을 조작하기 전 제어기 조작반과 티치펜던트(teach pendant) 상의 비상정지 스위치를 눌렀을 때 비상정지 회로가 제 기능을 발휘하여 모터OFF가 되는지를 확인합니다. 
        </li><br>	
        <li>
            로봇 본체와 마주보는 자세로 작업하여 주십시오.  
        </li><br>	
        <li>
            미리 결정된 작업 절차를 따릅니다.
        </li><br>	
        <li>
            예상치 못하게 로봇이 자기를 향하여 돌진할 경우가 있다고 생각하고 대피할 수 있는 방법이나 장소를 마련해 두십시오.
        </li><br>	
</ol># 1.9. 보수 점검 시 안전 대책# 1.9.1. 제어기 보수, 점검 시 안전대책

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td>   
            <td colspan="4"> 
                로봇 제어기 보수, 점검 시 다음의 안전대책을 따라 주십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
            보수, 점검 작업을 하는 사람은 특별 보수교육을 받아서, 내용을 숙지한 사람만이 해야 합니다.  
        </li><br>			
		<li>
            제어기 보수, 점검 절차에 의하여 작업을 진행하여 주십시오.  
        </li><br>	  
        <li>
        	보수, 점검작업은 반드시 주위의 안전을 확인하여 위험을 피하기 위한 통로나 장소를 확보하고서 안전한 작업을 하여 주십시오. 
        </li><br>	
        <li>
            로봇의 일상점검이나 수리, 부품 교환 등의 작업을 할 때는 반드시 전원을 내리고 작업하십시오. 또, 다른 작업자가 부주의로 전원을 투입할 수 없도록 1차 전원에 [전원투입금지] 등의 경고 표시를 하여 주십시오. 
        </li><br>	 
        <li>
            교환 부품은 반드시 지정된 부품을 사용하십시오. 
        </li><br>	 
        <li>
            제어기 문을 열 경우는 반드시 전원을 내리고, 약 3분 동안 기다린 후 작업에 들어가십시오.
        </li><br>	      
        <li>
            제어기 내부의 보수 및 점검 작업시, 충분한 조도가 확보되지 않을 경우에는 외부 조명등을 사용 하십시오. 
        </li><br>	 
        <li>
            서보 앰프의 방열 판과 회생저항은 열이 심하게 발생하므로 만지지 마십시오. 
        </li><br>	
        <li>
            보수가 끝낸 다음 제어기내에 공구, 이물질 등을 놓아두지 않았는지 확인한 후 문을 확실하게 닫아 주십시오.
        </li><br>	
</ol># 1.9.2. 로봇시스템, 로봇본체의 보수, 점검 시 안전대책

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                로봇시스템, 로봇본체의 보수, 점검 시 다음의 안전대책을 따라 주십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
            제어기 보수, 점검 시 안전대책을 참조하여 주십시오. 
        </li><br>			
		<li>
            로봇시스템, 로봇 본체를 보수, 점검할 때는 지시된 절차에 의하여 작업을 진행하여 주십시오. 
        </li><br>	  
        <li>
        	제어기의 주 전원은 꼭 차단하여 주십시오. 다른 작업자가 다시 전원을 올리지 못하도록 1차 전원에 [전원투입금지] 등의 경고 표시를 하여 주십시오. 
        </li><br>	
        <li>
            로봇 본체의 보수, 점검 시 로봇의 암(arm)이 낙하 또는 이동 시 위험이 생길 경우가 있으므로 반드시 암(arm)을 고정한 후에 작업하여 주십시오. (로봇 본체 보수설명서를 참조하여 주십시오.)
        </li><br>
        <li>
            가스스프링의 압력이 저하될 경우 로봇의 암(Arm)이 낙하될 수 있으므로, 암 낙하 방향 밑으로 절대 들어가지 않도록 하여 주십시오. 암 낙하 방지를 위해 가스스프링의 압력이 과다하게 저하된 상태에서는 2축의 원점이 아닌 방향으로 동작되지 않도록 하여 주시고, 2축을 원점으로 이동시킨 후 가스스프링의 압력을 보충 혹은 가스스프링을 교환하여 주십시오.
        </li><br>	 
</ol># 1.9.3. 보수, 점검 후 조치사항

<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/강제표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                보수, 점검 후에는 다음의 조치사항을 따라 주십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br>


<ol style="list-style-type:decimal" start="1">
		<li>
            제어기 내의 전선이나 부품이 정상적으로 결합되어 있는지를 점검하여 주십시오. 
        </li><br>			
		<li>
            보수가 끝난 뒤 제어기, 로봇 본체, 시스템 내 또는 주위에 공구가 남겨져 있는지 확인하여 정리정돈을 확실히 하여 주십시오. 각 문은 반드시 닫아 주십시오. 
        </li><br>	  
        <li>
        	만약 어떤 문제나 치명적인 결함이 발견되었을 때는 로봇의 전원을 켜지 마십시오. 
        </li><br>	
        <li>
            전원을 켜기 전에 로봇의 작업영역 안에 작업자가 없는지, 자신이 안전한 장소에 있는지를 확인한 후 전원을 투입하십시오. 
        </li><br>	
        <li>
            제어반 내에 주 전원 차단기를 켜십시오. 
        </li><br>	
        <li>
            로봇의 현재의 위치와 상태를 확인하십시오. 
        </li><br>	
        <li>
            로봇을 저속에서 작동하십시오. 
        </li><br>	 
</ol># 1.10. 안전 기능
# 1.10.1. 안전 전기회로의 작동

![](../../_assets/그림_1.5_안전체인_구성도_.png)


그림 1.5 안전체인 구성도


로봇의 안전 시스템은 그 상태를 계속적으로 감시하는 이중의 안전 전기회로로 되어 있습니다. 만약 에러가 검지되면 모터의 전원을 바로 차단하면서 모터 브레이크를 작동시킵니다. 모터ON 상태로 돌아가기 위해선 이중 전기회로의 스위치가 모두 연결되어야 합니다. 만약 안전회로의 이중 스위치 중 어느 하나라도 단락 되었을 때는 모터의 접촉 자는 끊어지며 브레이크가 작동하여 로봇이 정지합니다. 또한 안전회로가 끊어지면 바로 인터럽트의 원인을 확인하기 위하여 인터럽트 콜이 제어기에 보내집니다. 

조작중의 안전 제어회로는 제어기와 모터 ON 모드가 상호 작용하는 이중의 안전 전기회로를 근거로 합니다. 로봇이 모터ON 모드로 되기 위해선 몇 개의 스위치로 연결되어 구성된 안전 전기회로가 모두 연결되어야 합니다. 모터ON 모드는 모터에 구동전류가 공급됨을 뜻합니다. 만약 안전 전기회로의 어떤 접촉 점이 끊어져 있으면 로봇은 항상 모터OFF 모드로 돌아갑니다. 모터OFF 모드는 로봇의 모터에 구동전류가 공급되지 않고 모터 브레이크가 작동되는 상태를 뜻합니다. 스위치의 상태는 티치펜던트(Teach Pendant)(조작설명서 “I/O 모니터링” 화면 참조)에 표시됩니다. 

<font size = 3><b>안전 전기회로 </b></font>

제어기 조작반과 티치펜던트(Teach Pendant) 상의 비상정지 버튼과 외부 설비에 설치된 비상정지 버튼은 안전 전기회로에 포함되어 있습니다. 자동 조작모드에서 작동되는 안전장치(안전 플러그, 안전 지역 진입 정지장치 등)는 사용자가 설치할 수 있습니다. 수동조작에서는 안전장치신호가 무시됩니다. 안전장치에 의한 정지는 (전반적인 안전 정지장치) 사용자가 연결하여 모든 작동모드에서 사용할 수 있습니다. 즉 자동 조작모드에서는 모든 안전장치(도어, 안전매트, 안전 플러그 등)가 동작되어 누구도 로봇의 안전지역으로 들어갈 수 없습니다. 이러한 신호는 수동 조작모드에서도 생성되지만, 제어기는 로봇의 티칭(Teaching)을 위하여 무시하고 로봇이 계속 조작되도록 합니다. 이 경우 로봇의 최대 속도는 250 mm/s로 제한됩니다. 즉 이러한 안전 정지장치 기능의 목적은 사람이 로봇을 보전, 티칭(Teaching)하기 위해 로봇에 접근하는 동안 본체 주위에 안전한 영역을 확보할 수 있도록 하는 것입니다. 

리밋 스위치에 의하여 로봇이 정지되면 정수 설정모드에서 티치펜던트(Teach Pendant)의 조작 키(key)로 로봇을 조깅하여 위치를 변화 시킬 수 있습니다. (정수 설정 모드라 함은 “수동모드에서 『[F2]: 시스템』” 메뉴에 진입한 상태를 의미합니다.) 


<blockquote>
<table border="0">
    <thead>
        <tr>
            <td>
            <div align="center">
              <img src="../../_assets/주의표시.png" width = 40 height = 40>
            </div>
            </td> 
            <td colspan="4"> 
                안전 전기회로는 어떠한 방법으로든 결코 무시하거나, 수정, 변경되지 않도록 하십시오.
            </td>
        </tr>
    </thead>
</table>  
</blockquote><br># 1.10.2. 비상정지

비상정지는 사람이나 장비가 위험지역에 있을 때 작동되어야 합니다. 제어기의 조작패널 위의 비상정지 스위치 등 모든 안전제어 장치는 안전영역 밖에서 쉽게 접근되도록 하여야 합니다.

![](../../_assets/말머리이미지.png)<font size = 3> **비상정지 상태** </font><br>

비상정지 버튼이 눌러졌을 때 로봇은 아래와 같이 동작합니다.
어떠한 경우든 로봇은 즉시 정지합니다.

<ol style="list-style-type:square" start="1">
		<li>
            로봇의 서보 시스템 전원을 차단합니다.
        </li>		
		<li>
            로봇의 모터 브레이크가 동작합니다.
        </li>	  
        <li>
        	티치펜던트(Teach Pendant)의 화면에 비상정지 메시지가 표시됩니다.
        </li>
</ol>


비상정지는 아래의 두 가지 방법을 병행할 수 있습니다.

<ol style="list-style-type:decimal" start="1">
		<li>
            조작패널, 티치펜던트의 비상정지 (기본)<br><br>
            제어기 조작반과 티치펜던트(Teach Pendant) 위에 있습니다.
        </li><br>
		<li>
            외부 시스템 비상정지<br><br>
            외부 비상정지장치(스위치 등)는 비상정지 회로의 응용표준에 의하여 안전 전기회로에 연결될 수 있습니다. (“제어기 기본구성”편의 시스템보드를 참조하십시오). 이때 비상정지는 “Normal ON”이 되도록 결선하며 시운전 시 반드시 작동을 확인하여 주십시오.<br><br>
        </li><br>
</ol>


![](../../_assets/그림_1.6_시스템보드_터미널블록_TBEM를_통한_외부비상정지스위치의연결.png)

그림 1.6 시스템보드 터미널블록 TBEM를 통한 외부비상정지스위치의 연결# 1.10.3. 조작속도

로봇을 티칭하기 위해선 조작모드 스위치는 수동 위치에 있어야 합니다. 이때 로봇의 최대 속도는 250 mm/s로 제한됩니다.# 1.10.4. 안전장치 연결

외부 안전장치는 시스템 설계자에 의하여 외부에서 사용하는 안전등, 안전 커튼, 안전 플러그, 안전 매트 등을 제어기의 안전 전기회로에 연결하여 제어기를 인터록(interlock)하는데 사용합니다. 이러한 장치는 자동모드에서 정상적인 프로그램을 실행할 때 안전장치로 사용합니다. 
# 1.10.5. 동작영역의 제한

로봇을 적용할 때 충분한 안전영역을 확보하기 위하여 로봇의 동작이 필요 없다고 판단되면, 로봇의 동작범위를 제한할 수 있습니다. 안전망 등과 같은 외부 안전 장치와 로봇이 충돌할 때 이런 기능은 손해를 최소화할 것입니다. 로봇의 1,2,3축은 기계적인 스토퍼(stopper)나 전기적인 리밋 스위치에 의해서 동작범위가 통제됩니다. 기계적인 스토퍼 또는 전기적인 리밋 스위치에 의하여 동작범위가 변경될 경우는 소프트웨어 상에서도 동작영역 한계 파라미터가 변경되어야 합니다. 필요하다면 손목 3축의 움직임 또한 제한될 수 있습니다. 각축의 동작영역의 한계는 사용자에 의하여 변경하여 수행할 수 있습니다. 출하 시는 로봇의 최대 동작영역으로 설정되어 있습니다. 

<style type="text/css">
    .block {background-color:#f8f8be}
</style>
<blockquote class="block">
    <ol style="list-style-type:disc" start="1">
        <br>
		<li>
            <font size = 3><b>수동모드 : 최대속도는 250mm/s입니다. </b></font><br>
            수동모드에서는 작업자의 선택에 의하여 로봇의 안전 영역으로 들어갈 수 있도록 되어 있습니다.
        </li><br>
		<li>
            <font size = 3><b>자동모드 : 원격 조작 장치로 로봇을 조작할 수 있습니다. </b></font><br>
            출입문, 안전 매트와 같은 안전장치가 작동합니다. <br>
            어느 누구도 로봇의 안전장치 영역에는 들어가서는 안됩니다.   
        </li><br>
    </ol>
</blockquote># 1.10.6. 감시기능

<ol style="list-style-type:decimal" start="1">
		<li>
      모터 감시기능 <br>
      모터는 모터 내부에 있는 센서에 의하여 과부하로부터 보호됩니다. 
    </li>	<br>
		<li>
      전압 감시기능 <br>
      서보 앰프 모듈은 증폭소자를 보호하기 위하여 과전압, 저 전압 발생시 서보 앰프로 입력되는 전원 스위치를 Off 시킵니다. 
    </li>	  
</ol># 1.11. 엔드이펙터(End Effector)에 관련된 안전

# 1.11.1. 그리퍼(Gripper)

<ol style="list-style-type:decimal" start="1">
		<li>
      만약 작업물을 잡기 위해 그리퍼(gripper)를 사용할 경우 불시에 작업물이 떨어지는 것에 대한 방비책이 있어야 합니다. 
    </li>	<br>
		<li>
      엔드이펙터(end effector) 및 암(arm)상에 기기를 취부할 경우에는 볼트는 규정된 크기와 개수를 사용하고, 토크 렌치를 사용하여 규정토크로서 완전히 조여 주십시오. 또 볼트에 녹이 없는 것이나 더럽지 않은 것을 사용하십시오. 
    </li><br>
    <li>
      엔드이펙터 제작에 있어서는 로봇 손목 부 부하허용치의 범위 안에서 사용 가능하도록 고려하십시오. 또, 전원이나 에어공급을 중단하였을 경우에도 파지물이 방출되거나 떨어지는 일이 없는 구조로 하고, 모서리 부나 돌출부의 처리를 확실하게 해서, 대인, 대물 손상을 주지 않는 구조로 하여 주십시오. 
    </li><br>
</ol># 1.11.2. 툴(Tool) / 작업물

<ol style="list-style-type:decimal" start="1">
    <li>
      밀링 커트와 같은 공구를 안전하게 바꾸는 것이 가능하도록 해야 합니다. 커터가 회전하는 것이 멈출 때까지 안전장치는 제 기능을 확실히 발휘하여야 합니다. 
    </li>	<br>
    <li>
      툴(Tool)은 갑작스러운 정전 또는 제어 장애 등이 발생되더라도 작업물에 이상이 없도록 설계되어야 합니다. 수동 조작일 때는 작업물의 분리가 가능해야 합니다. 
    </li><br>
</ol># 1.11.3. 공압 / 수압 시스템

<ol style="list-style-type:decimal" start="1">
    <li>
      특별한 안전법규는 공압, 수압 시스템까지 적용됩니다.  
    </li>	<br>
    <li>
      이러한 시스템은 정지 후에도 잔여 에너지가 남아 있을 수 있으니, 특히 주의를 기울여 주십시오. 공압, 수압 시스템을 수리하기 전에는 반드시 기기내의 압력을 제거하여 주십시오.  
    </li><br>
</ol># 1.12. 책임

로봇 시스템은 최신 기술 표준과 승인된 안전규격에 준하여 제작되어 있습니다. 그럼에도 불구하고 사용시 로봇시스템과 주변 설비물의 충돌에 의하여 조작자의 생명의 위협이나 팔, 다리가 부상을 당하는 사고가 발생할 수 있습니다. 

로봇 시스템은 설계 용도에 맞게 기술적으로 완벽한 상태에서 사용하며, 조작에 포함된 위험성을 완전히 인식하여 안전에 주의를 기울이는 작업자에 의하여 사용해 주십시오. 로봇 시스템은 조작 지시와 로봇 시스템에서 함께 공급되는 설명서에 준하여 사용하십시오. 로봇 시스템에서 안전에 관련된 기능을 다른 용도로 사용하는 것은 절대 허용되지 않습니다. 

로봇을 설계된 목적 외에 다른 목적 또는 추가적인 목적으로 로봇 시스템을 사용하기 위해서는 설계 용도에 준하는지를 검토하여 주십시오. 제작자는 그러한 오용에 의하여 발생한 어떠한 손해 및 사고에 대하여 책임을 질 수 없습니다. 오용에 대한 책임은 전적으로 사용자에게 있습니다. 설계된 용도 안에서 로봇시스템을 조작할 때는 로봇 조작 기준서인 조작 설명서를 꼭 숙지 바랍니다. 

로봇 시스템에 포함되어 사용되는 기계나 장치에 대하여 98/37/EC(2006/42/EC) 와 US OSHA에서 지시하는 EU 기계류 기준서에 준할 때까지 로봇 시스템을 사용하지 말아주십시오.

아래의 정리된 표준서는 로봇 시스템의 안전과 관련되어 있는 것들입니다.


<ol style="list-style-type:square" start="1">
    <li>
      ANSI/RIA R15.06-1999 <br>
      Industrial Robots and Robot Systems - Safety Requirements  
    </li>	<br>
    <li>
      ANSI/RIA/ISO 10218-1-2007 <br>
      Robots for Industrial Environment - Safety Requirements - Part 1 - Robot  
    </li><br>
    <li>
      ISO 11161:2007 <br>
      Safety of machinery - Integrated manufacturing systems - Basic requirements 
    </li><br>
    <li>
      EN ISO 13849-1:2008 <br>
      Safety of machinery - Safety-related parts of control systems - Part 1: General principles for design (ISO 13849-1:2006)  
    </li><br>
    <li>
      EN 60204-1:2006 <br>
      Safety of machinery - Electrical equipment of machines - Part 1: General requirements (IEC 60204-1:2005 (Modified))  
    </li><br>
    <li>
      EN ISO 10218-1:2006 <br>
      Robots for industrial environments - Safety requirements - Part 1: Robot (ISO 10218-1:2006)   
    </li><br>
</ol>


이러한 지시를 무시하여 발생한 사고에 대한 책임은 사용자에게 있습니다. 또한 사용자가 공급한 장비나 제조사와 계약한 부분에 포함되지 않은 장비나, 사용자가 임의로 로봇 시스템 주변에 구성한 장비에 의하여 발생한 손해의 책임은 제조사에 있지 않습니다. 이러한 장비와 관련된 모든 위험에 대한 책임은 전적으로 사용자에게 있습니다.
# 2. 사양
# 2.1. 로봇 기구부 형식


![](../_assets/그림_2.1_로봇기구부형식.png)


그림 2.1 로봇 기구부 형식# 2.2. 로봇 명판 위치

명판에는 로봇형태, Serial number, 제조일자가 기록되어 있습니다.

명판은 아래 그림과 같이, 본체 하면(좌 혹은 우측)에 있습니다.



![](../_assets/그림_2.2_로봇명판부착위치.png)


그림 2.2 로봇 명판 부착 위치 (명판 CI 변경)# 2.3. 기본사양

표 2-1 모델별 기본 사양
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-c3xd{background-color:#f8f8be;border-color:inherit;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-mft0{background-color:#ccf1bc;border-color:inherit;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-c3xd" colspan="4">항목</th>
    <th class="tg-c3xd" colspan="4">사양</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3xd" colspan="4">로봇 모델</td>
    <td class="tg-c3xd">HH4L</td>
    <td class="tg-c3xd">HH7</td>
    <td class="tg-c3xd">HH7E</td>
    <td class="tg-c3xd">HH8</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">구조</td>
    <td class="tg-9wq8" colspan="4">관절형</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">자유도</td>
    <td class="tg-9wq8" colspan="4">6</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">구동방식</td>
    <td class="tg-9wq8" colspan="4">AC 서보 방식</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="6">최대동작범위</td>
    <td class="tg-mft0" rowspan="3">주축</td>
    <td class="tg-mft0">S</td>
    <td class="tg-mft0">선회</td>
    <td class="tg-9wq8" colspan="4">±2.967rad (±170°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">H</td>
    <td class="tg-mft0">전후</td>
    <td class="tg-9wq8" colspan="4">+3.14 ~ -0.96rad(+180°~ -55°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">V</td>
    <td class="tg-mft0">상하</td>
    <td class="tg-9wq8" colspan="3">+3.71 ~ - 1.22rad (+213°~ -70°)</td>
    <td class="tg-9wq8">+3.71 ~ - 1.15rad (+213°~ -66°)</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="3">손목축</td>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">회전2</td>
    <td class="tg-9wq8" colspan="4">±3.316 rad (±190°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">B</td>
    <td class="tg-mft0">굽힘</td>
    <td class="tg-9wq8" colspan="2">±2.356 rad (±135°)</td>
    <td class="tg-9wq8">±2.094 rad (±120°)</td>
    <td class="tg-9wq8">±2.356 rad (±135°)</td>
  </tr>
  <tr>
    <td class="tg-mft0">R1</td>
    <td class="tg-mft0">회전1</td>
    <td class="tg-9wq8" colspan="4">±6.283 rad (±360°)</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="6">최대속도</td>
    <td class="tg-mft0" rowspan="3">주축</td>
    <td class="tg-mft0">S</td>
    <td class="tg-mft0">선회</td>
    <td class="tg-9wq8">5.235 rad/s (300°/s)</td>
    <td class="tg-9wq8" colspan="2">6.544 rad/s (375°/s)</td>
    <td class="tg-9wq8">7.941 rad/s (455°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">H</td>
    <td class="tg-mft0">전후</td>
    <td class="tg-9wq8">4.014 rad/s (230°/s)</td>
    <td class="tg-9wq8" colspan="2">5.497 rad/s (315°/s)</td>
    <td class="tg-9wq8">6.719 rad/s (385°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">V</td>
    <td class="tg-mft0">상하</td>
    <td class="tg-9wq8">6.283rad/s (360°/s)</td>
    <td class="tg-9wq8" colspan="2">7.155rad/s (410°/s)</td>
    <td class="tg-9wq8">9.075rad/s (520°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0" rowspan="3">손목축</td>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">회전2</td>
    <td class="tg-9wq8" colspan="4">9.599 rad/s (550°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">B</td>
    <td class="tg-mft0">굽힘</td>
    <td class="tg-9wq8" colspan="4">9.599 rad/s (550°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">회전1</td>
    <td class="tg-9wq8" colspan="2">9.599 rad/s (550°/s)</td>
    <td class="tg-9wq8">13.613 rad/s (780°/s)</td>
    <td class="tg-9wq8">17.453 rad/s (1000°/s)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">가반중량</td>
    <td class="tg-9wq8">39.2 N (4 kg)</td>
    <td class="tg-9wq8" colspan="2">68.6 N (7 kg)</td>
    <td class="tg-9wq8">78.4 N (8 kg)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="2" rowspan="3">손목토크</td>
    <td class="tg-mft0">R2</td>
    <td class="tg-mft0">회전2</td>
    <td class="tg-9wq8" colspan="2">6 N·m (0.61 kgf·m)</td>
    <td class="tg-9wq8" colspan="2">17 N·m (1.73 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-mft0">B</td>
    <td class="tg-mft0">굽힘</td>
    <td class="tg-9wq8" colspan="2">6 N·m (0.61 kgf·m)</td>
    <td class="tg-9wq8" colspan="2">17 N·m (1.73 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-mft0">R1</td>
    <td class="tg-mft0">회전1</td>
    <td class="tg-9wq8" colspan="2">2.9 N·m (0.30 kgf·m)</td>
    <td class="tg-9wq8" colspan="2">10 N·m (1.02 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">위치 반복 정도<sup>1)</sup></td>
    <td class="tg-9wq8" colspan="3">±0.03 mm</td>
    <td class="tg-9wq8">±0.02 mm</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">주위 온도<sup>2)</sup></td>
    <td class="tg-9wq8" colspan="4">0 ~ 45 ℃ (273 ~ 318 K)</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">상대 습도</td>
    <td class="tg-9wq8" colspan="4">20  ∼ 85 %RH</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">본체 중량</td>
    <td class="tg-9wq8">49 kg</td>
    <td class="tg-9wq8">49 kg</td>
    <td class="tg-9wq8">49 kg</td>
    <td class="tg-9wq8">47 kg</td>
  </tr>
  <tr>
    <td class="tg-mft0" colspan="4">동작범위 횡단 면적</td>
    <td class="tg-9wq8">3.45m²</td>
    <td class="tg-9wq8" colspan="2">1.98m²</td>
    <td class="tg-9wq8">1.46m²</td>
  </tr>
</tbody>
</table>

1)	ISO 9283을 준거합니다.
2)	고온 환경 사용 및 가동 조건이 가혹할 경우 당사에 기술 검토 요청해주십시오. 
# 2.4. 본체 외형 치수 및 동작 영역



![](../_assets/그림_2.3_로봇_본체_외형_치수_및_동작_영역.png)

그림 2.3 로봇 본체 외형 치수 및 동작 영역 (HH4L)


![](../_assets/그림_2.4_로봇_본체_외형_치수_및_동작_영역.png)


그림 2.4  로봇 본체 외형 치수 및 동작 영역 (HH7)

![](../_assets/그림_2.5_로봇_본체_외형_치수_및_동작_영역.png)


그림 2.5 로봇 본체 외형 치수 및 동작 영역 (HH8]

![](../_assets/그림_2.6_로봇_본체_외형_치수_및_동작_영역.png)


그림 2.6 로봇 본체 외형 치수 및 동작 영역 (HH7E)# 2.5. 동작 축 명칭

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-bgl2{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-jnja{background-color:#ccf1bc;text-align:center;color:#000000; font-weight:bold;vertical-align:top}
</style>
<table class="tg">
<caption> 표 2-2 각 축의 회전 방향</caption>  
<thead>
  <tr>
    <th class="tg-bgl2">축 명칭</th>
    <th class="tg-bgl2">동작</th>
    <th class="tg-bgl2" colspan="2">티치팬던트 버튼</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-jnja">S</td>
    <td class="tg-baqh">선회</td>
    <td class="tg-baqh">좌(S+)</td>
    <td class="tg-baqh">우(S-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">H</td>
    <td class="tg-baqh">전후</td>
    <td class="tg-baqh">후(H+)</td>
    <td class="tg-baqh">전(H-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">V</td>
    <td class="tg-baqh">상하</td>
    <td class="tg-baqh">상(V+)</td>
    <td class="tg-baqh">하(V-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">R2</td>
    <td class="tg-baqh">회전 2</td>
    <td class="tg-baqh">정(R2+)</td>
    <td class="tg-baqh">역(R2-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">B</td>
    <td class="tg-baqh">구부림</td>
    <td class="tg-baqh">정(B+)</td>
    <td class="tg-baqh">역(B-)</td>
  </tr>
  <tr>
    <td class="tg-jnja">R1</td>
    <td class="tg-baqh">회전 1</td>
    <td class="tg-baqh">정(R1+)</td>
    <td class="tg-baqh">역(R1-)</td>
  </tr>
</tbody>
</table>
<br><br>

![](../_assets/그림_2.5_본체_외관_및_동작_축.png)

그림 2.7 본체 외관 및 동작 축
# 2.6. 손목축 취부면 상세도


손목축 선단부 프렌지(flange)에 작업용 툴 부착 시 볼트는 모델 별 해당 볼트를 이용하십시오.


![](../_assets/그림_2.6_손목축_취부면_상세도.png)

그림 2.8 손목축 취부면 상세도 (HH4L/HH7/HH8)

![](../_assets/그림_2.6_손목축_취부면_상세도2.png)

그림 2.9 손목축 취부면 상세도 (HH7E)# 2.7. 응용 부품 취부면 상세도

로봇 본체에 주변기기 및 브라켓을 부착하기 위한 Tap이 가공 되어 있습니다. 



![](../_assets/그림_2.10_응용부품_취부면_상세도.png)

그림 2.10 응용 부품 취부면 상세도 
# 2.8. 어플리케이션(APPLICATION)용 배선 및 배관도


로봇 본체에는 부가 장비를 연결하기 위한 콘넥터와 공기 유닛이 있습니다.

다음 그림들은 사용자 응용 콘넥터를 표시합니다.


![](../../_assets/그림_2.9_어플리케이션용_배선_및_배관도.png)
![](../../_assets/그림_2.11_어플리케이션용_배선_및_배관도.png)

그림 2.11 어플리케이션용 배선 및 배관도

<br>

# 2.8.1. 어플리케이션용 배선 커넥터 상세도


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-baqh"><img src="../../_assets/그림_2.11_어플리케이션_커넥터_상세.png">
    </img></td>
    <td class="tg-baqh">< ASR 1 ><br>
    · 케이블: 0.2sq * 10P<br>
    · 커넥터 형식 : LF13WBRB -20S(HIROSE) (M)<br>
    · 상대 커넥터 : LF13WBLP -20PA(HIROSE) (F/ELBOW TYPE)<br>
                 : LF13WBP -20P(HIROSE) (F/STRAIGHT TYPE)
  </td>
  </tr>
</thead>
</table>


그림 2.12 어플리케이션용 커넥터 상세도# 2.9. 동작 범위 제한

로봇 설치 시, 전체 동작범위 안에서 특정범위로 제한할 수 있습니다. 

다음과 같은 환경에서 동작범위의 제한은 유용합니다.

*	로봇 동작 시 동작영역을 제한하자고 할 때
*   주변기기와 충돌이 발생할 수 있을 때
*   응용케이블이나 호스의 길이가 제한적일 때


로봇이 동작영역을 벗어나지 않게 하는 방법에는 2가지가 있습니다. 즉,

*	소프트웨어 리밋(전축 적용)
*	기계적 스토퍼(Stopper)(1~3축)


<img src="../../_assets/작은주의표시.png"><b>[주의]</b><br>
기계적 스톱퍼는 물리적인 장치입니다. 로봇은 기계적 스톱퍼를 넘어서는 안됩니다. 1~3축의 기계적 스톱퍼는 고정되어있습니다. 4~6축은 소프트웨어 리밋 만 적용되어 있습니다.

기계적 스톱퍼는 한 번 충돌하면 변형되며, 강도를 보장할 수 없습니다. 따라서, 반드시 교체해주십시오.
# 2.9.1. 1축(S축)

1축 스토퍼 블록(Stopper Block)과 스토퍼(Stopper)에 심한 충격이 가해져 변형되었다면, 반드시 교체해야 합니다.# 3. 취급 주의사항



# 3.1. 각 부위 명칭

본체 각부의 명칭을 그림 3.1 및 표 3-1에 표시합니다. 


![](../_assets/그림_3.1_본체_각_부위_명칭.png)

그림 3.1 본체 각 부위 명칭

<br>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;margin-left:auto;margin-right:auto;}
.tg caption{caption-side: top;text-align: left;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-bgl2{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-bav5{background-color:#f8f8be;text-align:center;color:#000000; font-weight:bold;vertical-align:top}
</style>
<table class="tg">
<caption> 표 3-1 본체 각 부위 명칭</caption>  
<thead>
  <tr>
    <th class="tg-bgl2">No.</th>
    <th class="tg-bgl2">각 부 명칭</th>
    <th class="tg-bgl2">No.</th>
    <th class="tg-bav5">각 부 명칭</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">베이스 바디(BASE BODY)</td>
    <td class="tg-baqh">8</td>
    <td class="tg-baqh">S축 모터</td>
  </tr>
  <tr>
    <td class="tg-baqh">2</td>
    <td class="tg-baqh">하부 프레임(LOWER FRAME)</td>
    <td class="tg-baqh">9</td>
    <td class="tg-baqh">H축 모터</td>
  </tr>
  <tr>
    <td class="tg-baqh">3</td>
    <td class="tg-baqh">상부 프레임(UPPER FRAME)</td>
    <td class="tg-baqh">10</td>
    <td class="tg-baqh">V축 모터</td>
  </tr>
  <tr>
    <td class="tg-baqh">4</td>
    <td class="tg-baqh">암 프레임(ARM FRAME)</td>
    <td class="tg-baqh">11</td>
    <td class="tg-baqh">R2축 모터</td>
  </tr>
  <tr>
    <td class="tg-baqh">5</td>
    <td class="tg-baqh">암 파이프(ARM PIPE)</td>
    <td class="tg-baqh">12</td>
    <td class="tg-baqh">B축 모터</td>
  </tr>
  <tr>
    <td class="tg-baqh">6</td>
    <td class="tg-baqh">손목부(WRIST BODY)</td>
    <td class="tg-baqh">13</td>
    <td class="tg-baqh">R1축 모터</td>
  </tr>
  <tr>
    <td class="tg-baqh">7</td>
    <td class="tg-baqh">손목부(WRIST HOLDER)</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
  </tr>
</tbody>
</table>
# 3.2. 안전 명판 위치

안전사고를 예방하기 위해 로봇 본체에는 [그림3.2]와 같은 안전 명판이 붙어 있습니다. 불필요하게 교체하거나 제거하지 마십시오.


![](../_assets/그림_3.2.1_안전명판위치1.png)

![](../_assets/그림_3.2.1_안전명판위치2.png)

그림 3.2 안전 명판 위치 (CI변경)# 3.3. 운송 방법
# 3.3.1. 크레인 이용


![](../../_assets/그림_3.5_운반방법_크레인이용.png)

그림 3.3 운송 방법 : 크레인 이용 (HH7, HH7E)

<br>

![](../../_assets/그림_3.6_운반방법_크레인이용.png)
![](../../_assets/그림_3.6_운반방법_크레인이용1.png)

그림 3.4 운송 방법 : 크레인 이용 (HH8, HH4L)

<br>


![](../../_assets/작은주의표시.png)
*	절대로 로봇 본체 아래로 걸어 다니지 마십시오.
*	그림과 같은 로봇 자세를 취합니다.
*	LIFTING BRACKET(OPTION)을 설치합니다. (4-M6x12)
*	LIFTING BRACKET HOLE에 와이어 로프 또는 후크를 체결합니다.
*	로봇 본체의 손상 방지용 보호 호스(50㎝)를 부착합니다.
*	리프팅 작업 시 안전 규정을 준수합니다.
*	본체의 무게: 47.5kg[HH8], 48.5kg[HH7], 49.2kg[HH4L], 49kg[HH7E]
*	최소 크레인 용량: 0.2톤


![](../../_assets/작은주의표시.png)
※ 로봇 본체와 와이어 로프의 접촉 부위에는 로봇 도장부의 손상을 방지하기 위해 와이어에 보호 호스를 끼운 후 사용하여 주십시오. 보호 호스를 사용할 부위는 그림을 참조하여 주십시오.# 3.3.2. 지게차 이용



![](../../_assets/그림_3.7_운반방법_지게차이용.png)

그림 3.5 운송 방법 : 지게차 이용

<br>

로봇 본체의 운반 시 지게차를 이용할 수 있습니다.

안전을 위해 다음의 절차를 준수해 주십시오.

<ol style="list-style-type:disc" start="1">
		<li>그림을 참조하여 기본 자세를 취하게 하십시오.</li>
        <li>로봇을 팔레트에 볼트로 고정하고 팔레트에 지게차의 포크를 밀어 넣어 운반하여 주십시오. 팔레트는 강도상 충분히 견딜 수 있는 것이어야 합니다.
        </li>
        <li>저속으로 운반하십시오.</li>
        <li>안전 규정을 준수하십시오.</li>
</ol><br>

<img src="../../_assets/작은주의표시.png"> <b>주의 사항</b>

<ol style="list-style-type:disc" start="1">
		<li>운반작업도중 로봇본체에 기대지 마십시오.</li>
        <li>상, 하차 작업 시 로봇본체가 바닥에 충돌하지 않도록 확인을 요합니다.</li>
        <li>지게차 작업 시 안전수칙을 준수하여 작업 하십시오.</li>
</ol><br># 3.4. 설치 방법

<img src="../../_assets/작은주의표시.png"><b> 주의:</b><br>
포장을 해체하고 로봇을 설치하기 전에 반드시 안전 규정이나 관련 지시 사항을 주의 깊게 읽어주십시오. 

<img src="../../_assets/작은주의표시.png"><b> 경고:</b><br>
설치는 반드시 설치 전문가가 하여야 하며, 해당 국가나 지역의 관련 규정을 준수하여야 합니다.

로봇 포장을 해체할 때, 운반이나 포장 해체 시 손상을 입지 않았는지 확인하십시오. 또한, 로봇 본체의 설치방법과 기초는 로봇 기능을 유지하는데 있어 매우 중요하기 때문에 아래의 사항을 엄수하여 주십시오.
# 3.4.1. 사용 조건

<ol style="list-style-type:decimal" start="1">
		<li>주변온도는 0℃ ~ 45℃ 범위 내에 있을 것. </li>
        <li>주변습도는 20 ~ 85% RH로써 결로현상이 없을 것.</li>
        <li>먼지, 기름, 수분 등이 적을 것.</li>
        <li>인화성, 부식성 액체 및 GAS가 존재하지 않을 것.</li>
        <li>큰 충격 및 진동 등을 받지 않을 것.</li>
        <li>큰 전기적 노이즈 발생원이 가까이 없을 것.</li>
        <li>로봇을 바로 설치하지 않을 경우, 주의 온도 -15℃∼40℃의 건조한 장소에 보관할 것.</li>
</ol># 3.4.2. 로봇 본체의 설치

로봇을 설치할 기초 바닥의 강성은 로봇의 동적 영향을 최소화 할 수 있도록 바닥 면의 콘크리트 두께가 200mm 이상으로 시공되어야 하며, 설치 시 콘크리트 바닥 면의 요철 및 균열 등을 보수하고 M20 앵커(Anchor)볼트로 마운팅 플레이트를 고정하여 주십시오. 그리고 바닥 면의 콘크리트 두께가 200mm 이하이면 독립된 기초공사가 필요하므로 사전에 검토 후 시공 바랍니다. 

로봇 본체를 마운팅 플레이트에 위치시킨 후 4개의 M10 볼트로 견고히 체결합니다. 

※주의사항 : 본체 설치 시 2개의 Ø6위치 결정용 PIN을 적용하여 주십시오.

*	볼트: M10x35 (12.9) SOCKET HEAD BOLT
*	와셔: 스프링와셔, 평와셔
*	체결 토크: 680 kgfcm
 
# 3.4.3. 설치면의 정도

로봇 본체의 플레이트 취부면 4곳의 설치면의 평면도 및 상호 높이 오차는 지정 사양을 만족하여야 하며, 필요에 따라 Shim을 사용하십시오. 

*	주의사항

    (1)	마운팅 플레이트(Plate) 4매의 평면도는 0.2 mm 이내로 하여 주십시오.

    (2)	플레이트 취부면 4매의 상호 높이 오차는 0.2mm (±0.1 mm) 이내로 하여 주십시오.


![](../../_assets/그림_3.6_로봇_설치면_정도.png)

그림 3.6 로봇 설치면 정도# 3.4.4. 비상 정지 시간 및 거리 

표준 부하를 장착하고 축 별 (S축, H축, V축) 최고 속도 동작 중 비상 정지에 대한 응답 시간과 거리를 측정하면 다음과 같습니다.

*	HH4L<p>
최대 시간	: 0.43 seconds<br>
최대 이동 거리 : 142.5 cm<br>

*	HH7<p>
최대 시간	: 0.43 seconds<br>
최대 이동 거리 : 163.3 cm<br>

*	HH8<p>
최대 시간 : 0.47 seconds<br>
최대 이동 거리 : 146.3 cm<br>

*	HH7E<p>
최대 시간	: 0.45 seconds<br>
최대 이동 거리 : 176 cm
# 3.4.5. 설치면 치수

로봇본체의 취부는 선회 베이스의 바닥 면을 고정하여 주십시오.
치수는 [그림 3.7]을 참조하여 주십시오.


※ 주의사항 : 본체 설치 시 2개의 Ø6위치 결정용 PIN을 적용하여 주십시오.



![](../../_assets/그림_3.7_로봇_설치면_치수.png)

그림 3.7 로봇 본체 설치 치수# 3.5. 손목축 부하 허용치



# 3.5.1. 허용 부하 토크, 허용 관성 모멘트 산정

로봇의 손목축 선단에 부착될 부하는 허용 중량, 허용 부하토크, 허용 관성 모멘트에 의해서 규제 됩니다. 부하 토크 및 관성 모멘트 계산 시 사용되는 좌표계의 방향은 로봇 베이스 좌표계의 방향과 동일합니다. R2축에 대한 검토는 B축과 동일한 방식으로 이루어집니다.


*	Step 1

    B축 회전 중심에서의 무게 중심의 위치를 계산 (L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>.)

    L<sub>x</sub>: X축 방향 무게중심 위치

    L<sub>y</sub>: Y축 방향 무게중심 위치

    L<sub>z</sub>: Z축 방향 무게중심 위치



*	Step 2

    B축, R1축에서부터 무게 중심까지 거리 계산

    ![](../../_assets/3.6.1_수식1.png)

    L<sub>B</sub> : B축 회전 중심에서 무게중심까지의 거리

    L<sub>R1</sub> : R1축 회전 중심에서 무게중심까지의 거리



*	Step 3

    계산된 거리로부터 부하 토크를 계산

    ![](../../_assets/3.6.1_수식2.png)


*	Step 4

    허용 부하 토크 표를 기준으로 Step 3에서 계산된 부하 토크가 제한치 이하인지 확인

 
* Note : 부하 질량이 하기의 토크 선도 상의 질량과 유사할 경우, 부하 토크 검증은 Step 3,4 대신 Step 2에서 계산된 거리가 토크 선도 내에 분포하는지 체크함으로 대체할 수 있습니다. 토크 선도 내에 위치할 경우, 계산된 부하 토크가 허용 부하 토크보다 작은 것이고, 토크 선도 밖에 위치할 경우, 계산된 부하 토크는 허용 부하 토크보다 큰 것입니다.


<br></br>

![](../../_assets/작은주의표시.png) <b>허용 부하 토크</b>

표 3-2 허용 부하 토크
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm" rowspan="2">로봇모델</th>
    <th class="tg-yhpm" colspan="3">허용 부하 토크</th>
  </tr>
  <tr>
    <th class="tg-yhpm">R2축 회전</th>
    <th class="tg-yhpm">B축 회전</th>
    <th class="tg-yhpm">R1축 회전</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">HH4L</td>
    <td class="tg-nrix">6 Nm (0.61kgf·m) 이내</td>
    <td class="tg-nrix">6 Nm (0.61kgf·m) 이내</td>
    <td class="tg-nrix">3 Nm (0.30kgf·m) 이내</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7</td>
    <td class="tg-nrix" rowspan="3">17 Nm (1.73kgf·m) 이내</td>
    <td class="tg-nrix" rowspan="3">17 Nm (1.73kgf·m) 이내</td>
    <td class="tg-nrix" rowspan="3">10N·m (1.02kgf·m) 이내</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7E</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH8</td>
  </tr>
</tbody>
</table>

![](../../_assets/작은주의표시.png) <b>허용 관성모멘트</b>

표 3-3 허용 관성 모멘트
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm" rowspan="2">로봇모델</th>
    <th class="tg-yhpm" colspan="3">허용 관성 모멘트</th>
  </tr>
  <tr>
    <th class="tg-yhpm">R2축 회전</th>
    <th class="tg-yhpm">B축 회전</th>
    <th class="tg-yhpm">R1축 회전</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">HH4L</td>
    <td class="tg-nrix">0.12 kgm²</td>
    <td class="tg-nrix">0.12 kgm²</td>
    <td class="tg-nrix">0.03 kgm²</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7</td>
    <td class="tg-nrix" rowspan="3">0.5 kgm²</td>
    <td class="tg-nrix" rowspan="3">0.5 kgm²</td>
    <td class="tg-nrix" rowspan="3">0.2 kgm²</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH7E</td>
  </tr>
  <tr>
    <td class="tg-wa1i">HH8</td>
  </tr>
</tbody>
</table>

[표 3-2 ~ 3-3]을 참고하여 부하가 허용조건을 초과하지 않도록 사용하여 주십시오.

*	Step 1

    각 손목축 중심에서 부하의 관성 모멘트 값을 계산 (J<sub>a4</sub>, J<sub>a5</sub>, J<sub>a6</sub>)

    J<sub>a4</sub> - R2축 회전 중심에서의 관성 모멘트

    J<sub>a5</sub> - B축 회전 중심에서의 관성 모멘트

    J<sub>a6</sub> - R1축 회전중심에서의 관성 모멘트

*	Step 2

    허용 관성 모멘트 표를 기준으로 관성 모멘트 값이 제한치 이하인지 확인# 3.5.2. 허용 토크, 관성 모멘트 계산 예 (HA006B Case)

[그림 3.7, 3.8]은취부되는 부하가 질점에 있다고 생각되는 경우에 그 질점이 위치할 수 있는 곳의 가능한 범위를 표시합니다. 그렇지만, 실제 부하(End Effector)가 질점에 있는 경우는 거의 없으므로 각 축의 관성모멘트를 구하여 평가하여 주십시오. 취부되는 부하를 질점으로 생각할 경우의 예를 들어보면,

<b>(예)로봇 형식은【HA006B】이고 취부되는 부하의 중량이5.74Kg일 때</b>

<br>

![](../../_assets/그림_3.8_2차원부하모델.png)

그림 3.8 2차원 부하 모델

<br>

M - 부하 중량

J<sub>xx</sub> - 부하 무게중심에서 X축 방향의 관성 모멘트

J<sub>yy</sub> - 부하 무게중심에서 Y축 방향의 관성 모멘트

J<sub>zz</sub> - 부하 무게중심에서 Z축 방향의 관성 모멘트

J<sub>a4</sub> - R2축 회전 중심에서의 관성 모멘트

J<sub>a5</sub> - B축 회전 중심에서의 관성 모멘트

J<sub>a6</sub> - R1축 회전중심에서의 관성 모멘트


 
<br></br>
☞ 부하조건: 가로 100mm, 세로 100mm, 두께 200mm 의 알루미늄 블록(Mass 5.74kg)


①	허용 토크 제한

B축 기준 무게 중심 위치 L<sub>X</sub> = 155mm, L<sub>Y</sub> = 0mm, L<sub>Z</sub> = -25.5mm

토크맵에서 B, R1축 거리 제한을 적용하면 아래와 같습니다.

![](../../_assets/3.6.2_수식.png)

②	허용 관성 모멘트 제한

무게중심에서 부하의 관성 모멘트 J<sub>xx</sub>=0.024kgm2, J<sub>yy</sub>=0.01kgm2, J<sub>zz</sub>=0.024kgm2

![](../../_assets/3.6.2_수식2.png)


③	결론 : 중량, 토크, 관성모멘트 조건 모두 제한 조건을 만족하므로 안전합니다.

<br>

*	R1축 중심에서의 허용중심위치

    ①	허용토크에서 보았을 때의 허용중심위치

    L<sub>R1</sub> ≤ (허용토크) / (부하중량)

    L<sub>R1</sub> = 5.9 N·m / (5.74Kg×9.8 m/s<sup>2</sup>) = 0.104 m


    ②	허용관성모멘트에서 보았을 때의 허용중심위치

    L<sub>R1</sub> ≤ (허용관성모멘트/부하중량)<sup>1/2</sup>

    = (0.06 kg·m2 / 5.74kg)<sup>1/2</sup> = 0.102 m

    이상의 결과에서 R1축 중심에서의 거리는 허용 토크에 의해 규제되고, 0.102 m 이내가 됩니다.

<br>

*	B축 중심에서의 허용중심위치

    (본 로봇은 B축 중심이 같은 축 상에 있고, 또한 허용 부하 토크, 허용 관성 모멘트도 B축, R2축이 같은 값입니다. 따라서 B축의 허용조건을 만족하면, R2축의 허용조건도 만족하게 됩니다.)

    ①	허용토크에서 보았을 때의 허용중심위치

    L<sub>B</sub> ≤ (허용토크) / (부하중량)

    L<sub>B</sub> = 9.8 N·m / (5.74Kg×9.8 m/s<sup>2</sup>) = 0.174 m


    ②	허용관성모멘트에서 보았을 때의 허용중심위치

    L<sub>B</sub> ≤ (허용관성모멘트/부하중량)<sup>1/2</sup> 

    = (0.27 kg·m2 / 5.74kg)<sup>1/2</sup> = 0.217 m

    이상의 결과에서 B축 중심에서의 거리는 허용 토크에 의해 규제되고, 0.174m 이내가 됩니다.

<br>

* <b>Torque Map</b>

![](../../_assets/그림_3.9_손목축_토크_선도.png)

그림 3.9 손목축 토크 선도 (HH4L)                       

![](../../_assets/그림_3.10_손목축_토크_선도.png)

그림 3.10손목축 토크 선도 (HH7)

![](../../_assets/그림_3.11_손목축_토크_선도.png)

그림 3.11 손목축 토크 선도 (HH8)

![](../../_assets/그림_3.12_손목축_토크_선도.png)

그림 3.12 손목축 토크 선도 (HH7E)# 4. 점검

로봇의 성능을 장기간 유지 시키기 위해 필요한 정기점검 및 분해조정 등에 대해서 설명합니다.# 4.1. 점검 계획

점검은 로봇의 장기 가동 시, 고성능을 유지하기 위하여 반드시 필요합니다.
점검은 일상점검, 정기점검이 있으며, [표 4-1]에 기본적 점검 주기를 표시하고 있으므로 점검 담당자는 점검주기에 따라 반드시 실시하여 주십시오.

35,000 가동시간마다 오버 홀(Overhaul)을 실시하여 주십시오. 

점검주기는 스폿(SPOT) 용접용으로 검토되었으며, 핸들링 작업과 같은 고정도 작업에 사용시는 [표4-1] 주기의 약1/2의 주기로 점검하길 권장합니다. 점검 및 조정 방법이 이해하기 어려울 경우, 당사 A/S 센터(고객지원과)로 문의하십시오.


<br>
표 4-1 점검 계획 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">일상점검</th>
    <th class="tg-wa1i">일상</th>
    <th class="tg-nrix">본체, 모터, 감속기</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-jafi" rowspan="3">정기점검</td>
    <td class="tg-wa1i">3개월</td>
    <td class="tg-nrix">배선, 볼트, 감속기</td>
  </tr>
   <tr>
    <td class="tg-wa1i">1년</td>
    <td class="tg-nrix">브레이크</td>
  </tr>
</tbody>
</table># 4.2. 점검항목과 주기

표 4-2 점검항목과 주기

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi" rowspan="2">No</th>
    <th class="tg-jafi" colspan="3">점검주기</th>
    <th class="tg-jafi" rowspan="2">점검항목</th>
    <th class="tg-jafi" rowspan="2">점검방법</th>
    <th class="tg-jafi" rowspan="2">기준</th>
    <th class="tg-jafi" rowspan="2">비고</th>
  </tr>
  <tr>
    <th class="tg-jafi">일상</th>
    <th class="tg-jafi">3개월</th>
    <th class="tg-jafi">1년</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i" colspan="8">로봇 본체 및 각축 공통</td>
  </tr>
  <tr>
    <td class="tg-wa1i">1</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">본체 청소</td>
    <td class="tg-nrix">오물 등의 육안확인</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">2</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">배선 점검</td>
    <td class="tg-nrix">케이블 손상 육안확인<br>케이블 고정 브라켓 체결 볼트<br>페인트 마킹 육안확인<br>케이블 커버 손상 육안확인
</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">3</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">주요볼트</td>
    <td class="tg-nrix">페인트 마킹 육안확인</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">4</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">모터</td>
    <td class="tg-nrix">이상발열 확인<br>이음발생 확인</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">모터</td>
  </tr>
  <tr>
    <td class="tg-wa1i">5</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">브레이크</td>
    <td class="tg-nrix">브레이크 해제스위치<br>ON, OFF에서 작동확인<br>
    주)브레이크 해제 스위치 ON에서,<br>암 또는 동작 축이 추락하기 때문에 확인 시는 1초 내에 OFF하십시오.</td>
    <td class="tg-nrix">브레이크 해제 스위치 OFF 상태에서<br>암 또는 엔드이펙트는 추락하지 않습니다</td>
    <td class="tg-nrix">브레이크</td>
  </tr>
  <tr>
    <td class="tg-wa1i" colspan="8">S, H, V축</td>
  </tr>
  <tr>
    <td class="tg-wa1i">6</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">이음발생 확인<br>진동발생 확인</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
<tr>
    <td class="tg-wa1i" colspan="8">R2, B, R1축</td>
  </tr>
  <tr>
    <td class="tg-wa1i">7</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">이음발생 확인<br>진동발생 확인</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">8</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">엔드 이펙트 체결볼트</td>
    <td class="tg-nrix">페인트 마킹 육안확인</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">9</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">유격</td>
    <td class="tg-nrix">각축을 정/역방향으로 회전하여<br>유격의 유무 확인</td>
    <td class="tg-nrix">손으로 유격을 느낄 수 없을 것</td>
    <td class="tg-nrix"></td>
  </tr>
</tbody>
</table>


<br>

*	만약 로봇이 악조건(예를 들면, 스폿 용접, 그라인딩 등)에서 사용되고 있다면 로봇 시스템의 성능 확보를 위해 점검 주기를 더욱 짧게 가져가십시오.

*	보이는 모든 케이블을 점검하시고, 손상된 케이블은 교체하십시오.

*	기계적 Bumper가 변형 및 손상된 부분이 없는지 확인하십시오. Bumper가 손상되었거나, Dog가 구부려졌다면 즉시 교체 하십시오.

*	[그림 4.1]의 주요 볼트의 체결 토크를 확인하십시오.

*	동력 전달 장치(모터, 감속기 등)의 이상 유무 확인을 위해, 자동 또는 티칭 모드에서 이상음을 확인하십시오. 

 


# 4.3. 주요 외부 볼트 점검

권장볼트 토크는 [그림 4.1]에 표시되어 있습니다.

반드시 토크 렌치를 사용하여 적정 토크로 체결한 후 페인트 마킹을 하여 주십시오.



표 4-3 주요 볼트 점검 부위

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-t1e1{background-color:#ccf1bc;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-1e26{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1e26">No.</th>
    <th class="tg-1e26">점검 부위</th>
    <th class="tg-1e26">No.</th>
    <th class="tg-1e26">점검 부위</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-t1e1">1</td>
    <td class="tg-baqh">S축 모터 취부볼트</td>
    <td class="tg-t1e1">7</td>
    <td class="tg-baqh">END EFFECTOR 취부볼트</td>
  </tr>
  <tr>
    <td class="tg-t1e1">2</td>
    <td class="tg-baqh">V축 모터 취부볼트</td>
    <td class="tg-t1e1">8</td>
    <td class="tg-baqh">R1축 MOTOR BASE</td>
  </tr>
  <tr>
    <td class="tg-t1e1">3</td>
    <td class="tg-baqh">R2축 모터 취부볼트</td>
    <td class="tg-t1e1">9</td>
    <td class="tg-baqh">B축 모터 취부볼트</td>
  </tr>
    <tr>
    <td class="tg-t1e1">4</td>
    <td class="tg-baqh">R2축 MOTOR BASE</td>
    <td class="tg-t1e1">10</td>
    <td class="tg-baqh">2암 고정용(HH4L, HH7용)</td>
  </tr>
  <tr>
    <td class="tg-t1e1">5</td>
    <td class="tg-baqh">B축 MOTOR BASE</td>
    <td class="tg-t1e1">11</td>
    <td class="tg-baqh">V축 MOTOR BASE</td>
  </tr>
  <tr>
    <td class="tg-t1e1">6</td>
    <td class="tg-baqh">R1축 모터 취부볼트</td>
    <td class="tg-t1e1">12</td>
    <td class="tg-baqh">H축 모터 취부볼트</td>
  </tr>
</tbody>
</table>



![](../_assets/그림_4.1_주요_볼트_점검_부위.png)

그림 4.1 주요 볼트 점검 부위 (HH4L/HH7/HH8)

![](../_assets/그림_4.2_주요_볼트_점검_부위.png)

그림 4.2 주요 볼트 점검 부위 (HH7E)
# 4.4. 본체 내 배선 점검

로봇본체의 기내배선은 굴곡성에 견딜 수 있는 것을 사용하고 있으나, 배선손상 및 파손 등으로 단선 또는 단락 되는 경우, 로봇 동작에 문제가 발생하므로 일상점검을 확실히 하여주십시오. 

그리고 아래의 안전점검조건에 의한 가동범위 내에서 작업을 시행 할 경우는 사전점검을 반드시 하여 주십시오.
# 4.4.1. 안전 점검 조건

사용자가 산업용 로봇의 가동 범위 내에서 로봇을 티칭 등(산업용 로봇의 구동원을 차단시키는 것은 제외) 의 작업을 할 때, 그 작업을 시작하기 전에 다음사항을 점검하고 이상을 확인했을 때에는 즉시 수정하고 그 외 필요한 조치를 취하지 않으면 안됩니다.

*	외부 전원의 피복과 Cable의 손상 유·무 확인
*	로봇 본체의 동작이상 유·무 확인
*	비상 정지 기능의 확인
# 4.4.2. 점검 부위



![](../../_assets/그림_4.3_케이블_점검_부위.png)


그림 4.3 케이블 점검 부위 # 4.5. 타이밍 벨트 점검

구동부에 타이밍 벨트를 적용한 부분이 있습니다.

타이밍 벨트 구동부는 매 1,500 시간 경과 후 또는 진동/소음이 발생할 경우, 벨트 장력을 확인하십시오. 타이밍 벨트의 장력이 적절하지 않을 경우 로봇 성능에 중대한 악 영향을 미칠 수 있습니다.


<ol style="list-style-type:decimal" start="1">
<li>로봇을 수동 조작하여 기본 자세로 위치 시킵니다. (2축 : 90˚, 나머지 축 : 0˚)<br>-각 축을 수동 조작하여 타이밍 벨트의 장력이 균일해질수 있도록 해주십시오.
        </li><br>
<li>전원을 끕니다.
    </li><br>
<li>점검부 Cover를 분해합니다.

![](../_assets/그림_4.4_b축_타이밍벨트_장력체크부위.png)

그림 4.4 축별 타이밍 벨트 점검 위치

</li><br>
    <li>타이밍 벨트를 장력계로 확인해 주십시오.  
</li><br>
    <li>벨트 장력이 적절하지 않을 경우 조정해주십시오.<br>
-장력은 벨트의 중앙 지점에서 측정해주십시오.<p>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-nrix">모델</th>
    <th class="tg-nrix">구분</th>
    <th class="tg-nrix">장력(N)</th>
    <th class="tg-nrix">Span(mm)</th>
    <th class="tg-nrix">Mass(g/m)</th>
    <th class="tg-nrix">Width(mm/R)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix" rowspan="3">HH4L/HH7/HH8/HH7E</td>
    <td class="tg-nrix">H축 (2축)</td>
    <td class="tg-nrix">55~65</td>
    <td class="tg-nrix">155</td>
    <td class="tg-nrix">4</td>
    <td class="tg-nrix">9</td>
  </tr>
  <tr>
    <td class="tg-nrix">V축 (3축)</td>
    <td class="tg-nrix">55~65</td>
    <td class="tg-nrix">195</td>
    <td class="tg-nrix">4</td>
    <td class="tg-nrix">9</td>
  </tr>
  <tr>
    <td class="tg-nrix">R2축 (4축)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">49</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="2">HH4L/HH7/HH8</td>
    <td class="tg-nrix">B축 (5축)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">183</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix">R1축 (6축)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">117</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="2">HH7E</td>
    <td class="tg-nrix">B축 (5축)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">184.5</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
  <tr>
    <td class="tg-nrix">R1축 (6축)</td>
    <td class="tg-nrix">29~36</td>
    <td class="tg-nrix">120</td>
    <td class="tg-nrix">2.5</td>
    <td class="tg-nrix">6</td>
  </tr>
</tbody>
</table>

![](../_assets/그림_4.5_hv축_타이밍벨트_장력체크부위.png)

그림 4.5 H/V축 타이밍 벨트 장력 체크 위치

![](../_assets/그림_4.6_r2br1축_타이밍벨트_장력체크부위.png)

그림 4.6 R2/B/R1축 타이밍 벨트 장력 체크 위치
</li><br>
    <li>그림 4.1과 4.2의 체결토크를 참조하여 모터 플랜지를 Loctite 243을 도포한 볼트로 체결합니다. 
</li><br>
    <li>점검부 Cover를 조립합니다.
</li><br>
    <li>전원을 켭니다. 
</li>
</ol>

# 5. 보수
# 5.1. 배터리 교환


각 축의 위치 데이터는 백업용 배터리로 보존됩니다. 배터리는 매 2년마다 반드시 교체해야 합니다. 배터리 교환 시 다음 절차를 따르십시오.


<ol style="list-style-type:decimal" start="1">
    <li>
제어기 전원 ON 상태에서 비상정지 버튼을 눌러 주십시오.
<p>
<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">전원을 끄고 배터리를 교환하면, 현재의 모든 위치 데이터를 잃어버리게 됩니다. 따라서 원점 설정을 다시 해야 합니다.</td>
  </tr>
</thead>
</table>  
</blockquote>
    </li><br>
    <li>
각 축 별 배터리 위치의 커버를 분리해 주십시오.
    </li><br>
    <li>
헌 배터리를 빼내어 주십시오.
    </li><br>
    <li>
새 배터리를 조립하십시오. 조립방향에 주의해 주십시오.
<p>

* 배터리 제조사 및 사양<br>

  1)	MAXWELL : ER6C<br>
  2)	TOSHIBA  : ER6V-T1

</li><br>
<li>
커버를 원래대로 설치해 주십시오.
</li>
</ol>


![](../../_assets/그림_5.1_배터리_교환위치.png)

그림 5.1 배터리 교환 위치

<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
    <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4">
    -	배터리를 버리지 마십시오. 해당 나라의 법이나 규율에 따라 산업용 폐기물로 취급하십시오.<p>
-	배터리를 충전하지 마십시오. 폭발이나 과열을 일으킬 수 있습니다.<p>
-	지정한 사양 이외의 배터리를 사용하지 마십시오.<p>
-	지정한 배터리로만 교환하십시오.<p> 
-	배터리의 음/양극을 쇼트 시키지 마십시오.<p>
-	배터리를 화염이나 고온에 노출시키지 마십시오. 
</td>
  </tr>
</thead>
</table>  
</blockquote>
# 5.1.1. 배터리 보관시의 주의 사항

<ol style="list-style-type:decimal" start="1">
    <li>
고온·고습 장소에는 보관하지 마시고, 결로가 없도록 통풍이 좋은 장소에 보관하십시오. 
</li><br>
    <li>
상온(20±15℃)으로 온도변화가 적고, 상대습도70% 이하의 장소에 보관해 주십시오. 
</li><br>
    <li> 
배터리의 보관은 6개월 기준으로 하고, 선입선출이 되도록 관리해 주십시오.
</li>
</ol>
# 5.2. 본체 내 배선 교환 

본체 배선의 교환주기는 다음 항목의 영향을 받습니다.

-	연속 가동
-	가동 속도
-	주위 환경

매 3개월 마다 주기적으로 점검하시고, 케이블이나 케이블 보호용 스프링에 손상이 없는지 확인하십시오. 손상이 발견되면 교체해야 합니다. 

사용 조건에 관계없이 매 16,000시간 마다 케이블을 교환하여 주십시오.



<blockquote>
<table border="0">
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 80 height = 80>
    </div>
    </td>
    <td colspan="4">
   -	배선에는 내굴곡성이 있는 것을 사용하고 있으므로 지정한 전선 이외는 절대로 사용하지 않도록 하십시오.<p>
   -	배선의 교환은 유니트(Unit) 단위로 하십시오.<p>
   -	케이블, 보호스프링, 호스 등에서 외상, 손상 등이 있는 것은 트러블의 원인이 되므로 사용하지 않도록 하십시오.<p>
   -	본체 내 배선을 구입하는 경우는 배선 형식을 당사 서비스 부문으로 문의해 주십시오.<p>
      -	본체에서 제어기까지의 배선은 반드시 길이를 지정해 주십시오.
</td>
  </tr>
</thead>
</table>  
</blockquote>


# 5.2.1. 배선전개 접속도

본체 내 배선의 부품기호는 [그림 5.2]를 참조하여 주십시오.


![](../../_assets/그림_5.2_본체내_배선기호설명.png)

그림 5.2 본체 내 배선 기호 설명

![](../../_assets/그림_5.3_본체배선접속도.png)

그림 5.3 본체 전개 접속도# 6. 문제점 발생시의 조치



# 6.1. 문제점 원인조사 진행방법

로봇의 동작·운전 중 어떠한 이상이 발생했을 때 제어기의 이상이 아닐 경우, 기계 부품의 손상에 의한 문제입니다. 트러블을 쉽고 빠르게 처리 할 수 있는 방법은 먼저 현상을 정확히 파악하고, 또한 어떤 부품의 불량에 의한 것인지를 판단할 필요가 있습니다.

<ol style="list-style-type:decimal" start="1">
	<li>제 1 단계 : 어느 축에 이상이 발생하고 있는가?

먼저 어느 축에 이상한 현상이 발생하고 있는가를 확인하여 주십시오. 이상한 현상이 동작에 나타나지 않아 판단하기 어려울 때는,


-	이음이 발생하고 있는 부위는 없는가?
-	이상발열이 발생하고 있는 부위는 없는가?
-	유격이 있는 부위는 없는가? 등을 조사하여 주십시오.
</li><br>
	<li>제 2 단계: 어느 부품에 손상이 있는가?

이상이 있는 축이 판명되면 어떤 부품에서 이상 원인이 있는가를 조사해 주십시오. 1가지 현상에 대해서 여러 가지의 원인이 나타날 수 있습니다. 다음 페이지의 트러블 현상과 원인에 대한 [표6-1]을 참조하여 주십시오.
</li><br>
	<li>제 3 단계: 불량 부품의 처리
	
불량 부품으로 판명되면 『6.3각 부품별 조사방법 및 처리방법』에 기술된 방법으로 처리해 주십시오. 귀사에서 처리할 수 있는 항목 이외의 사항에 대해서는 당사 서비스부문으로 연락 주십시오.
</li>
</ol> 

# 6.2. 문제점 현상과 원인 

[표 6-1]에 나타난 것과 같이 한가지의 현상에 대해서 그 원인으로 생각되는 부품이 여러 가지가 있을 수 있습니다. 
어떤 부품이 손상되어 있는가 판단하기 위해서 다음 페이지를 참고하여 주십시오.

<br>
표 6-1 문제점 현상과 원인

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">이상부위/<br>트러블현상</th>
    <th class="tg-jafi">감속기</th>
    <th class="tg-jafi">브레이크</th>
    <th class="tg-jafi">모터</th>
    <th class="tg-jafi">엔코더</th>
    <th class="tg-jafi">각 지점 베어링부</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">과부하 [주 1]</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
  </tr>
  <tr>
    <td class="tg-wa1i">위치 편차</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>

  </tr>
  <tr>
    <td class="tg-wa1i">이음 발생</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>

  </tr>
  <tr>
    <td class="tg-wa1i">운전시 진동 [주 2]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>

  </tr>
    <tr>
    <td class="tg-wa1i">정지 시 흔들림 [주 3]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>

  </tr>
    <tr>
    <td class="tg-wa1i">불규칙적 주기(맥동) [주 4]</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>

  </tr>
  <tr>
    <td class="tg-wa1i">편차 이상</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>

  </tr>
  <tr>
    <td class="tg-wa1i">축의 자유 낙하</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>

  </tr>
  <tr>
    <td class="tg-wa1i">이상 발열</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>

  </tr>
  <tr>
    <td class="tg-wa1i">오동작, 폭주</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>

  </tr>
</tbody>
</table>

<br>

[주1] 과부하 ------------- 모터의 정격사양 조건을 초과하는 부하가 걸릴 때 발생하는 현상.

구체적으로는 온도릴레이, 회로차단기의 차단 등이 발생합니다.

[주2] 운전시 진동 -------- 동작시의 진동 현상.

[주3] 정지 시 흔들림 ----- 정지 시에 정지위치 주변에서 수 회 동안 요동을 되풀이하는 현상.

[주4] 불규칙적 주기(맥동)- 유지 자세에 있어서 정해진 주기를 유지하지 못하고 진동하는 현상.

<br>

이음이 발생하는 경우는 대개 다음과 같습니다.
1.	그리스/감속기 교환 후 가동시
2.	장기간 미사용 후 가동시
3.	저속에서 가동시
4.	저온 가동시

# 6.3. 각 부품별 조사방법 및 처리방법# 6.3.1. 각 지점 베어링부

각 지점 베어링부 자체가 손상되는 경우는 진동·이음발생과 과부하 현상의 원인이 됩니다. 또한, 베어링 고정용 너트(Nut)에 헐거움이 생길 경우 베어링에 유격이 발생합니다. 이처럼 유격이 생기면 베어링을 손상시키는 원인이 됩니다.



*	조사방법

    ①	베어링에 유격이 없는지 제 1암과 제 2암에 힘을 가하여 조사하여 주십시오.

    (체인 블록(Chain Block) 등이 사용될 경우는 제 1암과 제 2암의 자세를 유지하고, 감속기에 부하가 가해지지 않은 상태로 베어링에 유격이 없는가를 조사하여 주십시오)

    ②	이상 발생 전에 로봇이 주변장치 등에 접촉 되지 않은가를 조사하여 주십시오.



*	처리방법

    베어링을 교환하여 주십시오. 이때 로봇 암을 위로 매달기 위하여 체인 블록(Chain Block) 등의 설비가 필요합니다. 어려움이 있으면 당사 서비스부문으로 연락 주십시오.




# 6.3.2. 감속기

감속기가 손상된 경우 진동·이음발생이 나타나게 됩니다. 이 경우 정상적인 운전을 방해하는 과부하현상 및 편차이상의 원인이 되며, 이상발열이 생기기도 합니다. 또한 전혀 움직이지 않거나 위치편차가 생기는 경우도 있습니다.

<img src="../../_assets/작은주의표시.png"> <b>[주축 (S, H, V)]</b>

H&V축 브레이크 해제 스위치를 [ON][OFF]할 때는, 암이 낙하하기 때문에, 암이 떨어지지 않도록 조치를 취한 다음 브레이크 해제 스위치를 작동시키십시오.

*	조사방법

    ①	동작 시에 진동·이음·감속기부의 이상 발열이 나타나지 않는지 조사하여 주십시오

    ②	감속기에 유격과 마모는 없는지, S축 브레이크 해제스위치를 [On] 상태에서 제 1암을 잡고 로봇을 돌려 이상이 손에 느껴지는지를 조사하여 주십시오.

    ③	이상 발생 전, 로봇이 주변장치 등에 접촉이 되지 않는가를 조사하여 주십시오.
    (접촉 충격에 의해 감속기가 손상되는 경우가 있습니다)


*	처리방법

    감속기를 교환하여 주십시오. 다음은 로봇의 암을 위로 매달기 위하여 체인블록(Chain Block)등의 설비가 필요합니다. 어려움이 있으면 당사 서비스부문으로 연락 주십시오


<img src="../../_assets/작은주의표시.png"> <b>[손목축(R2, B, R1)]</b>

브레이크 해제 스위치를 [ON][OFF]할 때는, 암이 낙하하기 때문에, 암이 떨어지지 않도록 조치를 취한 다음 브레이크 해제 스위치를 작동시키십시오.

*	조사방법

    ①	동작 시에 진동·이음, 감속기부의 이상발열이 나타나지 않는가 조사해주십시오.

    ②	감속기에 유격은 없는지 엔드이펙터(End Effector(스폿 건, 핸드장치 등))에 힘을 가해 조사하여주십시오.

    ③	운전준비를 차단하고 브레이크해제 스위치 [ON]의 상태에서 손으로 축이 움직이는가 조사하여주십시오. 움직이지 않으면 이상이 있는 것입니다.

    ④	비상 발생 전, 로봇 주변 장치 등에 접촉이 되지 않는가를 조사하여 주십시오.

    (접촉 충격에 의해 감속기가 손상되는 경우가 있습니다)

*	처리방법

    ①	감속기를 교환하여 주십시오.

    ②	손목부 전체를 교환하여 주십시오.

    (감속기의 교환에는 시간과 설비가 필요하기 때문에 손목부 전체를 교환하는 경우 빠르고 확실히 처리할 수 있습니다)
 



# 6.3.3. 브레이크(Brake)

브레이크에 이상이 발생한 경우 운전준비 [OFF]상태에서 각 축이 낙하할 경우가 있습니다. 또는, 역으로 운전준비 [ON]상태에서도 브레이크가 작동하게 되는 경우가 있습니다. 이와 같은 경우는 과부하현상, 소음발생의 원인이 됩니다.


![](../../_assets/작은주의표시.png) 모터 [ON]하지 않고 로봇 본체를 움직이고자 할 때는 브레이크 해제 스위치를 [ON]으로 하여 움직이십시오. 이때, 중력에 의해 로봇 암이 낙하하기 때문에, 암의 낙하방지조치를 취한 후에 브레이크 해제 스위치를 [ON]하십시오. 



*	조사방법

    운전준비 [OFF]상태에서 브레이크 해제스위치의 [ON], [OFF]하면서 브레이크의 동작 음이 나는지 조사하여 주십시오. 브레이크의 동작 음이 나지 않는 경우는 단선으로 생각 됩니다. (브레이크 해제스위치의 [ON], [OFF]를 작동할 경우 암의 낙하에 특히 주의하여 주십시오. 브레이크의 해제스위치는 제어기의 문을 열면 문 측의 기판에 있습니다)
    
*	처리방법

    기내배선을 체크하여 단선이 아닐 경우, 모터를 교환해 주십시오.




# 6.3.4. 모터(Motor)

모터에 이상이 발생된 경우 정지 시 흔들림, 불규칙 주기(맥동), 운전시 진동과 같은 이상 동작이 발생합니다. 또한, 이상발열과 이음이 발생하는 경우도 있습니다.

감속기가 손상된 경우와 같은 유사한 현상이 생기므로 원인이 어디에 있는가를 판단하기 위해서는 감속기 및 베어링부의 조사도 동시에 해 주십시오.

*	조사방법

    이음, 이상발열이 발생하지 않는가 조사하여 주십시오.
 
*	처리방법

    모터를 교환하여 주십시오.
# 6.3.5. 엔코더(Encoder)

엔코더에 이상이 발생된 경우 위치편차·오동작·폭주 등을 일으키며 정지 시 흔들림, 불규칙한 주기(맥동)가 발생하는 경우가 있습니다. 그리고 이러한 트러블 경우는 기계적인 이음과 발열·진동 등의 현상이 생기는 것과는 관계가 없습니다.

*	조사방법

    ①	엔코더 데이터에 이상이 없는가 조사하여 주십시오.

    ②	맞춤용 스케일의 기준위치에 맞추고 위치데이터에 오차가 없는가 조사하십시오.

    ③	로봇 각 축을 움직여 데이터가 불규칙적으로 변화하는 곳이 없는지 조사하십시오.

    ④	서보 앰프 기판, BD542을 교환하여 에러 현상이 발생하지 않는지를 조사하십시오.

*	처리방법

    ①	배선을 체크하여 단선이 아닌 경우는 엔코더를 교환하여 주십시오.

    ②	서보 앰프 기판 BD542을 교환하여 에러 현상이 발생하지 않는 경우는 서보 앰프 기판을 교환하여 주십시오.


# 6.4. 엔코더 원점 설정

엔코더 데이터가 어떠한 트러블로 인하여 이상한 수치를 나타낸 경우와 모터 교환을 한 경우는 로봇의 원점 맞추기를 하여야 합니다.

로봇의 각 축 기준 자세 위치 결정 방법으로 스케일을 사용하고 있습니다. 손목축의 구조상 축간섭이 있기 때문에, 반드시 4축, 5축, 6축 순으로 원점 설정을 해야 합니다.




![](../../_assets/작은주의표시.png) <b>주의사항</b>

이 작업은 운전준비 [ON] 상태에서 수행해야 하는 부분이 있습니다. 그러므로 2인 1조로 작업을 실시하며 한 사람은 언제라도 비상정지 버턴을 누를 자세를 취하고, 다른 한 사람은 로봇의 동작에 특히 주의하면서 신속하게 작업을 하십시오.

또한, 작업 전에는 미리 위험을 벗어날 장소를 확인하여 주십시오.
# 6.4.1. 원점 맞추기

<ol style="list-style-type:decimal" start="1">
<li>
제어기를 티칭 모드에 맞추고 운전 준비를 [ON]으로 하여 주십시오. 
이상으로 인하여 운전준비를 [ON]할 수 없는 경우는 브레이크 해제 스위치를 사용하여 로봇의 기준 위치를 맞추어주십시오.
</li><br>
<li>
각 축을 기본자세까지 움직여 스케일 및 V홈을 일치시키십시오.
</li><br>
<li>
엔코더 리셋을 하십시오. 엔코더 리셋 방법은 『6.5.2 엔코더 리셋』을 참고하십시오.
</li><br>
<li>엔코더 보정을 해 주십시오. 『제어기 조작설명서』를 참조하십시오.
</li><br>
<li>로봇 동작에 문제가 없는지를 확인하십시오.
</li>
</ol>
<br># 6.4.2. 엔코더 리셋

<ol style="list-style-type:decimal" start="1">
    <li> 모터를 OFF하십시오.
</li><br>
    <li>시리얼 엔코더 리셋 창을 띄웁니다. (『[F2]: 시스템』 → 『5: 초기화』 → 『4: 시리얼 엔코더 리셋』)
<br><br>

![](../../_assets/그림_6.4_시리얼_엔코더_리셋.png)
 

</li><br>
    <li>
    [↓], [↑], [SHIFT] + [←][→]키를 이용하여 원하는 축으로 이동한 후 [실행]키를 누릅니다.
</li><br>
    <li>
엔코더 리셋 후에는 반드시 제어기 전원을 OFF → ON 해야 합니다.
</li>
</ol>
# 6.4.3. 엔코더 보정 및 선택


*	로봇 각 축의 기준 위치에 엔코더 DATA의 보정 작업이 필요합니다.
*	제어기 조작설명서『엔코더 보정』을 참조해서, 엔코더 보정을 해주십시오.

<b>[엔코더 보정화면]</b>

![](../../_assets/그림_6.5_엔코더_보정.png)



<ol style="list-style-type:decimal" start="1">
    <li>
축을 선택하고 [축 조작]키로 기준위치로 축을 이동시키고 『[F1]: 적용』키를 누릅니다. 
    </li><br>
    <li>
로봇 전축을 [축조작]키를 이용하여 기준자세로 위치시키고 『[F2]: 전체적용』키를 누르면 한번에 모든 축에 대해 엔코더 옵셋 보정이 수행됩니다.
    </li><br>
    <li>
설정 데이터를 저장하기 위해서는 『[F7]: 확인』키를 누릅니다. [ESC]키를 누르면 변경된 데이터가 저장되지 않습니다.
</li>
</ol>

<table>
<thead>
  <tr>
    <td>
    <div align="center">
      <img src="../../_assets/주의표시.png" width = 60 height = 60>
    </div>
    </td>
    <td colspan="4"><b>주의사항</b><br>
    모터 교환 후, 엔코더 DATA 보정을 행하는 경우, 일단 전원 준비를 『ON』상태로 해서 모터에 전원이 들어가는지를 확인해 주십시오.</td>
  </tr>
</thead>
</table>  


# 7. 권장 예비부품

로봇의 예비부품으로서 권장하는 부품은 아래 표와 같습니다. 구입할 때는 로봇본체의 제조 번호와 제조일자를 확인하고 당사 서비스부문으로 연락 주십시오.

<b>[분류]</b>

A : 정기 보수부품 (정기적으로 교환하는 것)

B : 주요 예비부품 (동작빈도가 많아서 예비부품으로 준비해 두기를 추천하는 것)

C : 주요 구성부품

D : 기구 부품

<br></br>
표 7-1 예비 부품 리스트
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">분류</th>
    <th class="tg-jafi">적용 로봇</th>
    <th class="tg-jafi">PLATE No.</th>
    <th class="tg-jafi">품명 및 규격</th>
    <th class="tg-jafi">수량</th>
    <th class="tg-jafi">비고</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">A</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R7900015261</td>
    <td class="tg-nrix">SK-1A</td>
    <td class="tg-nrix">2.5kg/CAN</td>
    <td class="tg-nrix">공통</td>
  </tr>
  <tr>
    <td class="tg-nrix">A</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R1001-6202-P2</td>
    <td class="tg-nrix">엔코더 배터리</td>
    <td class="tg-nrix">6EA</td>
    <td class="tg-nrix">공통</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P02</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S축</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P03</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H축</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P04</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V축</td>
  </tr>
  <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P02</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R2축</td>
  </tr>
   <tr>
    <td class="tg-nrix">B</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P03</td>
    <td class="tg-nrix">MOTOR</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">B,R1축 공용</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P01</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P01</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P02</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P01</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R2축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P01</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P02</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P01</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P02</td>
    <td class="tg-nrix">감속기</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1축</td>
  </tr>
  <tr>
    <td class="tg-nrix">C</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7511-001</td>
    <td class="tg-nrix">S축 배선 ASS'Y</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">CABLE ASSY</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P03</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">S축 GEAR(2ND)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P04</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S축 감속기</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P05</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S AXIS SHAFT</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7111-P06</td>
    <td class="tg-nrix">O-RING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">S AXIS MOTOR</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H축 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P06</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V축 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P07</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">UPPER FRAME</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P08</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H축 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P09</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V축 감속기</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P10</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">UPPER FRAME</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P11</td>
    <td class="tg-nrix">TIMING BELT</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">H축 모터</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7211-P12</td>
    <td class="tg-nrix">TIMING BELT</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">V축 모터</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P03</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">ARM FRAME (V축)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P04</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">ARM FRAME (R2 축)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">ARM PIPE</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P06</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">ARM FRAME (V축)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P07</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">ARM FRAME (R2 축)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7311-P08</td>
    <td class="tg-nrix">TIMING BELT</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R2축 모터</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P04</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B축 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">B축 감속기</td>
  </tr>
      <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P06</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P07</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P08</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">GEAR(R1 2nd)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P09</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">R1축 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P10</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P11</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P12</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P13</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">HOLDER(R1 AXIS)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P14</td>
    <td class="tg-nrix">TIMING BELT B</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">B축 모터</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7/HH4L/HH8</td>
    <td class="tg-nrix">R3447-7411-P15</td>
    <td class="tg-nrix">TIMING BELT R1</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1축 모터</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P05</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B축 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P06</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B축 감속기</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P07</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P08</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">GEAR(R1 1st)</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P09</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P10</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P11</td>
    <td class="tg-nrix">BALL BEARING</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">GEAR(R1 2nd)</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P12</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">MECHANICAL INTERFACE</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P13</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
    <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P14</td>
    <td class="tg-nrix">OIL SEAL</td>
    <td class="tg-nrix">2EA</td>
    <td class="tg-nrix">WRIST HOLDER</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P15</td>
    <td class="tg-nrix">TIMING BELT B</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">B축 모터</td>
  </tr>
  <tr>
    <td class="tg-nrix">D</td>
    <td class="tg-nrix">HH7E</td>
    <td class="tg-nrix">HH7E-7411-P16</td>
    <td class="tg-nrix">TIMING BELT R1</td>
    <td class="tg-nrix">1EA</td>
    <td class="tg-nrix">R1축 모터</td>
  </tr>
</tbody>
</table># 8. 본체 내 배선 접속도





# 8.1. 부품 배치도

본체 내 배선은 유니트(UNIT)마다 분기하여 접속도로 나타내고 있으므로 배선체크 및 교환 시에 이용해주십시오.

![](../_assets/그림_10.1_본체_부품_배치.png)

그림 8.1 본체 부품배치


![](../_assets/기내배선도표지.png)
![](../_assets/기내배선도.png)
![](../_assets/기내배선도1.png)
![](../_assets/기내배선도2.png)
![](../_assets/기내배선도3.png)
![](../_assets/기내배선도4.png)
![](../_assets/기내배선도5.png)
![](../_assets/기내배선도6.png)
![](../_assets/기내배선도7.png)
![](../_assets/기내배선도8.png)
![](../_assets/기내배선도9.png)
![](../_assets/기내배선도10.png)
![](../_assets/기내배선도11.png)
![](../_assets/기내배선도12.png)
![](../_assets/기내배선도13.png)
![](../_assets/기내배선도14.png)
![](../_assets/기내배선도15.png)
![](../_assets/기내배선도16.png)
![](../_assets/기내배선도17.png)
![](../_assets/기내배선도18.png)
![](../_assets/기내배선도19.png)
![](../_assets/기내배선도20.png)
![](../_assets/기내배선도21.png)

