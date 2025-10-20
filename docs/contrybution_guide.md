## Как вносить изменения
1. Всегда создавайте отдельную ветку от main.
2. Делайте небольшие коммиты с понятными сообщениями.
3. Открывайте Pull Request (PR) в main. Прямой push в main запрещен (ветка защищена).
4. Дождитесь нужного числа approve’ов, закройте все комментарии и только потом мержьте.

Рекомендуемый цикл:
```bash
git checkout -b feature/<topic>
# ... изменения ...
git add -A
git commit -m "feat: add initial questionnaire"
git push -u origin feature/<topic>
# Открыть PR в GitHub UI
