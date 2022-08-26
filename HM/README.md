## Results

| 파일명(코드) | 설명 | 결과(val) | 결과(private) |
|:----------|:----------|:----------|:----------:|
| LGBMRegressor_RGS | LGBM + 하이퍼파라미터 튜닝(랜덤서치) | 1.9318 | 1.9436 | 
| PolynomialFeatures1 | LGBM + feature 개수 증가 | 1.9342 | x |
| PolynomialFeatures2 | LGBM + x_grouping + feature 개수 증가 | 1.9560 | x |
| PolynomialFeatures3 | Ensemble(RF,XGBoost,LGBM) + feature 개수 증가 | x | **1.9389** |
| re_LGBMRegressor_RGS | LGBM + 하이퍼파라미터 튜닝(랜덤서치)_new ver | 1.9321 | x |

* scaled features 사용 시, 성능 저하
