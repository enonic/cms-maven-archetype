#example cms plugin

Example plugin will include one example of each of Enonic's extension types. 

1. FunctionLibrary     
2. HttpAutoLogin     
3. HttpController (simple example + one advanced example with thymeleaf view)    
4. HttpInterceptor     
5. HttpResponseFilter     
6. TaskHandler     
7. TextExtractor     
8. Authenticator     
9. RemoteUserStoreFactory

* Delete the extensions you don't want to use before starting your project, and implement the ones you want.
* If not using the ThymeleafController, delete
    * src/java/com.enonic.plugin.thymeleafcontroller package
    * src/resources/com.enonic.plugin.thymeleafcontroller package
    * src/resources/thymeleafcontroller-views folder.