                                   SELENIUM WEBDRIVER
                                           │
 ┌─────────────────────────────────────────┼─────────────────────────────────────────┐
 │                                         │                                         │
¿Qué es?                              Tipos de Selenium                        Arquitectura
 │                                         │                                         │
- Automación de navegadores.        - Selenium IDE                        - Test Script (código)
- Simula acciones reales.           - Selenium WebDriver                  - Protocolo WebDriver (W3C)
- Pruebas web automatizadas.        - Selenium Grid                       - Browser Driver (ChromeDriver, etc.)
                                                                                 │
                                                                                 → Control del navegador
 └─────────────────────────────────────────┼─────────────────────────────────────────┘
                                           │
                                Localizadores de Elementos
                                           │
                     - id              (más recomendado)
                     - name
                     - className
                     - tagName
                     - linkText / partialLinkText
                     - cssSelector     (rápido y flexible)
                     - xpath           (muy flexible)
                                           │
 ┌─────────────────────────────────────────┼─────────────────────────────────────────┐
 │                                         │                                         │
 Comandos Principales                 Navegación                          Interacción
 │                                         │                                         │
- click()                            - get()                              - sendKeys()
- sendKeys()                         - navigate()                         - clear()
- clear()                            - back(), forward()                  - submit()
- getText()                          - refresh()
                                           │
                               Otros Comandos Importantes
                                           │
                        - Esperas: implícitas y explícitas
                        - Manejo de alertas y ventanas
                        - Acciones avanzadas (Actions)
                        - Captura de pantalla
                        - close() / quit()
