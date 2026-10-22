# Lista de Tareas en Flutter

App de lista de tareas hecha con Flutter, como práctica integradora de Flutter con Git y GitHub.

## Cómo ejecutarla

1. flutter pub get
2. flutter run

## Reglas de trabajo

1. Nadie hace commit directo en main. Todo entra por Pull Request.
2. Cada tarea es una issue y cada issue tiene su propia rama.
3. Nombres de rama: feature/descripcion-corta, fix/descripcion-corta, docs/descripcion-corta.
4. Commits pequeños con la convención tipo: descripción en infinitivo (feat, fix, docs, refactor, chore).
5. Un PR = una funcionalidad, con descripción y Closes #n para cerrar la issue.
6. El PR no se fusiona hasta que el CI esté en verde y el supervisor lo apruebe.
7. Nunca se suben contraseñas, tokens, llaves ni datos de la organización.