# Evision-HV
EVI$ION x 한화비전 스터디 및 프로젝트 C · C++ · Qt · Linux · Raspberry Pi

9주 동안 엣지 디바이스 개발 기초를 함께 공부하고, 이어서 4주 동안 팀 프로젝트를 진행합니다. 이 레포는 스터디 기간에는 깃허브 실습용으로, 프로젝트 기간에는 실제 협업용으로 사용합니다.

---------------------------------------
🚀 1주차: Git & GitHub

인원이 많은 프로젝트에서 협업하려면 git은 필수입니다. 1주차에는 git과 GitHub가 무엇인지, 실제로 어떻게 쓰는지 직접 해 보면서 익힙니다.

💡 이미 git을 잘 쓴다면? 잔디(GitHub contribution) 인증 시 1주차 면제 가능

진도
순서	내용
1	동영상 수강: 깃허브 모르면 바이브코딩 못합니다 | 비개발자를 위한 깃허브 설명
2	동영상 수강: (유노코딩) 깃과 깃허브가 처음인 당신에게 (8개)
3	Git 실습: Learn Git Branching
· main: git 기본 1, 2, 3, 4
· main: 다음 단계로 1
· 원격 (전부)
4	GitHub 실습: 아래 실습 가이드 따라 하기
5	최종 실습: VSCode(또는 본인이 쓰는 에디터)와 git을 연결해 로컬에서 commit / push / merge 해 보기
🛠 GitHub 실습 가이드
0. 준비
GitHub 계정을 만들고, 계정 아이디를 GitHub 관리 담당(초현)에게 알려 주세요. 레포에 초대해 드립니다.
초대 메일이 오면 수락해 주세요.
1. 내 레포지토리 만들어 보기

GitHub에서 New repository로 자유롭게 레포를 하나 만들어 봅니다.

2. 이 레포 클론하기
bash
git clone https://github.com/chohyunKANG/Evision-HV.git
cd Evision-HV
3. 브랜치 만들기
bash
git checkout -b practice/본인이름
# 예: git checkout -b practice/chohyun
4. 파일 추가하고 커밋하기

practice/ 폴더 안에 본인이름.md 파일을 만들고 자기소개를 한 줄 적어 주세요.

bash
git add practice/본인이름.md
git commit -m "add: 본인이름 자기소개"
5. 내 브랜치 푸시하기
bash
git push origin practice/본인이름
6. main에 병합하고 푸시하기
bash
git checkout main
git pull origin main          # 다른 사람이 먼저 올린 내용 받기
git merge practice/본인이름
git push origin main

⚠️ push가 거절되면 다른 사람이 먼저 올린 것입니다. git pull origin main을 한 번 더 하고 다시 push하세요. ⚠️ 다른 사람의 파일은 수정하지 마세요. 자기 이름 파일만 다루면 충돌이 나지 않습니다.

7. 확인

GitHub 레포 페이지의 practice/ 폴더에 내 파일이 보이면 성공입니다 🎉
