# Court Decision Prediction
 
## Contest Link:

[DACON] https://dacon.io/competitions/official/236112/overview/description

-----
## Dataset Info:

- ID : 사건 샘플 ID

- first_party : 사건의 첫 번째 당사자

- second_party : 사건의 두 번째 당사자

- facts : 사건 내용

- first_party_winner : 첫 번째 당사자의 승소 여부 (0 : 패배, 1 : 승리)

------
## Submissions:

- submission_0 : Bert tokenizer + DNN(train only)
- submission_1 : Bert tokenizer + DNN(train + val)
- submission_2 : Bert tokenizer tpot automl
- submission_3 : Bert tokenizer + tpot automl(upsampling)
- submission_4 : Bert tokenizer + DNN(upsampling)
- submission_5 : Bert tokenizer + DNN(downsampling)

Current Best Score: submission_4 with 0.50967