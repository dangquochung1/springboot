# Self Study — Lộ trình học từ code thực hành

Bộ tài liệu này được tổng hợp từ **code thực hành và notes cá nhân** trong quá trình học, sắp xếp lại theo lộ trình từ cơ bản đến nâng cao.

<br />

## Mục lục

| # | Chủ đề | Nguồn code | Nội dung chính |
| - | ------ | ---------- | -------------- |
| 01 | [Maven và Quản lý Dependencies](01.%20Maven%20va%20Quan%20ly%20Dependencies.md) | `maven1.2` | Cấu trúc project, POM, mvn commands, đóng gói JAR |
| 02 | [Lombok và JSON](02.%20Lombok%20va%20JSON.md) | `fap-master-data.3lombokjson` | Boilerplate code, Lombok annotations, Jackson, JSON format |
| 03 | [JDBC — Kết nối Database thuần](03.%20JDBC%20Ket%20noi%20Database%20thuan.md) | `fap4jdbc` | DriverManager, PreparedStatement, ResultSet |
| 04 | [ORM, JPA và JPQL](04.%20ORM%20JPA%20va%20JPQL.md) | `fap.5.6ORM.JPA`, `fap.7.polymorphism` | Entity, EntityManager, persist/find/merge/remove, JPQL, Lambda |
| 05 | [Layer Architecture và Singleton](05.%20Layer%20Architecture%20va%20Singleton.md) | `fap_08_3_layerachitecture_n_singleton` | 3-layer, Repository pattern, JpaUtil Singleton |
| 06 | [Entity Relationships](06.%20Entity%20Relationships.md) | `fap.09.10.onetomany_bidirectional` | @OneToMany, @JoinColumn, Cascade, FetchType |
| 07 | [SOLID và Dependency Injection](07.%20SOLID%20va%20Dependency%20Injection.md) | `fap.11.12.SOLID.DI` | SRP, OCP, Tight vs Loose Coupling, Interface, DI manual |
| 08 | [Spring IoC Container](08.%20Spring%20IoC%20Container.md) | `fap.13_spring-to-go`, `fap13p2springboot-to-go` | @Component, @Autowired, ApplicationContext, Constructor/Setter/Field Injection |
| 09 | [Spring Boot Web — Controller và Thymeleaf](09.%20Spring%20Boot%20Web.md) | `fap15-javacoffee`, `fap16_17_19_MVC`, `fap19v2_noti`, `fap19v3_binding` | @Controller, @RestController, Model, Thymeleaf, GET/POST, Redirect |
| 10 | [Spring Security và JWT](10.%20Spring%20Security%20va%20JWT.md) | `mamnguqua-no-role-md`, `greeting-api` | SecurityFilterChain, JWT Authentication, Authorization, Role-based Access |

<br />

## Nguồn tham khảo

Toàn bộ code và notes nằm trong các folder cùng cấp:
- **Code comments bằng tiếng Việt** — ghi chú trực tiếp trong source code
- **Note.md** — notes riêng tại mỗi folder
- **mamnguqua-no-role-md** — bộ tài liệu Security chi tiết (~6000 dòng)

<br />
