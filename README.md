# ⚡ Velocity

[![Build Status](https://img.shields.io/github/actions/workflow/status/PaperMC/Velocity/gradle.yml)](https://papermc.io/downloads/velocity)  

**Velocity**는 탁월한 서버 지원, 확장성, 그리고 유연성을 갖춘 **마인크래프트 서버 프록시**입니다.

Velocity는 **GPLv3 라이선스** 하에 배포됩니다.



## 🎯 목표 (Goals)

* **쉽게 이해할 수 있는 코드베이스**  
  가능한 한 자바 프로젝트의 모범 사례를 꾸준히 따르며, 개발자들이 쉽게 코드를 파악하고 기여할 수 있도록 합니다.

* **고성능**  
  단일 프록시에서 수천 명의 플레이어를 처리할 수 있도록 설계되었습니다.

* **새롭고 강력한 API**  
  처음부터 유연하고 강력하게 설계된 API로, 다른 프록시에서 나타난 설계상의 실수나 비효율적인 구조를 피합니다.

* **Paper, Sponge, Fabric, Forge 완벽 지원**  
  이 서버 구현체들은 최우선적으로 지원하며, 다른 서버 플랫폼도 가능하면 호환되도록 노력합니다.


## 🏗️ 빌드 (Building)

Velocity는 [Gradle](https://gradle.org)을 사용해 빌드됩니다.  
CI(지속적 통합)에서도 `./gradlew` 스크립트를 사용하므로, **Gradle Wrapper(`./gradlew`)를 사용하는 것을 권장합니다.**

전체 빌드 사이클을 실행하려면 다음 명령어를 사용하세요:

```bash
./gradlew build
