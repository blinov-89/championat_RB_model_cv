# championat_RB_model_cv

Задача

В рамках чемпионата участникам предстоит создать и обучить ML-модель, которая поможет на основе выявления аномалий на представленных фотоснимках формировать фокусированные проблемно-ориентированные выборки, что в свою очередь позволит более продуктивно организовать работу инспекторов за счет отказа от используемой в настоящее время в республике многоуровневой проверки фотоотчетов методом случайной выборки.

Решение:

За основу взят предоставленный baseline,
датасет train переразмечен
трансформацию изображений не делал, так как ухудшает качество на данном датасете
добавлены фото в каждый класс
пред обученная модель resnet18
в качестве оптимизатора SGD with momentum 
обучение на 50 epoch

> Score = 0.871227

Призовое 15 место с чемпионате РБ

