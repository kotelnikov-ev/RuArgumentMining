# RuArgumentMining
Репозиторий содержит ресурсы и модели, разработанные в рамках проекта [РНФ № 22-21-00885](https://rscf.ru/project/22-21-00885/):
- модель ArgBERT для бинарной классификации предложений на "аргумент" / "не аргумент";
- модель ArgBERT-premise для бинарной классификации аргументативных предложений на "аргумент за" / "аргумент против";
- модель AspBERT для классификации предложений по 16 аспектам (многоклассовая классификация);
- 7 моделей Random Forest для многозначной классификации (multilabel classification) по 7 аспектам: "Безопасность", "Влияние на здоровье", "Влияние на психику", "Надежность", "Отношение властей", "Уровень жизни", "Эффективность";
- корпус из 5000 предложений, содержащий разметку по аргументации:
1) является ли предложение аргументом по отношению к заданному утверждению;
2) если предложение является аргументом, то выражена позиция «за» или «против»;
3) если предложение является аргументом, то какой упоминается аспект.
