# Python-crash-course-
once i register the model with the admin site I try to follow the next step define the entry model but sistem provide next answer 

(ll_env) C:\learning_log>python manage.py runserver
Traceback (most recent call last):
  File "manage.py", line 21, in <module>
    main()
  File "manage.py", line 17, in main
    execute_from_command_line(sys.argv)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\__init__.py", line 381, in execute_from_command_line
    utility.execute()
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\__init__.py", line 375, in execute
    self.fetch_command(subcommand).run_from_argv(self.argv)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\base.py", line 323, in run_from_argv
    self.execute(*args, **cmd_options)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\commands\runserver.py", line 60, in execute
    super().execute(*args, **options)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\base.py", line 364, in execute
    output = self.handle(*args, **options)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\core\management\commands\runserver.py", line 67, in handle
    if not settings.DEBUG and not settings.ALLOWED_HOSTS:
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\conf\__init__.py", line 79, in __getattr__
    self._setup(name)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\conf\__init__.py", line 66, in _setup
    self._wrapped = Settings(settings_module)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\conf\__init__.py", line 157, in __init__
    mod = importlib.import_module(self.SETTINGS_MODULE)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\importlib\__init__.py", line 127, in import_module
    return _bootstrap._gcd_import(name[level:], package, level)
  File "<frozen importlib._bootstrap>", line 1006, in _gcd_import
  File "<frozen importlib._bootstrap>", line 983, in _find_and_load
  File "<frozen importlib._bootstrap>", line 967, in _find_and_load_unlocked
  File "<frozen importlib._bootstrap>", line 677, in _load_unlocked
  File "<frozen importlib._bootstrap_external>", line 728, in exec_module
  File "<frozen importlib._bootstrap>", line 219, in _call_with_frames_removed
  File "C:\learning_log\learning_log\settings.py", line 16, in <module>
    django.setup()
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\__init__.py", line 19, in setup
    configure_logging(settings.LOGGING_CONFIG, settings.LOGGING)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\conf\__init__.py", line 79, in __getattr__
    self._setup(name)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\conf\__init__.py", line 66, in _setup
    self._wrapped = Settings(settings_module)
  File "C:\Users\Allen\AppData\Local\Programs\Python\Python37-32\lib\site-packages\django\conf\__init__.py", line 176, in __init__
    raise ImproperlyConfigured("The SECRET_KEY setting must not be empty.")
django.core.exceptions.ImproperlyConfigured: The SECRET_KEY setting must not be empty.

(ll_env) C:\learning_log>
