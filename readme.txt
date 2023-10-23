Файлы в Zip архиве. Ибо гитхаб отказывается загружать больше 100 файлов "Yowza, that’s a lot of files. Try uploading fewer than 100 at a time."




log - admin
pass - admin


Для работы Google OAuth, client_id и secret нужно прописывать в settings.py, из social application в панели администратора не работает.

# Provider specific settings
SOCIALACCOUNT_PROVIDERS = {
    'google': {
        # For each OAuth based provider, either add a ``SocialApp``
        # (``socialaccount`` app) containing the required client
        # credentials, or list them here:
        'APP': {
            'client_id': '527475780160-9p418libvm3494d4g26cdgb3vfafqqdr.apps.googleusercontent.com',
            'secret': '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',
            'key': ''
        }
    }
}