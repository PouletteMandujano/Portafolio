# 👩‍💻 Portafolio Técnico - Poulette Mandujano
**Perfil:** Talento Junior Tech | Backend Developer (Python & Django)

Aquí comparto mi experiencia resolviendo problemas complejos a través de código limpio, bases de datos relacionales y el framework Django.

---

## 💻 Mis Proyectos
1. **Modelado y Base de Datos "Alke Wallet":** Diseño de un Modelo Entidad-Relación (ERD), normalizado hasta la 3FN, e implementado usando sentencias DDL y DML en SQL.
2. **Task Manager (App Web Django):** Aplicación web para gestión de proyectos y tareas con autenticación de usuarios (`LoginRequiredMixin`), operaciones CRUD y Bootstrap 5.
3. **Desarrollo Backend "Alke Wallet":** Construcción del backend en Django, utilizando el ORM y transacciones atómicas seguras.

---

## 🌟 Caso de Estudio Destacado: Alke Wallet (Backend)

* **Breve descripción:** Desarrollo de una aplicación web completa que simula una billetera digital, permitiendo registro, consulta de saldos, transferencias y un historial de transacciones.
* **El Desafío:** Garantizar la integridad financiera durante una transferencia (Transacciones ACID). Si el sistema fallaba a la mitad, existía el riesgo de descontar dinero del origen sin sumarlo al destino. Además, la aplicación debía protegerse contra ataques de inyección y vulnerabilidades CSRF.
* **Solución técnica:** Implementé el decorador `@transaction.atomic` de Django para asegurar que los movimientos de saldo se ejecutaran en un bloque único seguro. Validé formularios con tokens CSRF y utilicé consultas nativas (`.raw()`) para reportes financieros.
* **Stack Tecnológico:** Python, Django, SQLite, HTML/CSS, Git.
* **Principales aprendizajes:** Consolidé el entendimiento del patrón Modelo-Vista-Plantilla (MVT), la normalización de datos y la creación de scripts de automatización (`poblar_datos.py`).
* **Métricas de impacto:** 
  * Pruebas unitarias superadas (`test gestion`), garantizando exactitud matemática.
  * Flujo de transferencia comprobado y seguro al 100%.
* **Habilidades aplicadas:** Programación en Python, diseño SQL, manejo avanzado de Django y testing unitario.
* **Justificación:** Elegí este proyecto porque integra todo mi recorrido técnico. Aborda una problemática crítica (manejo de dinero) y demuestra mis capacidades End-to-End, desde el diagrama ERD hasta el código funcional en producción.

---
