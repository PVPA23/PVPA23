<div align="center">

# Vinicius Albuquerque
### Desenvolvedor Java & Programador de Robótica (FRC & FTC)

[![Equipe FRC](https://img.shields.io/badge/FRC_Team-Prodixy_%239195-blue?style=for-the-badge&logo=first)](https://github.com/PVPA23)
[![Categoria FTC](https://img.shields.io/badge/FTC-FIRST_Tech_Challenge-orange?style=for-the-badge&logo=first)](https://github.com/PVPA23)
[![Linguagem](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://github.com/PVPA23)

</div>

---

## Sobre Mim

Sou estudante e desenvolvedor focado em **Robótica de Competição**, automação e sistemas embarcados. Faço parte da equipe **Prodixy (#9195)**, onde atuo no desenvolvimento de software para robôs nas categorias **FRC (FIRST Robotics Competition)** e **FTC (FIRST Tech Challenge)**.

- Experiência prática na arquitetura **Command-Based** da **WPILib** em Java.
- Desenvolvimento de sistemas de **Visão Computacional** e alinhamento automático utilizando **PhotonVision** e **AprilTags**.
- Integração e controle de motores e hardware (**REV Robotics / SparkMax**, motores **NEO Brushless** e **CIM Brushed**, **CTRE Phoenix**).
- Criação de interfaces de telemetria e calibração em tempo real via **Shuffleboard** e **SmartDashboard**.

---

## Tecnologias & Ferramentas

<div align="center">

| Linguagens & Base | Robótica & Controle (FRC/FTC) | Visão & Autônomo | Ferramentas |
| :---: | :---: | :---: | :---: |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) | ![WPILib](https://img.shields.io/badge/WPILib-Command--Based-red?style=flat-square) | ![PhotonVision](https://img.shields.io/badge/PhotonVision-AprilTags-00A8E8?style=flat-square) | ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) |
| ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white) | ![REVLib](https://img.shields.io/badge/REVLib-SparkMax-orange?style=flat-square) | ![PathPlanner](https://img.shields.io/badge/PathPlanner-Autonomous-purple?style=flat-square) | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| | ![AdvantageKit](https://img.shields.io/badge/AdvantageKit-Telemetry-green?style=flat-square) | ![Shuffleboard](https://img.shields.io/badge/Shuffleboard-Dashboard-blue?style=flat-square) | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

</div>

---

## Projetos em Destaque — Equipe Prodixy #9195

### [Muke](https://github.com/PVPA23/Muke) *(Temporada FRC 2026)*
Código completo de controle do robô utilizando arquitetura **Command-Based (WPILib 2026)**:
- **DriveSubsystem:** Tração diferencial (*Arcade Drive*) com 4 controladores **SparkMax** e 3 modos dinâmicos de pilotagem (`NORMAL`, `SLOW` e `AGGRESSIVE`) suavizados com `SlewRateLimiter`.
- **IntakeSubsystem:** Controle híbrido combinando motor **CIM (Brushed)** contínuo em Teleop e motor **NEO (Brushless)** com máquina de estados em *Toggle/Latch* (`FORWARD`, `REVERSE`, `STOP`) e proteção de corrente/limit switches.
- **VisionSubsystem:** Monitoramento de alvos e estimativa de distância/ângulo via **PhotonVision**.

### [VisioN](https://github.com/PVPA23/VisioN) *(Temporada FRC 2025)*
Sistema dedicado de **Visão Computacional e Alinhamento Automático**:
- **Alinhamento por AprilTags (`AlignToAprilTagCommand`):** Controle proporcional ($k_P$) com compensação de potência mínima (`MinPower`) ajustável em tempo real pelo **Shuffleboard**.
- **Dashboard do Piloto e Visão:** Integração de câmera USB de pilotagem + stream HTTP do **PhotonVision**, exibindo métricas ao vivo de *Yaw (tx)*, *Pitch (ty)*, área do alvo, latência e telemetria elétrica dos motores.
