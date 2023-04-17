## 추천시스템 - CF(협업필터링)_KNN

* 최종파일 : RecSys_CF_KNN.ipynb

* RMSE(train_test_split) : 

    k =  10 RMSE =  1.0273917739385365

    k =  20 RMSE =  1.013277766548689

    k =  30 RMSE =  1.0108864923478802

    k =  40 RMSE =  1.0107965767476177

    k =  50 RMSE =  1.0115477707625304
    
    
* RMSE(shuffle) : 

    k =  10 RMSE =  1.0276962402480696

    k =  20 RMSE =  1.0138971068281928

    k =  30 RMSE =  1.0127795779278337

    k =  40 RMSE =  1.0131177551253685

    k =  50 RMSE =  1.0140011322144393
    
    
* `train_test_split(x, y, test_size=0.25, stratify=y, random_state=12)`의 정확도가 근소하게 높고,

* 가장 높은 정확도는 다음과 같다 : k =  40 RMSE =  1.0107965767476177 (train_test_split)
