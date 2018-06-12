# AutoML-Experiments

Estes são dados comparativos preliminares com o objetivo exclusivo de monitorar o avanço da solução de AutoML na plataforma Marvin.

Os datasets selecionados possuem menos de 1000 registros (linhas) e menos de 100 features (colunas). Esta seleção foi feita para simplificar e agilizar o processo de treinamento e otimização dos modelos.

| OpenML ID| dataset           | flow_name                                                      | measure   |    value |   automl_value |        delta |
|---------:|:------------------|:---------------------------------------------------------------|:----------|---------:|---------------:|-------------:|
|        2 | anneal            | weka.LogitBoost_DecisionStump(3)                               | f_measure | 0.997506 |       0.95     |  -0.047506   |
|       50 | tic-tac-toe       | weka.SMO_PolyKernel(1)                                         | f_measure | 1        |     nan        | nan          |
|       54 | vehicle           | sklearn.pipeline.Pipeline(..., clf=sklearn.svm.classes.SVC)(1) | f_measure | 0.869092 |       0.829412 |  -0.0396804  |
|      311 | oil_spill         | classif.lda(11)                                                | f_measure | 0.966721 |       0.714286 |  -0.252435   |
|      839 | kdd_el_nino-small | weka.RotationForest_PrincipalComponents_J48(14)                | f_measure | 0.962931 |       0.980392 |   0.0174612  |
|      841 | stock             | weka.Decorate(1)                                               | f_measure | 0.973682 |       0.962963 |  -0.010719   |
|     1016 | vowel             | classif.IBk(5)                                                 | f_measure | 1        |       1        |   0          |
|    40693 | xd6               | weka.kf.RandomForest(1)                                        | f_measure | 1        |       1        |   0          |
|    40705 | tokyo1            | weka.kf.RandomForest(1)                                        | f_measure | 0.934157 |       0.936508 |   0.00235094 |
