---
title: Contradiction Logic Problem
tags: [logic, math, propositional-logic]
---

> [!note] Definition
> A contradiction (Conor/tradicshon) is a proposition that is always false (has a truth value of false in all cases).

# 1. กำหนด "Conor/tradicshon" คือประพจน์ที่มีค่าความจริงเป็นเท็จทุกครั้ง ประยุกต์ในข้อใด เป็น Conor/tradicshon

## Options:
**ก.** $(p \wedge q) \wedge \sim(p \vee q)$
**ข.** $(p \vee q) \wedge (\sim p \vee q)$
**ค.** $(p \rightarrow q) \wedge \sim(p \vee q)$
**ง.** $(p \leftrightarrow q) \wedge (p \vee q)$

## Solution:
**ก.** เป็น Conor/tradicshon
- ใช้กฎดีมอร์แกน: $\sim(p \vee q) \equiv \sim p \wedge \sim q$
- แทนค่าในสมมูล: $(p \wedge q) \wedge (\sim p \wedge \sim q)$
- จัดกลุ่ม: $(p \wedge \sim p) \wedge (q \wedge \sim q)$
- เนื่องจาก $p \wedge \sim p = F$ และ $q \wedge \sim q = F$, ดังนั้นผลลัพธ์เป็น $F \wedge F = F$ (เท็จทุกครั้ง)

**ข.** สามารถเป็นจริงได้ (เช่น ถ้า $q$ เป็นจริง)
**ค.** สามารถเป็นจริงได้ (เช่น ถ้า $p$ เป็นเท็จ, $q$ เป็นจริง)
**ง.** สามารถเป็นจริงได้ (เช่น ถ้า $p$ และ $q$ เป็นจริง)

> [!tip] Conclusion
> เฉพาะข้อ **ก.** เป็น Conor/tradicshon เพราะมีค่าความจริงเป็นเท็จทุกกรณี