# Rails 에러 메세지 모음

* `PendingMigrateError` : 마이그레이션 오류
  * 해결 : `rake db:migrate`
* `no routes match` : "라우츠파일에 너가 갈 곳이 어딘지 정의가 안되어있어"
  - 해결 : routes.rb에서 url주소를 '컨트롤러#액션'에 잘 보냈는지 확인
  - +form에서 url 잘 보냈는지 확인하기
* `unknown action` : "컨트롤러에 액션이 정의 안됬는데?"
  - 해결 : 컨트롤러 파일에 액션 정의하기
* `templete is missing`
  - 템플릿 = 사용자가 보는 뷰
  - 해결 : 뷰파일 확인하기
* `NoMethodError` : 메소드가 존재하지 않습니다
  * 에러메세지에서 틀린 부분을 확인하고
  * 해결 : 메소드와 관련된 부분에 오타가 있는지 확인
* 완벽하게 적었는데 동작이 안될때
  * 서버를 껏다켜봅시다
  * db를 날리고 다시 써봅시다
