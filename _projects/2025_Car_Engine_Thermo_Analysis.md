---
layout: project
title: Car Engine Analysis
description: Thermodyanic Analsis of Car Engine 
image: /assets/images/Car_eng.png
---







==============================
FOUR-STROKE IC ENGINE
==============================
1. Intake Stroke
- Intake valve opens
- Piston moves down
- Air–fuel mixture enters the cylinder

2. Compression Stroke
- Piston moves up
- Air–fuel mixture is compressed
- Temperature and pressure increase

3. Power Stroke
- Spark ignites the air–fuel mixture
- Combustion increases pressure
- Expanding gases push piston down
- Useful work is produced

4. Exhaust Stroke
- Exhaust valve opens
- Piston moves up
- Exhaust gases are pushed out


==============================
ENGINE CONTROL VOLUME
==============================
- Air + fuel enter the system
- Exhaust gases leave the system

Mass balance:
m_dot_in = m_dot_out

Steady state:
dm/dt = 0

==============================
ENTROPY BALANCE (CONTROL VOLUME)
==============================
ΔS_sys = ∫(δQ_rev / T) + S_gen

Entropy generation:
S_gen ≥ 0

Main sources of entropy generation:
- Combustion irreversibility
- Finite temperature heat transfer
- Friction

Minimizing entropy generation:
- Increases useful work output

==============================
STEADY-STATE ENERGY BALANCE
==============================
ΔU = Q_in - Q_out - W

For steady state:
ΔU = 0

Therefore:
W_out = Q_in - Q_out

Heat transfer terms:
Q_in  = m c (T3 - T1)
Q_out = m c (T4 - T2)

Work output:
W = m c [ (T3 - T1) - (T4 - T2) ]

Net work rate:
W_dot_net = m_dot_fuel × η_engine

==============================
THERMAL EFFICIENCY
=============================
η = W_out / Q_in

η = 1 - (Q_out / Q_in)

For an ideal heat engine:
η = 1 - (T_L / T_H)

==============================
INCREASING ENGINE EFFICIENCY
==============================

To increase efficiency:
- Increase high temperature (T_H)
- Decrease low temperature (T_L)
Knock (autoignition): Increasing r raises cylinder temperature and pressure during compression so there is less high quality
Mechanical stress / durability: Higher pressures raise peak mechanical loads
on pistons which means more expensive and higher quality materials
Real efficiency vs ideal: Real engines have friction, pumping losses, non-ideal combustion, and heat transfer losses, which makes the real engine much less efficient
Alternative approach - turbocharging: Instead of increasing static compression ratio, many engines use a boosted intake (turbo/supercharging) to increase the m dot. Turbocharging increases power and can increase thermal efficiency at part load, but it increases intake temperature.
Knock (autoignition): Increasing r raises cylinder temperature and pressure during compression so there is less high quality
Mechanical stress / durability: Higher pressures raise peak mechanical loads
on pistons which means more expensive and higher quality materials
Real efficiency vs ideal: Real engines have friction, pumping losses, non-ideal combustion, and heat transfer losses, which makes the real engine much less efficient
Alternative approach - turbocharging: Instead of increasing static compression ratio, many engines use a boosted intake (turbo/supercharging) to increase the m dot .Turbocharging increases power and can increase thermal efficiency at part load but it increases intake temperature.