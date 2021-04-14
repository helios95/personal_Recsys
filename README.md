# personal_Recsys
개인화 추천

스마일게이트 모바일 게임 에픽세븐의 스토브 커뮤니티에서 개인화 추천 기능 제공


대상
온스토브 에픽세븐 커뮤니티

범위
 - 온스토브 에픽세븐 커뮤니티를 대상으로 로그인한 가입자에게 개인별 맞춤 컨텐츠를 제공
 - 협업필터링을 이용하여 나와 활동 이력이 비슷한 사용자가 좋아하는(read) 게시글 추천

추천 대상 카드
유저가 아직 소비하지 않은 카드 중 선호할 만한 게시글의 집합을 제공

추천 방법론
 Matrix Factorizaion 알고리즘 중 SVD(Singular Value Decomposition)이용


구현방안 
 Implicit Feedback에서 선호도를 계산하여 특정한 유저/아이템간 상호작용에 대한 평점 예측
 각 컨텐츠별 선호도
- 클릭횟수
- 좋아요
- 댓글
