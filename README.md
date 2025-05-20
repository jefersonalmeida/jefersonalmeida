```typescript
class Person {
    name          = 'Jeferson Almeida';
    username      = 'jefersonalmeida';
    title         = 'Software Engineer';
    location      = 'Mato Grosso, Brazil';
    languages     = ['Portuguese (native)', 'English (basic)'];
}

class Skills {
    programming   = ['Java', 'TypeScript', 'PHP', 'Go'];
    databases     = ['SQL', 'MongoDB', 'Redis'];
    frameworks    = ['Spring', 'Quarkus', 'NestJS', 'Laravel', 'Angular', 'React'];
    devops        = ['Docker', 'Kubernetes', 'Argo CD', 'Ansible', 'Terraform', 'GitHub Actions'];
    messaging     = ['RabbitMQ', 'Kafka'];
    security      = ['Keycloak', 'OAuth2', 'JWT'];
    monitoring    = ['Prometheus', 'Grafana', 'Promtail', 'Loki'];
    cloud         = ['AWS', 'GCP', 'Azure', 'Private'];
    methodologies = ['Scrum', 'Kanban'];
    testing       = ['JUnit', 'Mockito', 'Cypress'];
}

const me = {...new Person, ...new Skills};
```
