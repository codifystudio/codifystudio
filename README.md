<h1 align="center">codify</h1>

<p align="center"><strong>Rust — движки, системные утилиты, десктоп.<br/>Быстро, безопасно, в одном бинарнике.</strong></p>

---

### О чём я

Разрабатываю системное ПО на Rust — там, где важны предсказуемая производительность, безопасность памяти и полный контроль над каждой зависимостью. Мне интересно идти от нуля: разбираться в спецификациях и протоколах, строить собственные движки и инструменты, а не собирать обёртки над чужими библиотеками. Каждый проект довожу до релиза: unit-тесты на критические гарантии, сборка под три платформы, контрольные суммы для каждого артефакта.

- **Браузерные технологии** — собственный движок рендеринга и лёгкий браузер поверх него;
- **Системные утилиты** — мониторинг и обслуживание ПК без фоновых служб, рекламы и лишнего;
- **Кроссплатформенный GUI** — нативные интерфейсы на egui/eframe: один исходник, три ОС, один исполняемый файл.

### Проекты

| Проект | Описание |
|---|---|
| **[Strata](https://github.com/codifystudio/strata)** | Независимый браузерный движок на Rust: HTML, CSS, layout и paint — без системных WebView. |
| **[Sierra](https://github.com/codifystudio/sierra)** | Лёгкий браузер на Rust с дизайном в духе Яндекс, Chrome и Safari. Бинарник — около 2 МБ. |
| **[NEXUS PC PRO](https://github.com/codifystudio/nexus-pc-pro)** | Мониторинг и обслуживание ПК: процессы, диски, сканер мусора, штатные инструменты. Rust + egui, готовые сборки для Windows, macOS и Linux. |

### Принципы

- **Один бинарник** — приложение запускается без установщиков, рантаймов и внешних зависимостей;
- **Производительность** — профилировать, а не предполагать; тяжёлые операции — вне UI-потока;
- **Безопасность по умолчанию** — белые списки путей с fail-closed, минимум привилегий, явное подтверждение опасных действий;
- **Честный код** — тесты закрепляют гарантии, CI собирает под каждую платформу, каждый релиз сопровождается SHA256.

### Технологии

<p>
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img alt="egui" src="https://img.shields.io/badge/egui-2D2D2D?style=flat-square&logo=rust&logoColor=white" />
  <img alt="wgpu" src="https://img.shields.io/badge/wgpu-4A4A4A?style=flat-square&logo=webgpu&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python%20%2F%20Qt-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img alt="Windows" src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" />
  <img alt="macOS" src="https://img.shields.io/badge/macOS-555555?style=flat-square&logo=apple&logoColor=white" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

### Контакты

Вопросы и предложения по проектам — через [Issues](https://github.com/codifystudio/nexus-pc-pro/issues) в соответствующем репозитории.
