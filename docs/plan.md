# Service plan and architecutre

## Planned services

1. Content Service
   Provide content, such as text, images and so on.

   Content can be divided onto several formats:
      * **simple-mocks.errors** - list of errors localizations.
        * Format is:
          * **systemCode** - source system code
          * **errorCode** - error unique code
          * **errorTitle** - error localized title
          * **errorSystemMessage** - error system message, for logs
          * **errorUserMessage** - error localized message, for user.
      * **simple-mocks.localizations** - list of localizations.
        * Format is:
          * **systemCode** - source system code
          * **localizationCode** - localization code
          * **localizationText** - locaization text

   Provided APIs:
      * **api-content** - general purpose content API
      * **api-error** - for **simple-mocks.errors**
      * **api-localization** - for **simple-mocks.localizations**

2. Async Service
   Provide ability to execute async tasks using persitent data base.

3. Session Service
   Provide ability to store data into persistent storage.

4. Storage Service
   Provide ability to store files.

5. Document Render Service
   Provide ability to render documents via one of supported render engine: freemarker, jasper, jolt.

6. Application Framework
   Provide ability to create application, catacolize whem and use via Web UI or Console.

   
