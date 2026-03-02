# Predicción de Clientes de Alto Valor
## Online Retail II — UCI Machine Learning Repository

### Problema de Negocio
¿Es posible predecir si un cliente realizará compras de alto 
valor basándonos en su comportamiento histórico de compras?

### Resultado Principal
Random Forest con F1-Score = 0.9953 y AUC-ROC = 0.9997

### Variables utilizadas (RFM)
- Recency: días desde la última compra
- Frequency: número de compras realizadas
- Ticket_Promedio: gasto promedio por compra
- Productos_Distintos: variedad de productos comprados
- Es_UK: cliente del Reino Unido (binaria)

### Modelos evaluados
| Modelo | F1-Score | AUC-ROC |
|---|---|---|
| Random Forest | 0.9953 | 0.9997 |
| Árbol de Decisión | 0.9965 | 0.9965 |
| SVM | 0.9930 | 0.9995 |
| Regresión Logística | 0.9906 | 0.9998 |

### Conclusión
La frecuencia de compra es el predictor dominante (43%).
La lealtad precede al valor económico, no al revés.

### Tecnologías
Python · scikit-learn · pandas · SHAP · Colab
```

Clic en **"Commit changes"**.

---

## Cómo queda tu repositorio final
```
online-retail-ml/
├── README.md          ← cara del proyecto, visible de entrada
└── notebooks/
    └── Proyecto_OnlineRetail.ipynb
└── OnlineRetail_Presentacion_Ejecutiva.pdf
```

---

## Para el futuro, cada vez que avances

El flujo se reduce a un solo paso:
```
Colab → Archivo → Guardar una copia en GitHub
