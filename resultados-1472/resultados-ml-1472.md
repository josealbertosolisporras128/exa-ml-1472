# Reporte de Análisis de Datos - Pandas

`jose solis Machine Learning pandas, NC 1472`

## 1. DataFrame Convertido
```text
     Gasolinera  Bombas  Litros_dia
0  Pemex Centro      12       25000
1      BP Norte      10       20000
2     Shell Sur       8       18000
3    Total Este      15       30000
4   Mobil Oeste       9       16000
5          Gulf      11       22000
```

## 2.1 Primeras Filas (head)
```text
     Gasolinera  Bombas  Litros_dia
0  Pemex Centro      12       25000
1      BP Norte      10       20000
```

## 2.2 Últimas Filas (tail)
```text
    Gasolinera  Bombas  Litros_dia
4  Mobil Oeste       9       16000
5         Gulf      11       22000
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Gasolinera      str
Bombas        int64
Litros_dia    int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column      Non-Null Count  Dtype
---  ------      --------------  -----
 0   Gasolinera  6 non-null      str  
 1   Bombas      6 non-null      int64
 2   Litros_dia  6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Litros_dia'
```text
count        6.000000
mean     21833.333333
std       5076.087732
min      16000.000000
25%      18500.000000
50%      21000.000000
75%      24250.000000
max      30000.000000
Name: Litros_dia, dtype: float64
```

## 4. Ordenar Ascendente por Litros_dia
```text
     Gasolinera  Bombas  Litros_dia
4   Mobil Oeste       9       16000
2     Shell Sur       8       18000
1      BP Norte      10       20000
5          Gulf      11       22000
0  Pemex Centro      12       25000
3    Total Este      15       30000
```

## 5. Ordenar Descendente por Bombas
```text
     Gasolinera  Bombas  Litros_dia
3    Total Este      15       30000
0  Pemex Centro      12       25000
5          Gulf      11       22000
1      BP Norte      10       20000
4   Mobil Oeste       9       16000
2     Shell Sur       8       18000
```

`jose solis Machine Learning pandas, NC 1472`