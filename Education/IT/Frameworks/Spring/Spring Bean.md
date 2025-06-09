
 
 Scopes :
 - Local 
	 - Singleton
	 - prototype
 - web-aware
	 - request
	 - session
	 - global
 - Other
	 - Application 
	 - WebSocket
	 - custom


Life cycle
- Container Started
- Bean Instantiated
	- Dependencies Injected
	- setBeanName()
	- setBeanFactory()
	- setApplicationContext()
	- preinitialization()
	- @PostConstruct
	- .afterPropertiesSet()
	-  init() 
- Bean is Ready
- Custom utility method
- Custom destroy() method