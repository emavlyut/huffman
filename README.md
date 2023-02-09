# Алгоритм Хаффмана

Реализована библиотека и утилита для сжатия с помощью алгоритма Хаффмана.

__Usage__: `huffman-tool (-c | -d) -i FILE_IN -o FILE_OUT`

```
FLAGS:
  -h, --help                more information
  -c, --compress            encode file 
  -d, --decompress          decode file
  -i, --input FILE_IN       input file
  -o, --output FILE_OUT     output file
```

Примечание: input-file не должен быть пустым: попытка сжать таковой файл является ошибкой.
