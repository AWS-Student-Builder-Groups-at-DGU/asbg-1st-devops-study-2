# Kubernetes Perfect Guide Study

![Kubernetes Study](https://img.shields.io/badge/Study-Kubernetes-326CE5?style=for-the-badge\&logo=kubernetes\&logoColor=white)
![Schedule](https://img.shields.io/badge/Every%20Sunday-13%3A00-2ea44f?style=for-the-badge)
![Book](https://img.shields.io/badge/Book-쿠버네티스%20완벽%20가이드-blue?style=for-the-badge)

<br/>

<div align="center">
  <img width="300" height="400" alt="image" src="https://github.com/user-attachments/assets/48dd07e4-b971-4bb4-b21b-474a6742706a" />
</div>

<br/>

## 📌 스터디 소개

이 저장소는 **『쿠버네티스 완벽 가이드』** 교재를 기반으로 진행하는 Kubernetes 스터디 저장소입니다.

각 주차별 발표자는 정해진 범위를 발표하고,
발표자가 아닌 스터디원들은 발표 내용과 관련된 질문을 GitHub Issue로 남깁니다.

스터디는 단순히 내용을 읽고 끝내는 것이 아니라,
각자 공부한 내용을 PR로 정리하고 Issue를 통해 질문과 답변을 남기는 방식으로 진행합니다.

---

## 🕐 정기 스터디 시간

| 항목    | 내용                                                                                                             |
| ----- | -------------------------------------------------------------------------------------------------------------- |
| 정기 시간 | 매주 일요일 13:00                                                                                                   |
| 교재    | 쿠버네티스 완벽 가이드                                                                                                   |
| 진행 방식 | 발표 + 질문 Issue + PR Merge                                                                                       |
| 실습 자료 | [kubernetes-perfect-guide 실습 자료](https://github.com/MasayaAoyama/kubernetes-perfect-guide/tree/ko/2nd-edition) |

---

## 👥 발표 순서

현재 확정된 발표 순서는 아래와 같습니다.

```text
민형 → [윤지, 민성, 도윤, 주호, 민종]
```

| 순서    | 발표자                | 상태    |
| ----- | ------------------ | ----- |
| 1     | 민형                 | 확정    |
| 2 ~ 6 | 윤지, 민성, 도윤, 주호, 민종 | 순서 미정 |

---

## ✅ 스터디 참여 규칙 요약

발표하지 않는 모든 사람은 **스터디 시작 전까지** 아래 작업을 완료해야 합니다.

```text
1. 본인이 공부한 내용을 PR로 올리기
2. 해당 PR 번호를 기준으로 Issue 생성하기
3. Issue에 발표자에게 할 질문 작성하기
```

발표자는 **발표가 끝난 후 스터디 진행 중에** 아래 작업을 완료해야 합니다.

```text
1. 본인 발표와 관련된 Issue 확인
2. Issue comment로 질문에 답변
3. 답변 완료 후 해당 질문자의 PR merge
4. Issue close 및 브랜치 delete 확인
```

**자세한 GitHub 운영 규칙은 RULES.md 문서를 참고합니다.**

---

## 📚 교재 목차

### 1장. 도커 복습과 Hello, Kubernetes

* 도커 복습
* 도커 컨테이너란?
* 도커 파일 작성법
* 도커 이미지 빌드
* 도커 레지스트리로 이미지 업로드
* 컨테이너 기동
* 쿠버네티스의 세계로

### 2장. 왜 쿠버네티스가 필요할까?

* 쿠버네티스란?
* 쿠버네티스의 역사
* 쿠버네티스를 사용하면 무엇을 할 수 있을까?
* 선언적 코드를 사용한 관리
* 스케일링과 오토 스케일링
* 스케줄링
* 리소스 관리
* 자동화된 복구
* 로드 밸런싱과 서비스 디스커버리

### 3장. 쿠버네티스 환경 선택

* 쿠버네티스 환경의 종류
* 로컬 쿠버네티스
* 미니큐브
* Docker Desktop
* kind
* 쿠버네티스 구축 도구
* 퍼블릭 클라우드 관리형 쿠버네티스 서비스
* GKE, AKS, EKS

### 4장. API 리소스와 kubectl

* kubectl 설치와 자동 완성
* 쿠버네티스 기초
* 쿠버네티스 리소스
* 네임스페이스
* 매니페스트 생성, 삭제, 갱신
* kubectl apply
* 리소스 상태 확인
* get, describe, logs, exec, cp, port-forward
* kubectl 디버깅

### 5장. 워크로드 API 카테고리

* 파드
* 레플리카셋
* 디플로이먼트
* 데몬셋
* 스테이트풀셋
* 잡
* 크론잡

### 6장. 서비스 API 카테고리

* 쿠버네티스 클러스터 네트워크
* 서비스 디스커버리
* ClusterIP
* ExternalIP
* NodePort
* LoadBalancer
* Headless Service
* ExternalName
* Ingress

### 7장. 컨피그 & 스토리지 API 카테고리

* 환경 변수
* Secret
* ConfigMap
* PersistentVolume
* PersistentVolumeClaim
* Volume
* StorageClass
* 동적 프로비저닝

### 8장. 클러스터 API 카테고리와 메타데이터 API 카테고리

* 클러스터 API 카테고리
* 메타데이터 API 카테고리
* 노드
* 네임스페이스

### 9장. 리소스 관리와 오토 스케일링

* CPU / Memory 리소스 제한
* Cluster Autoscaler
* LimitRange
* QoS Class
* ResourceQuota
* HorizontalPodAutoscaler
* VerticalPodAutoscaler

### 10장. 헬스 체크와 컨테이너 라이프사이클

* Liveness Probe
* Readiness Probe
* Startup Probe
* restartPolicy
* 초기화 컨테이너
* postStart / preStop
* 파드의 안전한 종료

### 11장. 메인터넌스와 노드 정지

* 노드 정지
* cordon
* uncordon
* drain
* PodDisruptionBudget

### 12장. 유연한 고급 스케줄링

* 필터링과 스코어링
* nodeSelector
* 노드 어피니티
* 인터파드 어피니티
* 안티어피니티
* 테인트와 톨러레이션
* PriorityClass

### 13장. 보안

* ServiceAccount
* RBAC
* Role / ClusterRole
* RoleBinding / ClusterRoleBinding
* SecurityContext
* Pod Security Context
* NetworkPolicy
* Secret 암호화

### 14장. 매니페스트 범용화 오픈 소스 소프트웨어

* Helm
* Helm Chart
* Artifact Hub
* Kustomize
* 매니페스트 오버레이
* ConfigMap / Secret 동적 생성

### 15장. 모니터링

* 쿠버네티스 모니터링
* Datadog
* Prometheus
* 대규모 모니터링 에코시스템

### 16장. 컨테이너 로그 집계

* 컨테이너 로그 출력
* Fluentd
* Fluent Bit
* Cloud Logging
* Datadog Logs
* Grafana Loki

### 17장. 쿠버네티스 환경에서의 CI/CD

* Kubernetes CI/CD
* GitOps
* Argo CD
* Conftest
* Open Policy Agent
* Skaffold
* Jenkins X
* Spinnaker

### 18장. 마이크로서비스 아키텍처와 서비스 메시

* 마이크로서비스 아키텍처
* 서비스 메시
* Istio
* Istio 아키텍처
* 샘플 애플리케이션

### 19장. 쿠버네티스 아키텍처의 이해

* Kubernetes Architecture
* etcd
* kube-apiserver
* kube-scheduler
* kube-controller-manager
* kubelet
* kube-proxy
* CNI
* CoreDNS
* CustomResourceDefinition
* Operator

### 20장. 쿠버네티스와 미래

* OCI
* CRI
* CSI
* CNI
* Kubernetes Ecosystem
* Kubernetes-native Testbed
* Config Connector

### 21장. 부록

* kubectl 리소스 약어
* 자주 묻는 질문과 답변

---

## 🔗 참고 링크

* [실습 자료 GitHub Repository](https://github.com/MasayaAoyama/kubernetes-perfect-guide/tree/ko/2nd-edition)
* [GitHub 운영 규칙](./RULES.md)

---

## 🚀 목표

이 스터디의 목표는 Kubernetes 개념을 단순히 암기하는 것이 아니라,
직접 정리하고 질문하며 실습을 통해 실제로 사용할 수 있는 수준까지 익히는 것입니다.

```text
읽기 → 정리하기 → 질문하기 → 답변하기 → 실습하기
```
