# HSE_SE_HW2
Небольшая программа для моделирования потока воды, чтобы передать в генерацию 
параметры SIZES и TYPES можно просто прописать их в main.cpp или передать в симейк
пример запуска
```
mkdir files
cd files
cmake ..
cmake --build .
./fluid  --file=../input.txt --p-type="FIXED(32, 16)" --v-type=DOUBLE --flow-type="FIXED(32, 16)
```
