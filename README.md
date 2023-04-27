```javascript
class Person {
    name       = 'Jeferson Almeida';
    nickname   = 'jefersonalmeida';
    title      = 'Software Engineer';
    location   = 'Mato Grosso, Brazil';
}

class Skills {
    languages  = ['Java', 'TypeScript', 'JavaScript', 'PHP'];
    databases  = ['*SQL', 'MongoDB', 'Redis'];
    frameworks = ['Spring', 'Quarkus', 'NestJS', 'Laravel', 'Angular', 'React'];
    tools      = ['Docker', 'Kubernetes', 'RabbitMQ', 'ActiveMQ', 'Kafka'];
    clouds     = ['AWS', 'GCP', 'Azure'];
}

const me = Object.assign(new Person, new Skills);
```
