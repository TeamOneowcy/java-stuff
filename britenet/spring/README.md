# Spring :leaves:

## Bean :cookie:

Bean jest obiektem zarządzanym przez kontener IoC :cake:

> Tworząc Beana możemy go później wstrzyknąć

## Kontener IoC :cake:

Kontener IoC *Inveresion of Control* zarządza cyklem życia beanów

### Pozwala na:

- automatyczne tworzenie obiektów,
- wstrzykiwanie zależności

> Wstrzykiwanie zależności to dostarczanie beana :cookie: przez IoC :cake:

## Kontenery IoC :cake::cake:  w Springu

Są dwa typy kontenerów IoC w Springu.

### BeanFactory

BeanFactory wykorzystuje wzorzec Factory i dostarcza Beany :cookie:

### Application context

Application context jest interface'em rozszerzającym BeanFactory

Dziedziczy zarządzanie Beanami od BeanFactory, a także:

- wspiera adnotacje,
- obsługuje zdarzenia,
- obsługuje transakcje i AOP - *Aspect oriented programming*,
- wspiera BeanFactoryPostProcessor - *Pozwala na bezpośrednie modyfikowanie i nadpisywanie konfiguracji beanów*


## Spring Boot :leaves::bulb:

Spring Boot dostarcza automatyczną konfigurację i implementacje użyte w kontekście.