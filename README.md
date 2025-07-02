# 👥  사원관리 프로그램

<br/>

## 📑 목차  
- [📝 프로젝트 소개](#-프로젝트-소개)
- [🛠 기술 스택](#-기술-스택)
- [💾 ERD](#-erd)
- [🏗️ 클래스 다이어그램](#-클래스-다이어그램)
- [✨ 주요 기능 소개](#-주요-기능-소개)  
- [🖥️ 실행 화면](#-실행-화면)

<br/>

## 📝 프로젝트 소개
Java Swing을 활용한 데스크탑 기반의 **사원 정보 통합 관리 프로그램**입니다.  
사원의 정보 등록, 수정, 조회, 삭제 기능을 포함하며, 관리자와 사원 권한을 구분하여 운영됩니다.  
Oracle DB와 연동하여 실제 기업 환경에서 사용할 수 있는 완전한 사원 관리 시스템을 구현했습니다.

- **개발 기간**: 개인 프로젝트
- **아키텍처**: Java Swing 기반 데스크탑 애플리케이션
- **배포 형태**: 실행 가능한 JAR 파일

<br/>

## 🛠 기술 스택

### Backend
- **Language**: Java SE
- **Database**: Oracle Database
- **Connection**: JDBC

### Frontend
- **GUI Framework**: Java Swing
- **Design Tool**: Golden (GUI 디자인)

### Development Environment
- **IDE**: Eclipse IDE
- **OS**: Windows 10
- **Build**: Executable JAR

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> <img src="https://img.shields.io/badge/swing-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/jdbc-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white">

<br/>

## 💾 ERD
<p align="center">
  <img src="https://github.com/user-attachments/assets/13001322-6879-48e9-8b7f-a62feaa742a4" alt="ERD" width="700"/>
</p>

<br/>

## 🏗️ 클래스 다이어그램

### 👤 사원 클래스 다이어그램
<p align="center">
  <img src="https://github.com/user-attachments/assets/91f7e55c-9f28-49b4-9ff3-5d37646b0c13" alt="사원 클래스 다이어그램" width="600"/>
</p>

### 👨‍💼 관리자 클래스 다이어그램
<p align="center">
  <img src="https://github.com/user-attachments/assets/331e8d81-af7d-43d0-b89c-405c73391aa9" alt="관리자 클래스 다이어그램" width="600"/>
</p>

<br/>

## ✨ 주요 기능 소개

### 👥 사원 기능
- 👤 개인 정보 조회 및 확인
- ✏️ 본인 정보 일부 수정 (연락처, 주소 등)
- 🔐 비밀번호 변경
- 📋 근태 등록

### 👨‍💼 관리자 기능
- 📊 전체 사원 관리 대시보드
- ➕ 신규 사원 등록
- 📝 사원 정보 수정/삭제
- 🔍 사원 정보 검색 및 조회
- 📈 부서별/직급별 통계
- 🗂️ 사원 데이터 내보내기


<br/>

## 🖥️ 실행 화면 일부 예시
<table align="center" border="0">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/8302243e-4db2-49ca-b3f2-140c660d4c21"  width="400"/>
      <br><br><b></b>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/3269687b-6b00-42ac-88c8-3be9ecb4d9ea"  width="400"/>
      <br><br><b></b>
    </td>
  </tr>
</table>

<br/>

## 🎯 프로젝트 목표 및 성과

### 📈 기술적 목표
- **Java Swing GUI 완성도 향상**: 사용자 친화적 인터페이스 구현
- **DB 연동 CRUD 학습**: Oracle과 JDBC를 통한 완전한 데이터 관리
- **객체지향 설계 실습**: 클래스 다이어그램 기반 체계적 설계
- **예외 처리 구현**: 안정적인 시스템 운영을 위한 예외 상황 대응

### 🏆 주요 성과
- 권한별 차별화된 기능 제공으로 실무 환경 반영
- 트랜잭션 처리를 통한 데이터 무결성 확보
- JAR 파일 배포로 실제 운영 환경에서 사용 가능

<br/>

---

**© 2025 Employee Management System. 본 프로젝트는 학습 목적으로 개발되었습니다.**
