# ICE4027-HW2
인공지능응용시스템 HW2 Hyperparameters의 변화에 따른 결과 분석

🐰 1번째 시도
- batch_size `64`로 변경

🐰 2번째 시도
- batch_size `256`로 변경

🐰 3번째 시도
- batch_size `256`로 고정
- optimizer `SGD`로 변경
- lr이 0.1로, 기존과 달라 비교가 불가하므로 lr을 0.002로 하여 다시 훈련해보아야 함

🐰 4번째 시도
- optimizer `SGD`
- lr = 0.002

🐰 5번째 시도
- optimizer가 Adamax일 때 learning rate를 0.004로 변경

🐰 6번째 시도
- optimizer가 Adamax일 때 learning rate를 0.02로 변경
