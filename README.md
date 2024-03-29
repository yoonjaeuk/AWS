# AWS
AWS(성능비교)

## 1. t4g.xlarge vs t4g.micro
### 크롤링 시간차

<div style="display: flex;">
  <img src="https://github.com/yoonjaeuk/AWS/assets/52642461/b4c02080-bf47-4d99-8990-aec2d84160d1" alt="Image 1" style="width: 50%;">
  <img src="https://github.com/yoonjaeuk/AWS/assets/52642461/cfe7ae70-c053-42d4-8c76-b6b0201e1d35" alt="Image 2" style="width: 50%;">
</div>

- t4g.xlarge(4.81s)가 t4g.micro(12.04s)보다 세배 가량 빠르다 

### cpu 사용량

<div style="display: flex;">
  <img src="https://github.com/yoonjaeuk/AWS/assets/52642461/ba008a85-1ff0-4f98-905d-841b7d19129b" alt="Image 1" style="width: 50%;">
  <img src="https://github.com/yoonjaeuk/AWS/assets/52642461/26a265ec-4f3f-438d-80a1-b5418ce1eb90" alt="Image 2" style="width: 50%;">
</div>

- 가장 높은 수치를 기준으로 t4g.xlarge(1.49%)가 t4g.micro(6.87%)에 비해 4배 가량 cpu사용량이 적다 

## 2. m6.2xlarge vs t3.2xlarge
### 크롤링 시간차

<div style="display: flex;">
  <img src="https://github.com/yoonjaeuk/AWS/assets/52642461/e993975c-eaf7-4866-8004-66c1fa91787b" alt="Image 1" style="width: 50%;">
  <img src="https://github.com/yoonjaeuk/AWS/assets/52642461/efb9a701-7bfc-43cb-881a-c33a266cc018" alt="Image 2" style="width: 50%;">
</div>

- m6.2xlarge(4.20s)가 t3.2xlarge(4.34s)보다 빠르다 


### cpu 사용량
![image](https://github.com/yoonjaeuk/AWS/assets/52642461/7c472ff4-b75b-481f-83bd-84eb1b1ad98c)
![image](https://github.com/yoonjaeuk/AWS/assets/52642461/42e3c2b7-31e5-44fd-98a2-d57287c24d40)

- m6.2xlarge(1.67%)가 t3.2xlarge(0.877%)보다 빠르다


1. t3.xlarge vs t4g.xlarge

![image](https://github.com/yoonjaeuk/AWS/assets/52642461/ba08311c-e337-423d-a65c-e63e112e28c0) 
- t4g_xlarge(mobalxterm)
![image](https://github.com/yoonjaeuk/AWS/assets/52642461/6b86774f-dc51-40d4-9bb2-75962e96fb3e)
- t4g_xlarge(aws_monitoring)

![image](https://github.com/yoonjaeuk/AWS/assets/52642461/3c4b1528-5a3b-4d3a-a8a5-03b6a6d8163a) 
- t3_xlarge(mobalxterm)
![image](https://github.com/yoonjaeuk/AWS/assets/52642461/e9f6da60-eae3-477b-9021-213b9fa5e9fb)
- t3_xlarge(aws_monitoring)





2. t3.2xlarge vs t4g.micro

![image](https://github.com/yoonjaeuk/AWS/assets/52642461/8020ffd3-ee89-4e59-8354-69c4341c9564) 
- t3_2xlarge(mobalxterm)
![image](https://github.com/yoonjaeuk/AWS/assets/52642461/031369c5-77a2-4b94-86fa-5c1e3c1dd447)
- t3_2xlarge(aws_monitoring)


![image](https://github.com/yoonjaeuk/AWS/assets/52642461/77e150cb-0cca-4af5-9f39-249e810a5b8d) 
- t4g_micro(mobalxterm)
![image](https://github.com/yoonjaeuk/AWS/assets/52642461/e986785a-42ac-4a27-83c5-79163980ad98)
- t4g_micro(aws_monitoring)



3. m6.2xlarge
   




