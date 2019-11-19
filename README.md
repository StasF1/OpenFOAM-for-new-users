# Об OpenFOAM-for-new-users
Репозиторий создан для помощи в освоении [OpenFOAM](https://github.com/StasF1/OpenFOAM-for-new-users/wiki/About) незнакомым с этой средой человеком.

Обучающие кейсы можно найти в [**OpenFOAM-for-new-users.Wiki**](https://github.com/StasF1/OpenFOAM-for-new-users/wiki)

# Требования
- [OpenFOAM v4.x или v5.x](https://github.com/StasF1/OpenFOAM-for-new-users/wiki/%5Binstall%5D-Official) для проекта [_snappyHexMesh/_](https://github.com/StasF1/OpenFOAM-for-new-users/tree/master/tutorials/snappyHexMesh)
- [OpenFOAM v6 и выше](https://github.com/StasF1/OpenFOAM-for-new-users/wiki/%5Binstall%5D-Official) для остальных проектов
- Для проекта [_bladeMachines/_](https://github.com/StasF1/OpenFOAM-for-new-users/tree/master/tutorials/bladeMachines):
	+ Дополнение [DensityBasedTurbo](https://github.com/StasF1/OpenFOAM-for-new-users/wiki/%5Binstall%5D-Additions#densitybasedturbo) к [OpenFOAM-extend-3.0](https://github.com/StasF1/OpenFOAM-for-new-users/wiki/%5Binstall%5D-Extend#openfoam-extend-30) или [OpenFOAM-1.6-ext](https://openfoamwiki.net/index.php/Installation/Linux/OpenFOAM-1.6-ext)
	+ [OpenFOAM-extend-4.0](https://github.com/StasF1/OpenFOAM-for-new-users/wiki/%5Binstall%5D-Extend#openfoam-extend-40) 

# [История версий](https://github.com/StasF1/dualFuelEngine/releases)
| Версия | Описание | Скачать архив 📥 |
|-------:|----------|------------------|
| [v0.1-beta](https://github.com/StasF1/OpenFOAM-for-new-users/tree/v0.1.1-beta) | Созданы проекты *bladeMachines*/, *cloneExistingSolver/*, *snappyHexMesh*/ | [.tar.gz](https://github.com/StasF1/OpenFOAM-for-new-users/archive/v0.1.1-beta.tar.gz), [.zip](https://github.com/StasF1/OpenFOAM-for-new-users/archive/v0.1.1-beta.zip) |

# Структура
```gitignore
OpenFOAM-for-new-users-0.1-beta
├── etc # скрипты устанавливающие OpenFOAM (от v4.x до v7), его расширенные версии и дополнения
└── tutorials # обучающие проекты, описание которых можно найти в Wiki репозитория
    ├── bladeMachines
    │   ├── DensityBasedTurbo # требует дополнения DensityBasedTurbo к 1.6-ext или extend-4.0
    │   │   ├── AxialMixerMRFCHTSteadyState
    │   │   ├── AxialMixerMRFCHTUnsteady
    │   │   ├── AxialMixerMRFFSISteadyState
    │   │   ├── AxialRotorMRF
    │   │   ├── AxialRotorSRF
    │   │   ├── AxialStageMRFRotating
    │   │   ├── bumpMinf0675
    │   │   └── forwardStep
    │   └── extend-4.0 # требует OpenFOAM-extend-4.0
    │       ├── steadyCompressibleFoam
    │       │	├── 2bump
    │       │	└── transonicBump
    │       ├── steadyCompressibleMRFFoam
    │       │	├── axialRotorStatorMRF
    │       │	├── axialTurbineMixingPlane
    │       │	├── bentRotorStator
    │       │	└── simpleRotorStator
    │       ├── steadyCompressibleSRFFoam
    │       │	├── bentBlade
    │       │	└── simpleBlade
    │       └── steadyUniversalMRFFoam
    │           ├── axialTurbineGgiJump
    │           └── axialTurbineMixingPlane
    ├── cloneExistingSolver # протестирован на OpenFOAM v6
    │   ├── prism
    │   └── quadPiston
    └── snappyHexMesh # протестирован на OpenFOAM v5
        ├── case
        ├── geometry
        └── mesh
```
