# Turkish Translation Glossary

> **Living glossary** - Updated after each section completion.
> Translator and Reviewer MUST check this before working.
> Only technical terms worth standardizing. Alphabetically sorted.

---

## Core Architecture Terms

| English | Turkish | Context |
|---------|---------|---------|
| architecture | mimari | |
| architecture (software) | yazılım mimarisi | full term |
| architecture decision | mimari karar | also: tasarım kararı |
| architecture pattern | mimari örüntü | |
| architecture view | mimari görünüm | |
| building block | yapı taşı | general structural element |
| component | bileşen | specific building block type |
| cross-cutting concern | kesişimsel ilgi alanı | |
| cross-cutting concept | kesişimsel kavram | |
| dependency | bağımlılık | |
| design | tasarım | |
| design principle | tasarım ilkesi | |
| influencing factor | etki eden etmen | |
| interface | arayüz | |
| module | modül | |
| pattern | örüntü | |
| structure | yapı | |
| specification | belirtim | |

## Quality Attributes

| English | Turkish | Context |
|---------|---------|---------|
| availability | erişilebilirlik | |
| maintainability | bakım yapılabilirlik | |
| modifiability | değiştirilebilirlik | |
| performance | performans | |
| persistence | süreğenlik | |
| portability | taşınabilirlik | |
| quality attribute | kalite niteliği | |
| reliability | güvenilirlik | |
| security | güvenlik | |
| testability | test edilebilirlik | |
| usability | kullanılabilirlik | |


## Stakeholders & Requirements

| English | Turkish | Context |
|---------|---------|---------|
| constraint | sınır koşulu | |
| functional requirement | işlevsel gereksinim | |
| requirement | gereksinim | |
| quality requirement | kalite gereksinimi | |
| stakeholder | paydaş | |

## Documentation

| English | Turkish | Context |
|---------|---------|---------|
| documentation | dokümantasyon | |
| notation | gösterim | |
| view | görünüm | architectural view |
| architectural view | mimari görünüm | architectural view |

## Curriculum Terms

| English | Turkish | Context |
|---------|---------|---------|
| curriculum | müfredat | |
| learning goal | öğrenme hedefi | |
| training | eğitim | |

## Other Technical Terms

| English | Turkish | Context |
|---------|---------|---------|
| cohesion | bağdaşıklık | |
| coupling | bağlaşım | |
| encapsulation | sarma | |
| information hiding | bilgi gizleme | |
| runtime | çalışma zamanı | |
| trade-off | ödünleşim | |
| heuristics | buluşsal yöntemler | |
| static typing | statik tipleme | |
| dynamic typing | dinamik tipleme | |
| hashtable | özet tablosu | |
| dictionary | sözlük | |
| map | eşlem | |
| imperative | emirsel | |
| imperative programming | emirsel programlama | |
| declarative | bildirimsel | |
| declarative programming | bildirimsel programlama | |
| functional | işlevsel | |
| functional programming | işlevsel programlama | |
| high level programming language | yüksek seviyeli programlama dili | |
| low level programming language | düşük seviyeli programlama dili | |
| refinement | safileştirme | |
| iteration | yineleme | |
| iterative development | yinelemeli geliştirme | |
| incremental | artımlı | |
| incremental development | artımlı geliştirme | |
| top-down | tepeden aşağı | |
| bottom-up | tabandan yukarı | |
| agile | çevik | |
| global state | genel durum | |
| global variable | genel değişken | |
| local state | yerel durum | |
| local variable | yerel değişken | |
| error handling | hata işleme | |
| exception handling | istisna işleme | |
| explicit | belirtik | |
| implicit | örtük | |
| cohesion | bağdaşıklık | |
| domain-driven | alan odaklı | |
| model-based | model tabanlı | |
| run-time | yürütüm zamanı | |
| compile time | derleme zamanı | |
| seperation of concerns | sorumlulukların ayrılması | |
| open-closed principle | açıklık-kapalılık ilkesi | |
| dependency inversion principle | bağımlılık evirimi ilkesi | |
| the principle of least surprise | en az sürpriz ilkesi | |
| Liskov’s substitution principle | Liskov ikame ilkesi | |
| single responsibility principle | tek sorumluluk ilkesi | |
| interface segregation principle | arayüz ayrım ilkesi | |
| dependency injection | bağımlılık enjeksiyonu | |
| implementation | gerçekleştirme | |
| application | uygulama | |
| synchronous | eşzamanlı | |
| asynchronous | eszamansız | |
| binary | ikilik | |
| non-binary | ikilik dışı | |
| function call | işlev çağırma | |
| procedure | yordam | |
| stored procedure | saklı yordam | |
| remote procedure call | uzaktan yordam çağırma | |
| batch | yığın | |
| streaming | akışlandırma | |
| service interface | hizmet arayüzü | |
| concurrency | eşzamanlılık | |
| build | derleme | |
| deployment | konuşlandırma | |
| release | azat | |









---

## Terms NEVER to Translate (Keep in English)

These terms must remain in English, matching the German (DE) version:

### Certification & Organization
- CPSA, CPSA-F
- Certified Professional for Software Architecture
- Foundation Level, Advanced Level
- iSAQB, IREB, OMG, IEEE, ISO

### Architectural Patterns
- Layers, Pipes and Filters, Microservices
- Blackboard, Broker, CQRS, Event Sourcing
- Dependency Injection, Plugin
- MVC, MVVM, MVU, PAC
- Ports and Adapters, Onion/Hexagonal/Clean Architecture
- SOA, Remote Procedure Call
- Black box, White box

### Technical Terms (Keep English)
- REST, REpresentational State Transfer
- GraphQL, SOAP, WS-*

### Design Patterns
- Combinator, Adapter, Facade, Proxy
- Interpreter, Observer, Visitor
- Template Method, Strategy

### Principles
- SOLID (all 5), DRY, KISS, YAGNI, CUPID
- Postel's Law, Conway's Law
- Information Hiding, Separation of Concerns

### Standards & Methodologies
- ISO 42010, ISO 25010, ISO 25019
- UML, ArchiMate, SysML, BPMN, C4
- arc42, ADR, ATAM
- REST, SOAP, GraphQL, HTTP, TCP/IP
- POSA, PoEAA, GOF

---

## Update Log

| Section | Date | Terms Added |
|---------|------|-------------|
| Initial | - | Seeded from glossary-german-to-turkish.csv |
| 01-what-to-expect | 2025-12-05 | yazılım mimarisi, müfredat, öğrenme hedefi, eğitim |
| 03-prerequisites | 2025-12-05 | tür sistemi, modülerleştirme, ön koşul |

