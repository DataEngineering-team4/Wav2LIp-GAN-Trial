# Wav2LIp-GAN-Trial

순차적으로 코드를 진행하면 되지만, 몇가지 에러때문에 저는 시간을 조금 태웠습니다..

1. 코드를 진행하기 위해 사전에 진행해야 할 것은, 구글 드라이브에 Wav2lip, Wav2Lip 폴더를 생성합니다.

2. Wav2Lip 폴더에는 합성할 오디오 파일(ditto.wav)과 영상 파일(kennedy.mp4)을 넣어주었습니다. 

3. Wav2lip 폴더에는 사전 학습된 weight 파일인 'wav2lip_gan.pth' 을 넣어주었습니다. 

  - weight 파일은 아래 본문 Readme 에 있는 Link를 통해 받을 수 있습니다. 
  
  ![image](https://user-images.githubusercontent.com/67546438/227890015-a014e75f-a0da-400e-a3d5-e82bccb46ca6.png)
  
  사용한 링크 : https://iiitaphyd-my.sharepoint.com/:u:/g/personal/radrabha_m_research_iiit_ac_in/EdjI7bZlgApMqsVoEUUXpLsBxqXbn5z8VTmoxp55YNDcIA?e=n9ljGW
  
4. requirements.txt 에 있는 대부분 라이브러리 버전을 설치할 수 없어서, 노가다를 통해서 구동시킬 수 있는 버전을 저는 다음과 같이 사용하였습니다.  
  <img width="237" alt="image" src="https://user-images.githubusercontent.com/67546438/227890654-30ab1b88-07c2-4614-b097-83c5c77a106c.png">

5. audio.py 코드를 수정해야 합니다. 오류 원인 찾느라 많이 아팠습니다.
   <img width="792" alt="image" src="https://user-images.githubusercontent.com/67546438/227890914-daa0b13c-896b-4d81-a236-304b93538766.png">

6. 이렇게 다 진행을 하면, results 폴더에 'result_voice' 로 합성된 싱크 영상이 생성됩니다. 
