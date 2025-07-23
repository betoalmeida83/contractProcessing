Contract Processing System with PayPal Payment Integration

This Java project simulates the processing of contracts for a company that uses an online payment service (PayPal) for installment payments. The system receives contract data and the desired number of installments, generating the payment schedule with due dates and calculated amounts based on simple interest and service fees.

Features:
* Input of contract data (number, date, total value)
* Definition of the number of installments
* Generation of installment schedule with due date and amount including:
  - 1% simple interest per month
  - 2% payment fee per installment (PayPal)
* Output of a detailed payment plan to the console

Technologies used:
* Java 17
* java.time API (LocalDate)
* Object-oriented programming
