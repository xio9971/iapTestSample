# iapTestSample
#### 인앱결제 테스트

+ 처음에는 프로젝트에 storeKit을 사용하여 인앱결제를 구현 했는데 appstoreconnect에 등록한 정보 가져올수 없음, 센드박스 테스트계정 사용 불가능 문제 발생
(storeKit 에 대한 정보 확인 필요)

+ 시뮬레이터로 인앱결제 연동시 아이템을 가져오는 부분부터 unkown error가 발생
  Ios14, xcode12 버전에서 동일한 오류가 발생한다고 함 (기기에서 앱빌드하여 직접 실행 후 해결)

+ appstoreconnect에 등록한 앱 내 구입 아이템을 가져와서 인앱결제를 하기위해서는
계약 - 유료 앱이 활성화 상태여야 가능함 확인 ( 유료 앱 활성화 하기위에서는 사업자 등록 번호가 필요 하기 때문에 회사 개발자 계정 사용 해서 해결)
