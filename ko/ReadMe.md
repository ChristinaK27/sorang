# Kubernetes (K8s)

[! [GoPkg 위젯]] [GoPkg] [! [CII 권장 사항] (https://bestpractices.coreinfrastructure.org/projects/569/badge)] (https://bestpractices.coreinfrastructure.org/projects/569)

<img src = "https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png"width = "100">

----

K8이라고도하는 Kubernetes는 [컨테이너화 된 애플리케이션]을 관리하기위한 오픈 소스 시스템입니다.
여러 호스트에서. 배포, 유지 관리,
응용 프로그램의 확장.

Kubernetes는 Google 실행에서 10 년 반의 경험을 바탕으로 구축되었습니다.
[Borg]라는 시스템을 사용하여 대규모 프로덕션 워크로드,
커뮤니티의 동급 최고의 아이디어 및 관행과 결합됩니다.

Kubernetes는 Cloud Native Computing Foundation ([CNCF])에서 호스팅합니다.
귀사가
컨테이너 패키지, 동적 예약 기술,
마이크로 서비스 지향적이라면 CNCF 가입을 고려하십시오.
참여자 및 Kubernetes의 역할에 대한 자세한 내용은
CNCF [공지]를 읽으십시오.

----

## K8s 사용을 시작하려면

[kubernetes.io]에 대한 문서를 참조하십시오.

[대화 형 자습서]를 사용해보십시오.

[Kubernetes로 확장 가능한 마이크로 서비스]에 대한 무료 과정을 수강하세요.

다른 애플리케이션에서 Kubernetes 코드를 라이브러리로 사용하려면 [게시 된 구성 요소 목록] (https://git.k8s.io/kubernetes/staging/README.md)을 참조하세요.
`k8s.io / kubernetes` 모듈 또는`k8s.io/kubernetes / ...`패키지를 라이브러리로 사용하는 것은 지원되지 않습니다.

## K8 개발 시작

[커뮤니티 저장소]는 다음에 대한 모든 정보를 호스팅합니다.
소스에서 Kubernetes 빌드, 코드 기여 방법
문서, 무엇에 대해 누구에게 연락해야하는지 등

Kubernetes를 즉시 구축하려는 경우 두 가지 옵션이 있습니다.

##### 작동하는 [Go 환경]이 있습니다.

```
mkdir -p $ GOPATH / src / k8s.io
cd $ GOPATH / src / k8s.io
git clone https://github.com/kubernetes/kubernetes
cd kubernetes
하다
```

##### 작동하는 [Docker 환경]이 있습니다.

```
git clone https://github.com/kubernetes/kubernetes
cd kubernetes
퀵 릴리스
```

전체 내용을 보려면 [개발자 문서]로 이동하세요.

## 지원하다

지원이 필요하면 [문제 해결 가이드]부터 시작하세요.
우리가 설명한 프로세스를 통해 작업하십시오.

즉, 궁금한 점이 있으면 Google에 문의하세요.
[일방 통행] [통신].

[공지] : https://cncf.io/news/announcement/2015/07/new-cloud-native-computing-foundation-drive-alignment-among-container
[Borg] : https://research.google.com/pubs/pub43438.html
[CNCF] : https://www.cncf.io/about
[통신] : https://git.k8s.io/community/communication
[커뮤니티 저장소] : https://git.k8s.io/community
[컨테이너화 된 애플리케이션] : https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/
[개발자 문서] : https://git.k8s.io/community/contributors/devel#readme
[Docker 환경] : https://docs.docker.com/engine
[Go 환경] : https://golang.org/doc/install
[GoPkg] : https://pkg.go.dev/k8s.io/kubernetes
[GoPkg 위젯] : https://pkg.go.dev/badge/k8s.io/kubernetes.svg
[대화 형 자습서] : https://kubernetes.io/docs/tutorials/kubernetes-basics
[kubernetes.io] : https://kubernetes.io
[Kubernetes로 확장 가능한 마이크로 서비스] : https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615
[문제 해결 가이드] : https://kubernetes.io/docs/tasks/debug-application-cluster/troubleshooting/
