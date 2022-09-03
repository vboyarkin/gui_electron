# Курсовая работа по дискретной математике

## Нахождение компонент сильной связности графа

Графический интерфейс программы написан на JavaScript, HTML и CSS и использует фреймворк Electron для создания оконного приложения. Основная логика программы (работа с матрицами) реализована на C++ в качестве модуля, который вызывается из Electron с помощью Node-API

По первому алгоритму Уоршалла строится матрица односторонней связности. Затем вычисляется матрица сильной связности, как произведение
матрицы односторонней связности и транспонированной матрицы односторонней связности. Далее производится поиск компонент сильной связности
с помощью алгоритма нахождения компонент сильной связности орграфа по матрице сильной связности. Сложность алгоритма: $О(n^3)$.
