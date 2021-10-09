---
id: 12971
title: SecretStorage
date: 2020-02-14
author: auto-mik
layout: post
permalink: /python/SecretStorage-3.3.1/
published: true
image:
categories:
   - python
tags:  
   - SecretStorage
---
_**Package details:**_









**name**: SecretStorage



**version**: 3.3.1



**description**: Python bindings to FreeDesktop.org Secret Service API



**long_description**: file: README.rst



**long_description_content_type**: text/x-rst



**author**: Dmitry Shachnev





**number of Python files**: 18



---





- `SecretStorage-3.3.1/setup.py` 

   (61 characters, 7 words)

    _imported modules:_ `setuptools` 





- `SecretStorage-3.3.1/secretstorage/exceptions.py` 

   (1576 characters, 165 words)

    _defined classes:_ `SecretStorageException`, `SecretServiceNotAvailableException`, `LockedException`, `ItemNotFoundException`, `PromptDismissedException` 





- `SecretStorage-3.3.1/secretstorage/dhcrypto.py` 

   (2417 characters, 316 words)

    _imported modules:_ `hmac`, `math`, `os`, `hashlib`, `typing` 

    _defined classes:_ `Session` 

    _defined functions:_ `int_to_bytes` 



- `SecretStorage-3.3.1/secretstorage/util.py` 

   (6002 characters, 607 words)

    _imported modules:_ `os`, `typing`, `jeepney`, `jeepney.io.blocking`, `secretstorage.defines`, `secretstorage.dhcrypto`, `secretstorage.exceptions`, `cryptography.hazmat.primitives.ciphers`, `cryptography.hazmat.backends` 

    _defined classes:_ `DBusAddressWrapper` 

    _defined functions:_ `open_session`, `format_secret`, `exec_prompt`, `unlock_objects`, `add_match_rules` 



- `SecretStorage-3.3.1/secretstorage/collection.py` 

   (8408 characters, 819 words)

    _imported modules:_ `typing`, `jeepney.io.blocking`, `secretstorage.defines`, `secretstorage.dhcrypto`, `secretstorage.exceptions`, `secretstorage.item`, `secretstorage.util` 

    _defined classes:_ `Collection` 

    _defined functions:_ `create_collection`, `get_all_collections`, `get_default_collection`, `get_any_collection`, `get_collection_by_alias`, `search_items` 



- `SecretStorage-3.3.1/secretstorage/__init__.py` 

   (3180 characters, 315 words)

    _imported modules:_ `jeepney.bus_messages`, `jeepney.io.blocking`, `secretstorage.collection`, `secretstorage.item`, `secretstorage.exceptions`, `secretstorage.util` 

    _defined functions:_ `dbus_init`, `check_service_availability` 



- `SecretStorage-3.3.1/secretstorage/defines.py` 

   (824 characters, 65 words)





- `SecretStorage-3.3.1/secretstorage/item.py` 

   (5241 characters, 513 words)

    _imported modules:_ `typing`, `jeepney.io.blocking`, `secretstorage.defines`, `secretstorage.dhcrypto`, `secretstorage.exceptions`, `secretstorage.util`, `cryptography.hazmat.primitives.ciphers`, `cryptography.hazmat.backends` 

    _defined classes:_ `Item` 





- `SecretStorage-3.3.1/tests/test_context_manager.py` 

   (813 characters, 71 words)

    _imported modules:_ `contextlib`, `unittest`, `secretstorage`, `secretstorage.collection` 

    _defined classes:_ `ContextManagerTest` 





- `SecretStorage-3.3.1/tests/test_dhcrypto.py` 

   (528 characters, 58 words)

    _imported modules:_ `unittest`, `secretstorage.dhcrypto` 

    _defined classes:_ `ConversionTest` 





- `SecretStorage-3.3.1/tests/test_unlocking.py` 

   (1164 characters, 84 words)

    _imported modules:_ `unittest`, `secretstorage`, `secretstorage.util`, `secretstorage.exceptions` 

    _defined classes:_ `LockingUnlockingTest` 





- `SecretStorage-3.3.1/tests/test_exceptions.py` 

   (1101 characters, 86 words)

    _imported modules:_ `unittest`, `secretstorage`, `secretstorage.exceptions` 

    _defined classes:_ `ExceptionsTest` 





- `SecretStorage-3.3.1/tests/__init__.py` 

   (0 characters, 0 words)





- `SecretStorage-3.3.1/tests/test_item.py` 

   (3347 characters, 260 words)

    _imported modules:_ `unittest`, `time`, `secretstorage` 

    _defined classes:_ `ItemTest` 





- `SecretStorage-3.3.1/tests/run_tests.py` 

   (1027 characters, 91 words)

    _imported modules:_ `os.path`, `sys`, `subprocess`, `unittest`, `secretstorage` 





- `SecretStorage-3.3.1/tests/test_collection.py` 

   (2856 characters, 234 words)

    _imported modules:_ `unittest`, `secretstorage`, `secretstorage`, `secretstorage`, `secretstorage.util`, `secretstorage.exceptions` 

    _defined classes:_ `CollectionTest`, `MockCollectionTest` 





- `SecretStorage-3.3.1/tests/cleanup_test_items.py` 

   (315 characters, 29 words)

    _imported modules:_ `contextlib`, `secretstorage` 





- `SecretStorage-3.3.1/docs/conf.py` 

   (2398 characters, 323 words)

    _imported modules:_ `sys` 

