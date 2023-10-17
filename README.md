# Assessment of flexible highway pavement deflection using Intelligent Pavement Assessment to estimate deflection in adjacent lanes with the use of Machine Learning.
The effective management of road pavements plays a crucial role in safety and the economy. The ability to predict deflection in road
lanes is essential for identifying areas that require maintenance. To achieve this, dynamic equipment surveys such as the Intelligent
Pavement Assessment (iPAVe) can be employed in lieu of static methods, like the Falling Weight Deflectometer (FWD), commonly used
in Brazil. Thus, this study aims to compare the predictive capability of deflection in road pavements based on adjacent lane surveys
using two Machine Learning models: Artificial Neural Network (ANN) and Random Forest (RF). Geospatial data were processed
and divided into training (2/3) and test (1/3) sets. The ANN was configured with optimized parameters after multiple tests, with 400
epochs, while the RF utilized 500 estimators. Both models underwent cross-validation. The results demonstrated that the RF model
outperformed the ANN in terms of performance. During cross-validation, the ANN showed an average MSE of 363.43 and an average
MAE of 11.84. In contrast, the RF model achieved an average MSE of 0.34 and an average MAE of 0.02. The average RMSE of the ANN
was 16.15, while the RF model recorded an average RMSE of 0.34. Furthermore, the average R2 of the ANN was 0.30, whereas the
average R2 of the RF reached 0.99. These results indicate that the RF model provided more accurate and consistent predictions of
deflections in adjacent lanes. Thus, the study provides a promising foundation for the development of deflection prediction models in
road pavements. However, challenges such as the temporality of surveys and the comparison of distinct methods were identified.
Future research can focus on improving training data, obtaining data from both sides of the lane using iPAVe, and conducting more
in-depth studies on the influences of variables on the model. The results of this study may have practical implications for pavement
management and highway maintenance.
