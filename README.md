## Документация информационной системе Edu Platform

### Основные разделы
  - `.github/workflows` - все пайплайны для `github-actions`
  - `xor-go` - монорепа со всеми `go` сервисами. Описание — [Go_general_readme.md](xor-go/XOR_GO_README.md)
  - `xor-java` - монорепа со всеми `java` сервисами
  - `xor-py` - монорепа со всеми `py` сервисами

### Документация
- ISO 42010 Software architecture document: [Xority_ISO42010_SAD.pdf](docs/ISO/Xority_ISO42010_SAD.pdf)
- ГОСТ 19 ТЗ на ИС: [TZ_General_Edu_Platform.pdf](docs/GOST/TZ_General_Edu_Platform.pdf)
- ГОСТ 19 ТЗ на подсистему курсов: [Go_general_readme.md](docs/GOST/TZ_Courses_Edu_Platform.pdf)
- ПЗ на подсистему курсов: [PZ_Courses.pdf](docs/GOST/PZ_Courses_Edu_Platform.pdf)
- РП на подсистему курсов: [PR_Courses.pdf](docs/GOST/RP_Courses_Edu_Platform.pdf)
- ПМИ на ИС: [PMI_General.pdf](docs/GOST/PMI_General_Edu_Platform.pdf)
- ПМИ на подсистему курсов: [PMI_Courses.pdf](docs/GOST/PMI_Courses_Edu_Platform.pdf)

- ATAM (Architecture tradeoff analysis): [Xority_ATAM.pdf](docs/ISO/Xority_ATAM.pdf)

### Описание и стек
[COURSES_README.md](./services/courses/README.md)

### Спецификации
[Courses API_README.md](xor-go/services/courses/docs/API_README.md)

[Courses Open API](/oapi/courses.yaml)

### Нейминг
  - сервисы называются во множественном числе без приставки `[service-name]`, например, сервис `payments`
  - папки проектов соответствуют названиям проектов 1 в 1
