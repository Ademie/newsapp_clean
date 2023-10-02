# newsapp_clean

Clean architecture is a blueprint for modular system which simply follows separation of concern

>>CORE(Shared resources)
    >>ERROR
    >>NETWORK
    >>USECASES
    >>UTIL
>>CONFIG(Themes, routes, etc)
    >>ROUTES
    >>THEME
>>FEATURE
    >>FEATURE_NAME
        >>DATA
            >>MODELS
            >>REPOSITORIES (implementation of repo in domain layer)
            >>SOURCES
                >>REMOTE
                >>LOCAL
        >>DOMAIN
            >>ENTITIES/MODELS (data types or classes used)
            >>REPOSITORIES (Abstact classes and contracts)
            >>USECASES
        >>PRESENTATION
            >>PAGES
            >>WIDGETS
            >>BLOC
