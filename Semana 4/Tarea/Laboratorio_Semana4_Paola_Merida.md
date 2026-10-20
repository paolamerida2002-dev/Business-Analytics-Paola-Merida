# Mini-lab Orange — Churn y CLV

## Captura del flujo completo de Orange
<img width="795" height="538" alt="Captura del flujo completo de Orange - Paola M" src="https://github.com/user-attachments/assets/06daa793-09cd-4dd9-8d5c-8bb5db83ea36" />

## Resultados de los modelos

Validación cruzada de 10 particiones, con clase objetivo «si».

| Modelo | Parámetro elegido | AUC |
| --- | --- | --- |
| Tree | Profundidad máxima = 4 | 0.718 |
| kNN | Número de vecinos = 100 | 0.652 |
| Logistic Regression | C = 1 | 0.780 |
| Random Forest | Parámetros por defecto | 0.710 |

## Conclusiones

La profundidad del árbol fue el parámetro que más cambió el resultado: al bajarla de 100 a 4, el AUC mejoró de 0.554 a 0.718.

Un árbol más grande no siempre predice mejor, porque puede memorizar los datos en lugar de aprender patrones útiles.

Si contactar cuesta menos, conviene contactar a más clientes; si cuesta más, debemos elegir un grupo más pequeño.
