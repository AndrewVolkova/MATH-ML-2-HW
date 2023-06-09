Линейная алгебра в контексте линейных методов.
Прогнозирование выработки газа на скважинах


 ### Решаемая задача

У Василия, основателя компании «Газ-Таз-Ваз-Нефть», дела идут в гору: у него уже функционирует 200 скважин для добычи газа. В этом году он открывает 30 новых скважин. Однако в целях оптимизации расходов и повышения дохода Василию необходимо оценить, сколько денег будет приносить ему каждая из скважин, а также понять, какие факторы (параметры скважин) потенциально сильнее всего повлияют на объём добычи газа. Для этого Василий решил нанять вас как специалиста в области Data Science.

* Построить модель на базе Линейной регрессии:
  * Без полиномиальных признаков
  * С полиномиальными признаками
  * С регуляризацией Lasso
  * С регуляризацией Ridge
  * Mix L1 L2 - ElasticNet
* Также, задача работы показать знания в подборе гмперпараметров параметров для вышеуказанных моделей
  
  

### Информация о данных

* Well — идентификатор скважины;
* Por — пористость скважины (%);
* Perm — проницаемость скважины;
* AI — акустический импеданс ($кг/м^2 * 10^6$);
* Brittle — коэффициент хрупкости скважины (%);
* TOC — общий органический углерод (%);
* VR — коэффициент отражения витринита (%);
* Prod — добыча газа в сутки (млн. кубических футов).
  
###  Использовались

  Библиотеки подборки гиперпараметров:
  * Optuna

### Результаты

* Результаты и выводы по ходу выполнения в рабочем ноубуке




