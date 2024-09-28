
# EN
**GenTimeSeriesPredictor** demonstrates how to build a causal convolutional neural network (CNN) model for time series forecasting using TensorFlow/Keras and scikit-learn.

He uses a causal convolutional neural network (CNN) to perform time series forecasting. The model is trained on a dataset of time series data and predicts future values based on historical trends.

## Installation:
Before running the project, make sure to have the following Python packages installed:
```bash
pip install numpy tensorflow scikit-learn matplotlib
```

## Usage
To use this model:
1. Clone the repository:
   ```bash
   git clone github.com/geniuszly/GenTimeSeriesPredictor
   ```
2. Run the script:
   ```bash
   python GenTimeSeriesPredictor.py
   ```
## Model Description
The model is based on a causal convolutional neural network (CNN), which is effective for time series prediction by ensuring that predictions for a given time step depend only on the previous time steps.

### Model Parameters:
- **start**: Starting index for data input.
- **count**: Number of data points to be used for training.
- **forecast_length**: Number of points to be predicted.
- **look_back**: Number of previous time points used for forecasting.
- **filters_1 & filters_2**: Number of filters in the first and second convolutional layers.
- **kernel_size_1 & kernel_size_2**: Size of the convolutional kernels in the layers.
- **epochs**: Number of training epochs.
- **batch_size**: Size of each mini-batch during training.

## Results
The model predicts the future values of the time series based on past data. Below is an example of the output plot, where:
- **Original Series**: Shows the actual historical data.
- **Real Values**: The actual values to be predicted.
- **Forecast**: The model's prediction of future values.

![image](https://github.com/user-attachments/assets/224005d1-ba2f-44b7-b297-1d86f886ff91)


## Future Work
- **Hyperparameter Tuning**: Experimenting with different model architectures.
- **Model Evaluation**: Using metrics such as MAE or RMSE for more accurate performance assessment.
- **Data Augmentation**: Applying different transformations to the dataset to enhance model robustness.

# RU
**GenTimeSeriesPredictor** демонстрирует создание модели причинно-следственной сверточной нейронной сети (CNN) для прогнозирования временных рядов с использованием TensorFlow/Keras и scikit-learn.\

Он использует модель причинно-следственной сверточной нейронной сети (CNN) для прогнозирования временных рядов. Модель обучается на наборе данных временного ряда и прогнозирует будущие значения на основе исторических трендов.

## Установка
Перед запуском проекта убедитесь, что установлены следующие Python-библиотеки:
```bash
pip install numpy tensorflow scikit-learn matplotlib
```

## Использование
Чтобы использовать эту модель:
1. Склонируйте репозиторий:
   ```bash
   git clone github.com/geniuszly/GenTimeSeriesPredictor
   ```
2. Запустите скрипт:
   ```bash
   python GenTimeSeriesPredictor.py
   ```

## Описание модели
Модель основана на причинно-следственной сверточной нейронной сети (CNN), которая эффективно выполняет прогнозирование временных рядов, гарантируя, что прогнозы для заданного временного шага зависят только от предыдущих временных шагов.

### Параметры модели:
- **start**: Начальный индекс для входных данных.
- **count**: Количество точек данных для обучения.
- **forecast_length**: Количество точек, которые нужно спрогнозировать.
- **look_back**: Количество предыдущих временных точек для прогнозирования.
- **filters_1 & filters_2**: Количество фильтров в первом и втором слоях свертки.
- **kernel_size_1 & kernel_size_2**: Размер ядра свертки в слоях.
- **epochs**: Количество эпох обучения.
- **batch_size**: Размер мини-пакета.

## Результаты
Модель прогнозирует будущие значения временного ряда на основе предыдущих данных. Пример выходного графика:
- **Исходный временной ряд**: Отображает фактические исторические данные.
- **Реальные значения**: Действительные значения для прогнозирования.
- **Прогноз**: Прогноз модели будущих значений.

![image](https://github.com/user-attachments/assets/2df3c8f9-2df6-475d-a3fc-1b1249b64434)


## Планы на будущее
- **Тонкая настройка гиперпараметров**: Эксперименты с различными архитектурами модели.
- **Оценка модели**: Использование метрик, таких как MAE или RMSE, для более точной оценки производительности.
- **Аугментация данных**: Применение различных преобразований к набору данных для повышения устойчивости модели.
