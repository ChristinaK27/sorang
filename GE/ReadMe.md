# Kubernetes (K8s)

[![GoPkg-Widget]][GoPkg] [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/569/badge)](https://bestpractices.coreinfrastructure.org/projects/569)

<img src="https://github.com/kubernetes/kubernetes/raw/master/logo/logo.png" width="100">

----

Kubernetes, auch bekannt als K8s, ist ein Open-Source-System zur Verwaltung von [containerisierten Anwendungen]
über mehrere Hosts. Es bietet grundlegende Mechanismen für Bereitstellung, Wartung,
und Skalierung von Anwendungen.

Kubernetes baut auf anderthalb Jahrzehnten Erfahrung im Google-Betrieb auf
Produktionsworkloads in großem Maßstab mit einem System namens [Borg],
kombiniert mit Best-of-Breed-Ideen und -Praktiken aus der Community.

Kubernetes wird von der Cloud Native Computing Foundation ([CNCF]) gehostet.
Wenn Ihr Unternehmen die Entwicklung von
Technologien, die in Containern verpackt, dynamisch geplant,
und Microservices-orientiert, erwägen Sie, der CNCF beizutreten.
Weitere Informationen zu den Beteiligten und der Rolle von Kubernetes finden Sie unter
Lesen Sie die CNCF [Ankündigung].

----

## So starten Sie die Verwendung von K8s

Siehe unsere Dokumentation auf [kubernetes.io].

Probieren Sie unser [interaktives Tutorial] aus.

Nehmen Sie an einem kostenlosen Kurs zu [Skalierbare Microservices mit Kubernetes] teil.

Informationen zur Verwendung von Kubernetes-Code als Bibliothek in anderen Anwendungen finden Sie in der [Liste der veröffentlichten Komponenten](https://git.k8s.io/kubernetes/staging/README.md).
Die Verwendung des Moduls `k8s.io/kubernetes` oder `k8s.io/kubernetes/...` als Bibliotheken wird nicht unterstützt.

## Um mit der Entwicklung von K8s zu beginnen

Das [Community-Repository] hostet alle Informationen über
Kubernetes aus dem Quellcode erstellen, Code beitragen
und Dokumentation, an wen Sie sich für was wenden können usw.

Wenn Sie Kubernetes sofort erstellen möchten, gibt es zwei Möglichkeiten:

##### Sie haben eine funktionierende [Go-Umgebung].

```
mkdir -p $GOPATH/src/k8s.io
cd $GOPATH/src/k8s.io
git-Klon https://github.com/kubernetes/kubernetes
cd kubernetes
machen
```

##### Sie haben eine funktionierende [Docker-Umgebung].

```
git-Klon https://github.com/kubernetes/kubernetes
cd kubernetes
Schnellverschluss machen
```

Die vollständige Geschichte finden Sie in der [Dokumentation des Entwicklers].

## Unterstützung

Wenn Sie Unterstützung benötigen, beginnen Sie mit der [Anleitung zur Fehlerbehebung],
und arbeiten Sie sich durch den von uns beschriebenen Prozess.

Das heißt, wenn Sie Fragen haben, wenden Sie sich an uns
[auf die eine oder andere Weise] [Kommunikation].

[Ankündigung]: https://cncf.io/news/announcement/2015/07/new-cloud-native-computing-foundation-drive-alignment-among-container
[Borg]: https://research.google.com/pubs/pub43438.html
[CNCF]: https://www.cncf.io/about
[Kommunikation]: https://git.k8s.io/community/communication
[Community-Repository]: https://git.k8s.io/community
[containerisierte Anwendungen]: https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/
[Entwicklerdokumentation]: https://git.k8s.io/community/contributors/devel#readme
[Docker-Umgebung]: https://docs.docker.com/engine
[Go-Umgebung]: https://golang.org/doc/install
[GoPkg]: https://pkg.go.dev/k8s.io/kubernetes
[GoPkg-Widget]: https://pkg.go.dev/badge/k8s.io/kubernetes.svg
[interaktives Tutorial]: https://kubernetes.io/docs/tutorials/kubernetes-basics
[kubernetes.io]: https://kubernetes.io
[Skalierbare Microservices mit Kubernetes]: https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615
[Anleitung zur Fehlerbehebung]: https://kubernetes.io/docs/tasks/debug-application-cluster/troubleshooting/