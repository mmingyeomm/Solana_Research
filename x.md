









## Clock in Ethereum 

NTP Server + Local OS time 을 이용하여 시간 측정 ​

정확한 기준이 없다. 



POH 

솔라나 같은 경우는 400ms의 짧은 블록타임을 갖고 있기 때문에 


예를 들어 리더 스케쥴이 A -> C -> B 로 나와 있다고 하자 이런 경우에 솔라나는 블록타임이 400ms이기 때문에 
서로 블록을 동시에 생성하는 일이 발생할 수 있다  


이를 해결하기 위해 

각 밸리데이터들이 각자 tick을 계속 돌린다 
리더 스케쥴이 나왔을때 각 밸리데이터들은 틱을 돌려서 자신의 리더 차례가 오기까지 얼만큼의 시간이 지났는지를 판단하고 자신의 차례가 되면 



이게 가능하기 위해서는 한가지의 가정이 필요한데 현재 컴퓨터가 아무리 성능이 좋아져도 해시를 일정시간 이상으로 빠르게 돌릴 수 없다는 것이 전제이다. 



<img width="1220" height="653" alt="Image" src="https://github.com/user-attachments/assets/44e75941-32de-4221-88ad-d548bf9de28f" />



<img width="739" height="361" alt="Image" src="https://github.com/user-attachments/assets/ed98cc4b-ab95-4351-99f0-dacb92fd9cd5" />

