---
layout: home
---

# CLI
Shell은 CLI(Command Line Interface) 명령을 통하여 Kernel에 접근하여 명령을 실행의 결과를 얻습니다.

## 인터페이스 
CLI(Command Line Interface)는 사용자가 컴퓨터와 상호작용하는 방식 중 하나로, 키보드를 통해 명령어를 입력하고, 터미널(명령어 해석기)을 통해 컴퓨터와 대화하는 방식입니다. CLI는 텍스트 기반으로 동작하기 때문에, 그래픽 사용자 인터페이스(GUI)보다 `적은 자원을 사용`하며, `자동화` 및 `스크립팅` 작업이 쉽습니다.

CLI를 사용하여 파일 시스템, 프로세스, 네트워크 등 시스템의 여러 가지 측면을 제어하고 관리할 수 있습니다. 리눅스에서는 Bash 쉘과 같은 몇 가지 쉘을 기본으로 제공하며, 사용자는 명령어를 입력하고 쉘에서 결과를 확인할 수 있습니다. 이와 같은 CLI의 기본적인 사용 방법을 익히면, 리눅스 시스템을 보다 효율적으로 운영할 수 있습니다.

## Command Line의 특징
리눅스가 CLI(Command Line Interface)를 기본으로 사용하는 이유는 다음과 같습니다.

* 자원 절약: CLI는 텍스트 기반으로 동작하기 때문에, GUI(Graphical User Interface)보다 적은 자원을 사용합니다. 특히, 초기 리눅스 개발 시에는 하드웨어의 성능이 낮았기 때문에, 자원 절약을 위해 CLI를 사용하였습니다.

* 자동화 및 스크립팅: CLI는 명령어를 스크립팅하여 자동화할 수 있습니다. 이를 통해, 많은 작업을 자동으로 처리할 수 있으며, 일관성과 정확성이 보장됩니다.

* 원격 접속: CLI는 원격으로 접속하여 컴퓨터를 제어하기에 적합합니다. 이는 서버 운영 등에서 매우 유용합니다.

* 텍스트 기반: 리눅스는 오픈 소스 기반으로 개발되었기 때문에, CLI를 사용하면 소스 코드나 로그 파일과 같은 텍스트 파일을 쉽게 편집하고 검색할 수 있습니다.

이러한 이유들 때문에 리눅스는 CLI를 기본 인터페이스로 사용합니다.

## 쉘
리눅스의 CLI는 `쉘(Shell)`이라는 프로그램을 통해 동작합니다.  

쉘은 CLI를 해석하고, 명령어를 실행하는 프로그램입니다. 사용자는 CLI에서 명령어를 입력하면, 이를 쉘로 전달하고, 쉘이 명령어를 해석하여 실행합니다. 쉘은 리눅스 시스템의 여러 가지 작업을 수행할 수 있는 명령어를 포함하고 있으며, 사용자는 이러한 명령어를 입력하여 시스템을 제어할 수 있습니다.

리눅스에서는 여러 종류의 쉘이 있으며, `Bash 쉘`은 가장 일반적으로 사용되는 쉘입니다. Bash 쉘은 기본적으로 대부분의 리눅스 배포판에 포함되어 있으며, 강력한 스크립트 기능을 제공하고 있습니다. 사용자는 Bash 쉘에서 다양한 명령어와 스크립트를 작성하여 시스템을 자동화하고 관리할 수 있습니다.