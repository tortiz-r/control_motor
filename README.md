# Práctica de control de un motor de corriente continua
Práctica de la asignatura "Sistemas Dinámicos y Realimentación" del Grado en Física de la UCM. El proyecto consiste en usar modelos de Simulink, en Matlab, para aplicar distintas técnicas de control y realimentación a un motor de corriente continua para estudiar el efecto que tienen dichas técnicas en el comportamiento y manejo del motor.


Estructura del repo:

```
control_motor/
├── Modelos/
│   ├── P2_Modelo_4_1_MotorIdeal.slx
│   ├── P3_Modelo_4_2_SenalPWM.slx
│   ├── P3_Modelo_4_6_EncodersCuadratura.slx
│   ├── P3_Modelo_4_7_MotorReal.slx
│   ├── P4_Modelo_4_10_RealimEstim.slx
│   ├── P4_Modelo_4_11_RealimEstim_ContrInt.slx
│   ├── P4_Modelo_4_9_SistRealim.slx
│   ├── P5_Modelo_ContrIntDiscret.slx
│   └── P6_Modelo_4_15_MotorCompleto.slx
├── P2_Estudio_Pos_Vel/
│   ├── P2_AnalisisDatos.mlx
│   ├── v10.mat
│   ├── v12.mat
│   ├── v2.mat
│   ├── v4.mat
│   ├── v6.mat
│   └── v8.mat
├── P4_Estudio/
│   ├── P4_EstimInt_0.01.mat
│   ├── P4_EstimInt_0.10.mat
│   ├── P4_EstimInt_1.00.mat
│   ├── P4_EstudioPosicionPolos_EstimInt.mlx
│   ├── P4_EstudioPosicionPolos_RealimDir.mlx
│   ├── P4_RealimDir_0.01.mat
│   ├── P4_RealimDir_0.10.mat
│   ├── P4_RealimDir_1.00.mat
│   ├── P4_RealimDir_10.00.mat
│   └── P4_funcion_obt_datos_graficas.mlx
├── P6_Estudio/
│   ├── imgs/
│   ├── P6_Plot_ExecMotor.mlx
│   └── P6_vars_final.mlx
└── README.md
```