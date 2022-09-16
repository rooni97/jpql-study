# jpql-study
jpql 학습용 소스코드

JPQL에서 엔티티를 직접 사용하면 SQL에서 해당 엔티티의 기본 키 값을 사용
select m from Member m where m.team = :team
select m from Member m where m.team in :teams
- team을 컬렉션으로 전달해도 동일하게 동작한다.
