# Analisis-exploratorio-creditos

Una empresa de servicios financieros quiere analizar información de clientes para comprender qué factores se relacionan con el puntaje crediticio. El dataset contiene variables demográficas, financieras y de comportamiento de pago, como edad, ingresos, cantidad de cuentas bancarias, cantidad de tarjetas de crédito, deuda pendiente, historial crediticio, pagos atrasados y categoría de puntaje crediticio.

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos sobre información crediticia de clientes. Se busca identificar patrones asociados al puntaje crediticio, considerando variables demográficas, financieras y de comportamiento de pago.

## Objetivo del análisis

El objetivo del trabajo es realizar un análisis exploratorio de datos para identificar patrones relevantes y producir una primera interpretación del problema. Además, se busca analizar la relación entre variables como edad, ingresos, deudas, cantidad de préstamos, utilización del crédito y categoría de puntaje crediticio.

## Tipo de problema

Se trata de un problema exploratorio, orientado a comprender qué factores podrían estar relacionados con un puntaje crediticio bueno, estándar o bajo.

## Dataset

| Variable                   | Descripción                                                                                |
| -------------------------- | ------------------------------------------------------------------------------------------ |
| `ID`                       | Identificador único de cada registro del dataset.                                          |
| `Customer_ID`              | Identificador único de cada cliente.                                                       |
| `Month`                    | Período temporal al que corresponde el registro.                                           |
| `Name`                     | Nombre del cliente.                                                                        |
| `Age`                      | Edad del cliente.                                                                          |
| `SSN`                      | Número de seguridad social del cliente.                                                    |
| `Occupation`               | Ocupación o profesión del cliente.                                                         |
| `Annual_Income`            | Ingreso anual del cliente.                                                                 |
| `Monthly_Inhand_Salary`    | Salario mensual disponible del cliente.                                                    |
| `Num_Bank_Accounts`        | Cantidad de cuentas bancarias que posee el cliente.                                        |
| `Num_Credit_Card`          | Cantidad de tarjetas de crédito que posee el cliente.                                      |
| `Interest_Rate`            | Tasa de interés asociada a los préstamos del cliente.                                      |
| `Num_of_Loan`              | Cantidad de préstamos tomados por el cliente.                                              |
| `Type_of_Loan`             | Tipo de préstamo tomado por el cliente.                                                    |
| `Delay_from_due_date`      | Cantidad de días de retraso en el pago respecto de la fecha de vencimiento.                |
| `Num_of_Delayed_Payment`   | Cantidad de pagos realizados con retraso.                                                  |
| `Changed_Credit_Limit`     | Cambios en el límite de crédito del cliente.                                               |
| `Num_Credit_Inquiries`     | Cantidad de consultas de información crediticia realizadas sobre el cliente. |
| `Credit_Mix`               | Composición o combinación de productos crediticios del cliente.                            |
| `Outstanding_Debt`         | Monto de deuda pendiente del cliente.                                                      |
| `Credit_Utilization_Ratio` | Proporción de utilización del crédito disponible.                                          |
| `Credit_History_Age`       | Antigüedad del historial crediticio del cliente.                                           |
| `Payment_of_Min_Amount`    | Indica si el cliente realizó el pago mínimo correspondiente.                               |
| `Total_EMI_per_month`      | Monto total mensual destinado al pago de cuotas o préstamos.                               |
| `Amount_invested_monthly`  | Monto invertido mensualmente por el cliente.                                               |
| `Payment_Behaviour`        | Comportamiento de pago del cliente.                                                        |
| `Monthly_Balance`          | Balance mensual del cliente.                                                       |
| `Credit_Score`             | Categoría de puntaje crediticio del cliente.                                               |


## Organización del repositorio

- `data/`: contiene el dataset utilizado.
- `notebooks/`: contiene la notebook principal del análisis.
- `outputs/`: contiene gráficos o resultados generados.
- `README.md`: descripción general del proyecto.
- `.gitignore`: archivos que no se suben al repositorio.

## Herramientas utilizadas

- Python
- Polars
- NumPy
- Matplotlib
- Seaborn
- Git y GitHub



