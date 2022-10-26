# EmoRecoNN
 Different models of machine learning and neural networks.
 
Здесь лежат архитектуры различных классификаторов на основе методов машинного обучения и нейронных сетей. Методы обучались на предварительно обработанных изображениях, в качестве признаков используются суммы вертикального и горизонтального расстояний от верхнего левого угла изображения до ключевой точки на лице. Точки находились с помощью библиотеки dlib. Для каждого изображения из общего набора ( ~ 2000 изображений) выделяется  68 признаков. Все данные хранятся в CSV файле. Классификация 7-классовая: злость, грусть, счастье, удивление, страх, отвращение и нейтральная эмоция. Помимо этого будут добавляться сверточные нейронные сети.

!В сборниках нет сохраненных весов моделей, однако при повторном обучении accuracy отличается менее чем на 0.2!

SimpleNN — сборник простых нейронных сетей для классификации эмоций на изображениях, показывающих accuracy равное 0.6 - 0.8.

ML — сборник популярных методов машинного обучения. Добавлю со временем. 

Sesa — архитектуры нейронных сетей, показавших наилучший результат работы. SesaConvNN: accuracy 0.87 - 0.90; Sesa_lrp: accuracy 0.87 - 0.89.

SimpleConvNN - сборник простых сверточных сетей, покаывающих accuracy равное 0.75.

AdvancedConvNN - сборник простых более продвинутых сверточных сетей, покаывающих accuracy равное 0.72 - 0.80. В отличии от SimpleConvNN, применяются нормализация и дропаут.

alexnet+vgg.ipynb - тесты с дообучением AlexNet и VGG на основе блокнота их курсов МФТИ.
