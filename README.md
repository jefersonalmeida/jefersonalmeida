```javascript
class Person {
    name       = 'Jeferson Almeida';
    nickname   = 'jefersonalmeida';
    title      = 'Software Engineer';
    location   = 'Mato Grosso, Brazil';
}

class Skills {
    languages  = ['Java', 'JavaScript', 'PHP', 'Go'];
    databases  = ['*SQL', 'MongoDB', 'Redis'];
    frameworks = ['Spring', 'Quarkus', 'NestJS', 'Laravel', 'Angular'];
    tools      = ['Docker', 'Kubernetes', 'RabbitMQ', 'Kafka', 'Keycloak', 'Ansible', 'Terraform'];
    clouds     = ['AWS', 'GCP', 'Azure'];
}

const me = Object.assign(new Person, new Skills);
```
