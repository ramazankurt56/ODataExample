# OData Projeleri

Bu depo, OData protokolünü öğrenmek ve uygulamak amacıyla geliştirilmiş birkaç basit projeyi içerir. Projeler, .NET Core ve Angular kullanılarak oluşturulmuştur.

## Proje Yapısı

### ODataExample.Client
- **Angular** kullanılarak geliştirilmiş istemci tarafı uygulamasıdır.
- **Kendo UI Angular** bileşenleri ve **ag-grid-angular** kütüphanesi ile zengin bir kullanıcı arayüzü sağlar.
- OData protokolü ile uyumlu veri işlemleri gerçekleştirir.

### ODataExample.Server
- **ASP.NET Core WebAPI** kullanılarak geliştirilmiş sunucu tarafı uygulamasıdır.
- **OData** protokolü ile RESTful API oluşturulmuştur.
- **Entity Framework Core** veritabanı işlemleri için kullanılır.
- **Bogus** kütüphanesi ile sahte veri oluşturulur.
- API dokümantasyonu için **Swashbuckle (Swagger)** kullanılmıştır.

### ODataExample2.MinimalAPI
- **Minimal API** yaklaşımı kullanılarak geliştirilmiş basit bir OData sunucusu.
- OData işlemlerini daha hafif ve minimal bir yapıyla gerçekleştirmek için tasarlanmıştır.
