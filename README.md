# 게임 서버 개발과 관련된 정보를 모은 저장소

## Socket 프로그래밍
  
### C#
- [SuperSocketLite](https://github.com/jacking75/SuperSocketLite ) - 라이브러리  
  


### C++ 
- [씹어먹는 C++](https://github.com/kev0960/ModooCode/raw/master/book/cpp/main.pdf )
- [YOUTUBE C++ Korea 제6회 세미나 - 채팅 서버 개발로 알아보는 C++의 기능들](https://youtu.be/JxejgUKTViQ )
- [BeeJ's Guide to Network Programming - 인터넷 소켓 활용](https://blogofscience.com/Socket_Programming-KLDP.html )  


## 클라우드 
- [AWS 리전간 레이턴시 시각화](https://benjdd.com/aws/ ) 
  
  
  
## Linux
- [WSL2 글모음](https://gist.github.com/jacking75/a4f3cb450bdf8ddfae15eaab58343cf5 )  
- [언어 환경 관리는 *env 및 *vm 넘어서 mise 로](https://docs.google.com/document/d/e/2PACX-1vQze-3qj7CXOcSYvjZ25mnUXUSoPSLadVIEp6IbNhxB4ptrX89vNDftoJPlODYvG13Inlur1cH_qAB9/pub )
  


## DB
  
### MySQL
- 설치
    - [windows 설치](https://stormpy.tistory.com/m/45 )
    - [MySQL Community Server 8.0.15 설치](https://parkdream.tistory.com/93  )
    - [Windows 10 환경 MySQL 64bit 수동 설치 (v8.0.19)](https://sysong85.tistory.com/102 )    
- docker  
    - [docker로 mysql을 사용하기](https://docs.google.com/document/d/1Qrvs07r2Cspce1QvKFAHcirzDjW0q5L-BMDk5jdJovg/edit?usp=sharing )
    - [로컬 환경에서 docker mysql에 연결](https://docs.google.com/document/d/e/2PACX-1vTSidi8ywtgkHC0CBbSQ69zpzyOol5sh9rXGk7Ho4Hjm_meP2YzfU3g2Z-gWa1VZZMAeEeGWBlZgV9k/pub )
    - [한방으로 db 환경 구축하기](https://docs.google.com/document/d/e/2PACX-1vQ8hKrDGdI62JzjoXxUpbHOwBhNkg7mBnDYP5QNj26yIE17V-lWza0-UV6GpPATZ1Cv_YTQ4ysynAX5/pub )  
- [MySQL의 다양한 타임아웃 옵션](https://docs.google.com/document/d/1vc0lBdO1yWZu8Yj2tvOiR3VzsQxin4PbmSW7Rbm5HQY/edit?usp=sharing )
- [수신기한이 지난 데이터를 MySQL에서 삭제할 때의 이야기](https://docs.google.com/document/d/e/2PACX-1vRLotins2K_uOZjf5WoYmspWvcvq18ykWHb8ec9gEOpP2JbYk0uqb5zYUu05k7z1TD7iGNLMmp6-Xh6/pub )
- [MySQL에서 문자열의 유니크 제약 조건을 걸 때 조심할 것](https://docs.google.com/document/d/e/2PACX-1vQXcAf7fzqav158jt8gEkhmSoND3IHDH4SSs0p59W2A0nbUMY78NBgWf9M9HBCMRyzttn_kL4bad3xN/pub )
- 트랜잭션, Lock
    - [트랜잭션 격리 수준에 대한 요약](https://docs.google.com/document/d/e/2PACX-1vQOKAf9lYmJEx7BXBTv4dviFWlFFOG8TUmSvA7OtlCWgB8umDDIHl5C_VRh6IZ7npZD8ccpg_oXrkTY/pub )
    - [MySQL 트랜잭션 격리 수준과 발생하는 법칙을 정리](https://docs.google.com/document/d/e/2PACX-1vRxc1rFVaFUjeqz4Xq9rwLes9Kujd1ijppwO0nJQUevSBHzKBKnDfgxedZM8h_OipELLd1eviXlg2Vr/pub )
    - ["트랜잭션을 사용하면 괜찮다" 라고 생각하지 않습니까? 버그의 온상이 되는 일반적인 구현 패턴](https://docs.google.com/document/d/e/2PACX-1vR3GzvFiTdxpXZYgGxE6nSjwQPujpd1deohWFrnIEES8Vi6egUahEH4b685zdsX8O3h-gtqfDSfnnyd/pub )      
    - [데이터베이스 락(Lock) 기초부터 교착 상태(데드락)까지](https://docs.google.com/document/d/e/2PACX-1vREFF4Ucc54rOjKjf7nast9ZCWqbRPdtN9JDY-MOq1u-1jTJjr5Bn0VjMBOrA36xeBHjPPBuL7FKQ-q/pub  ) 
    - [MySQL의 갭락과 넥스트 키 락에 대해서](https://docs.google.com/document/d/12vBdawRbgs8vzRYG5e1r5WpOhRLfMhU0iXGWzVPZ5r8/edit?usp=sharing )
    - [MySQL 8.0의 lock read의 NOWAIT와 SKIP LOCKED 옵션에 대해서](https://docs.google.com/document/d/1zDXKv_stqUwORs5d_R0S6t41YofUL2Y8xUrQfBBybPM/edit?usp=sharing )
    - [UPDATE IN SELECT로 인한 교착 상태가 더 이상 발생하지 않게된 이야기](https://docs.google.com/document/d/e/2PACX-1vSebnl1juzCZsPd9vL0cGIwYtF4VxvNkK1r-jqwmsWGTBAUZSIci0qK2jHI76tIeia32sYRPLsPgqDx/pub )  
    - [MySQL의 ALTER TABLE 문 실행 시 주의 사항](https://docs.google.com/document/d/e/2PACX-1vQyhU_YDZ7HmqdjQanORZAhUHYEUn-b8fj2TKPlaPe5ksfEBGa9OKhCKFK5EsJnP61HJmf-rHDFw0_h/pub ) 
    - [MySQL(InnoDB)에서 각종 Lock 동작 알아보기](https://docs.google.com/document/d/e/2PACX-1vQ51LK8ym7wcjZmERz5RIB-AvH0QGIWYkbDs93Vv08Ml2i3kR-m4IwXxbo7FmWOFaIyCP41wnump3AN/pub ) 
    - [Waiting for table metadata lock 대처 방법, 복습](https://docs.google.com/document/d/13MdqBaFR0G9IX1e-LrOo4QG2sLBEyODFt_Gvq4NTEBM/edit?usp=sharing )  
    - [MySQL에서 발생할 수 있는 뜻밖의 데드락과 대응 방법](https://docs.google.com/document/d/e/2PACX-1vRp3cRZ-azq4bJFY52RT1U153lrrvVs7SwmQK8lbohnVKqL2TATKNdXaj-6eP4Kg8ho7yszasKX9ePj/pub )  
    - [MySQL 메타데이터 Lock에 대해서](https://docs.google.com/document/d/e/2PACX-1vQ6wX6K7Mtk7vn530JqUXdBUCgtQmNW81sQHYjCaKTb9zk2V1TFyP_CW641FoKxf1HmrpH5vKzeCeXA/pub ) 
    - [MySQL 온라인 DDL에서 Deadlock 오류가 발생하는 경우](https://docs.google.com/document/d/e/2PACX-1vRHjet16g6TCRP8mcS0wtFtoksZMSbVl78GfBkgtLxMuk3SKHDKP2kwnFZzmytlr8Dik22KKTa1JYKf/pub  ) 
        
  
### Redis 
- [레디스 게이트](http://www.redisgate.com/redis/command/latency.php ) 기능 설명
- [(영상) Redis 야무지게 사용하기](https://forward.nhn.com/2021/sessions/16 ) 
- [Redis 글 모음](https://gist.github.com/jacking75/5d9927851b22a539774301017e0cefd7 ) 
- [(유튜브) C++를 이용한 Redis 프로그래밍](https://www.youtube.com/watch?v=pGo1TnPH43Y&t=16s )  
- [(유튜브) Redis C# 프로그래밍](https://www.youtube.com/watch?v=09ufiNEWynk )
- [redis 라이브러리 사용 방법 정리](https://github.com/jacking75/how_to_use_redis_lib )
- [Redis를 활용한 다양한 시스템 설계](https://devs0n.tistory.com/92 )
- [Redis의 기본 데이터 유형 및 명령](https://docs.google.com/document/d/10mHFq-kTpGBk1-id5Z-zoseiLnTKr_T8N3byBZP5mEg/edit?usp=sharing )
- [Redis로 방문자수 구현하기](https://docs.google.com/document/d/e/2PACX-1vQFFSlvGJuDIjeEJM7UZdKRAC0Ps-CiBGFJQfZs_dLwko5cuIYMcbYWUZYeyb-K7M3pdMs9WAv7WD8B/pub )
- [Redis를 사용하여 동일 유저의 요청은 순차적으로 처리되도록 하기](https://docs.google.com/document/d/e/2PACX-1vRxEVk0OTmRYzDuDlq7BfrtkFh_9Gd9zcHArYfJS_oEOM3WO3TPpRIkbFybcPiwANufZ8R4BA2KHZDb/pub )
- [Redis를 사용한 분산 잠금 (SETNX, Redlock)](https://docs.google.com/document/d/e/2PACX-1vQjDwRvrzQPxPI0z9AGn2COp_HPed8Ny0yWnQ77ogoFTV21aYKVtIknXTuqtwR6IaBwQqmkBenCcA8t/pub )
- [Redisson 분산락을 이용한 동시성 제어](https://velog.io/@hgs-study/redisson-distributed-lock )
- [Redis 모델링](http://www.joinc.co.kr/modules/moniwiki/wiki.php/man/12/REDIS/DataModeling )



## Log
- [Elastic 가이드북](https://esbook.kimjmin.net/ )  
  


## 추천 학습 자료 
- [게임 서버 디자인 가이드, NDC2013](http://www.slideshare.net/devcatpublications/ndc2013-19986939 )
- [게임 분산 서버 구조](http://www.slideshare.net/hyunjikbae1/ss-35206140 )
- [스마트폰 온라인 게임에서 고려해야 할 것들](http://www.slideshare.net/hyunjikbae1/ss-39522754 )
- [C++ Korea 제9회 세미나 - 유지보수 편하게 게임 서버 만들기 (허린)](https://www.youtube.com/watch?v=NiDbkG_Eqpo )
- [System Design is About Tradeoffs](https://docs.google.com/document/d/e/2PACX-1vRGfnqxKy83IBU4n1E0hwH6mXHuyHeQjNOOzCoLByVpwaNlXWB0X7rcb_uSMZRjYs8F4zuUiToC0Ggc/pub )
- [상위 6가지 부하 분산 알고리즘](https://docs.google.com/document/d/e/2PACX-1vTVYE1-8WXfFZyIwcQyrDOmBhQhymRliglUalotjeqTjiNUDB5z4XVCLcchzzZZ0M4yTufUM9G0BXB6/pub  )  
  
  