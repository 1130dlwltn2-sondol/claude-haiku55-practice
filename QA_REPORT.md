# QA 보고서

- 책 제목: Claude Haiku 5.5로 저비용 AI 업무 처리하기
- 저자: 이준수 / 작성 기준일: 2026-10-11
- 저장소: ~/workspace/claude-haiku55-practice/
- 점검일: 2026-10-11

## 완료 항목

- chapters/01.md~08.md: 8장 본문 완성. 각 장에 학습 목표·선행 개념·쉬운 설명과 용어 풀이·가상 데이터 예시·번호 있는 실습·복사용 프롬프트·예상 결과·흔한 오류와 해결책·자가 점검표·관련 공식 출처([S1]~[S4]) 포함.
- book.md: 전체 통합 원고 (표지→도서 소개→학습 준비→목차→8장→실습 정답/예시→FAQ→참고 자료→마지막 안내 순서로 조립).
- project/: README.md, prompts.md, results.md, checklist.md, references.md 5개 파일 완성.
- data/sample_synthetic_inquiries.csv: 사용자가 제공한 가상 문의 12건 파일을 그대로 포함. 2·4·5·8장 실습에서 사용. BOM(utf-8-sig) 주의사항을 2장 본문에 명시.
- references.md: S1~S4에 제목·발행처·URL·열람일 표시. 원문 전문 복제 없음.
- README.md (책 소개), TOC.md (전체 목차), pages/ 15개 파일 (위키독스 페이지 순서 배치, 로컬のみ).
- assets/cover.png: 1000x1300 PNG, 아이보리·살구·브라운 계열, 애니메이션풍 로봇 삽화. 한글 깨짐 없음 (이미지 직접 확인).
- assets/ 개념도 3종: diagram-model-choice.png, diagram-routing.png, diagram-token-cost.png. 전부 '개념도' 표기, 한글 넘침 없음 (이미지 직접 확인). 1·6·7장 본문에서 참조.
- book.pdf: 실제 빌드 성공. fpdf2 + NotoSansCJK-KR 폰트로 39페이지 생성. 표지·목차·본문·표 페이지를 이미지로 렌더링해 한글 정상 확인.
- 문체 검사: Markdown 굵은 표시(**) 0건, 장식성 이모지 0건, '완벽 가이드'·'완전 정복' 등 과장 표현 0건 (grep 전수 검사).
- 보안 검사: 실제 API 키·개인정보·민감정보 없음. 모든 예제는 가상 데이터. 키 관리 원칙만 서술.
- 사실 표기: 발표일(2026-10-07)과 작성 기준일(2026-10-11) 분리 서술. 가격은 "2026-10-11 공식 문서 기준" 명시. 토큰 단가 인하율과 실제 청구 비용 절감률을 구분 서술. 벤치마크는 공급사 발표 수치로 표기하고 원본 재배포 없음. S4 시스템 카드는 직접 추출 미완료로 미확인 표기.
- 위키독스 업로드·외부 게시: 수행하지 않음.

## 미완료 항목

- 없음. 요구된 산출물은 전부 생성했다.

## 검증 불가 항목

- 공식 문서의 최신 상태: 가격은 2026-10-11 기준이며 이후 변동 여부를 이 환경에서 재확인하지 않았다. 본문에 기준일을 명시했다.
- S4 시스템 카드 세부 내용: 대용량 페이지 직접 추출 미완료로 미확인 표기했다.
- 실제 API 실행 결과: 이 책의 예상 결과는 가상 예시이며, 실제 모델 출력과 다를 수 있다. 본문에 명시했다.
- 위키독스 연동: 저자 검토 전까지 수행하지 않으므로 pages/ 파일의 실제 업로드 동작은 미검증이다.

## 파일 경로 정리

- 통합 원고: book.md
- 장별 원고: chapters/01.md ~ chapters/08.md
- 참고 자료: references.md
- 표지·도식: assets/cover.png, assets/diagram-*.png (3종)
- PDF: book.pdf (39페이지)
- 최종 프로젝트: project/README.md, project/prompts.md, project/results.md, project/checklist.md, project/references.md
- 실습 데이터: data/sample_synthetic_inquiries.csv
- 위키독스 연동용: README.md, TOC.md, pages/ (15개)
- 앞·뒤 부속 원고: front-intro.md, front-prep.md, appendix-answers.md, appendix-faq.md, appendix-closing.md
- 입력 파일 (원본 보관): 2026-10-11_topic5_sources.md, 2026-10-11_topic5_curriculum.md
