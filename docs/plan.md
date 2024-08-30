# Service plan and architecutre

## Planned services

1. Content Service
   Provide content, such as text, images and so on.

   Content can be divided onto several formats:
   *  simple-mocks.errors - list of errors localizations.
     * Format is:
       * systemCode - source system code
       * errorCode - error unique code
       * errorTitle - error localized title
       * errorSystemMessage - error system message, for logs
       * errorUserMessage - error localized message, for user.
   *  simple-mocks.localizations - list of localizations.
     * Format is:
       * systemCode - source system code
       * localizationCode - localization code
       * localizationText - locaization text
