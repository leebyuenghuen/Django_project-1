# HnH : 클라우드 서비스 개발 팀프로젝트

## 1. 프로젝트 개요
- HnH는 'Health & Happy'를 뜻하며, 건강한 음식으로 즐거운 건강관리를 하자는 의미를 담고있다. 

## 2. 구성도

![1.png](./cloudImg/1.png?raw=true)
- 그림1. 클라우드 아키텍처 구성도


## 3. 기능
- [x] 1. 검색한 식재료 기반 음식점 추천
  - 식재료 검색 > 사용자의 위치 기반으로 주변 음식점 추천 목록 불러오기
  - 사용한 오픈API : 카카오맵 API

- [x] 2. 게시판
  - 정보 공유 및 밥친구 모집 
  - 댓글 기능 

- [ ] 3. 검색한 식재료 기반 건강 레시피 불러오기
  - 식재료 입력 > 관련 건강 레시피 


## 4. 구현 기술
 ### 1) Kubernetes Service
 - SVC, Deployment, Statefulset, Secret, ConfigMap, Cronjob, Namespace, HPA 
 
 ### 2) AWS 
 - ECR
 - ACM
 - AWS WAF
 - Amazon CloudWatch
 - ELB
 - AWS Lambda
 - Amazon SNS
 - Amazon S3
 - Amazon RDS
 - Amazon EC2
 - Amazon EKS
 - Route53

 ### 3) Github
 - GithubAction을 활용한 CI/CD 

 ### 4) Web Server
 - nginx

 ### 5) WAS (Web Application Server)
 - django 
  
