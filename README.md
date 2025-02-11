# Настройка рабочей среды для фронтенд-разработки

## 1. Регистрация почты в Proton Mail

Прежде чем начинать работу, вам потребуется рабочая почта. Для обеспечения конфиденциальности и удобства работы используем **Proton Mail**.

- Перейдите на [сайт Proton Mail](https://proton.me/mail).
- Зарегистрируйте новый аккаунт.
- Сохраните данные для входа.

## 2. Регистрация в ChatGPT

Для работы вам потребуется аккаунт в **ChatGPT**. Так как регистрация требует номер телефона, используйте виртуальный номер.

1. Купите виртуальный номер на одном из сервисов (например, [sms-activate.org](https://sms-activate.org) или [onlinesim.io](https://onlinesim.io)).
2. Перейдите на [сайт ChatGPT](https://openai.com/chatgpt).
3. Зарегистрируйтесь, используя вашу Proton Mail почту.
4. Подтвердите регистрацию через полученный SMS-код.

## 3. Регистрация на GitHub

**GitHub** — это платформа для хранения кода и совместной работы.

- Перейдите на [сайт GitHub](https://github.com/).
- Создайте новый аккаунт, используя вашу Proton Mail почту.
- Подтвердите регистрацию через email.
- Настройте двухфакторную аутентификацию (рекомендуется).

## 4. Установка Node.js и npm

**Node.js** и **npm** (Node Package Manager) необходимы для работы с JavaScript-проектами.

- Перейдите на [официальный сайт](https://nodejs.org/).
- Скачайте и установите **LTS-версию**.
- Проверьте установку в терминале:

```sh
node -v
npm -v
```

## 5. Установка редактора кода (VSCode)

**Visual Studio Code** — это удобный редактор для веб-разработки.

- Перейдите на [официальный сайт VSCode](https://code.visualstudio.com/).
- Скачайте и установите последнюю версию.
- Запустите VSCode и установите следующие расширения:
  - **ESLint** (проверка кода на ошибки)
  - **Prettier** (автоформатирование кода)
  - **GitHub Copilot** (AI-помощник в коде, опционально)

## 6. Установка Git

**Git** нужен для управления версиями кода.

- [Скачайте Git](https://git-scm.com/downloads).
- Установите, используя стандартные настройки.
- Проверьте установку:

```sh
git --version
```

- Настройте имя пользователя и email:

```sh
git config --global user.name "Ваше имя"
git config --global user.email "your-email@proton.me"
```

## 7. Установка Windows Terminal (для пользователей Windows)

Стандартный терминал Windows и PowerShell не так удобны для работы с разработкой. Рекомендуется использовать **Windows Terminal**.

- Перейдите в **Microsoft Store**.
- Скачайте и установите **Windows Terminal**.
- Откройте Windows Terminal и установите его в качестве основного терминала.

## 8. Доступ в Jira

**Jira** используется для управления задачами и проектами.

- Вам придет приглашение на email (Proton Mail).
- Перейдите по ссылке и зарегистрируйтесь.
- Ознакомьтесь с интерфейсом, куда будут приходить ваши задачи.

## 9. Финальная проверка

Проверьте, что всё установлено и работает:

```sh
node -v   # Должен показать версию Node.js
npm -v    # Должен показать версию npm
git --version   # Должен показать версию Git
code .    # Должен открыть VSCode
```

Теперь у вас готова рабочая среда, и можно приступать к выполнению задач в **Jira**!
