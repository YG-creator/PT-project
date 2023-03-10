# 요구사항 분석

[요구사항 분석](./document/요구사항분석.md)



# 설계

[설계](./document/설계)



# 기능 설명

[상세 설명](./document/상세설명.md)

* 이용권
  * 이용권 등록
  * 사용자는 N개의 이용권을 가질 수 있다.
  * 이용권은 횟수가 모두 소진되거나 이용기간이 지나면 만료된다.
  * 이용권 만로 전 사용자에게 알림을 준다.
  * 업체에서 원하는 시간을 설정하여 일괄로 사용자에게 이용권을 지급할 수 있다.
* 수업
  * 예약된 수업 10분 전 출선 안내 알림을 준다.
  * 수업 종료 후 이용권 횟수 차감한다.
* 통계 데이터
  * 사용자의 수업 예약, 출석, 이용권 횟수 등의 데이터로 통계데이터를 만든다.



# Environments

- OpenJDK 18.0.1
- Spring Boot 2.7.3
- Gradle
- MySQL (Docker)
- JPA
- lombok
- ModelMapper



