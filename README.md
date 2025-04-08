Cotton Leaf Disease Classification With Meta-Heuristic Algorithm (This notebook presents a deep learning-based classification framework enhanced with a meta-heuristic optimization algorithm. The model architecture integrates EfficientNetB3 for feature extraction, and the parameters of its dense layers are fine-tuned using a Genetic Algorithm (GA). The objective of using a meta-heuristic is to improve model generalization, optimize hyperparameters effectively, and avoid local minima that conventional methods may fall into. The notebook includes steps such as data preprocessing, model creation, fitness evaluation, and GA-based optimization. It concludes with performance evaluation using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.)
Cotton Leaf Disease Classification Without Meta-Heuristic Algorithm (This notebook implements a baseline deep learning model for cotton leaf disease classification without any optimization from meta-heuristic algorithms. It uses the same EfficientNetB3 architecture to ensure fair comparison with the optimized model. The training process involves conventional hyperparameter settings, and the model is evaluated using the same dataset and metrics as the optimized version. This serves as the control experiment to evaluate the performance improvement gained from the use of a meta-heuristic algorithm in the previous notebook.)
Explainable AI Results of LIME and SHAP (This notebook demonstrates the application of Explainable Artificial Intelligence (XAI) techniques—LIME (Local Interpretable Model-agnostic Explanations) and SHAP (SHapley Additive exPlanations)—to interpret the predictions of the trained cotton leaf disease classification model. LIME helps identify the most influential regions in individual input images that contribute to specific predictions by perturbing the input and observing model behavior. SHAP, on the other hand, offers a unified measure of feature importance by calculating Shapley values, providing both global and local explanations of the model’s behavior. Together, these methods enhance model transparency, facilitate trust in AI predictions, and support informed decision-making in precision agriculture by revealing the rationale behind the model's outputs.)
Dataset Link (https://www.kaggle.com/datasets/ataher/cotton-leaf-disease-dataset/data)
