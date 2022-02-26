# PythonProjectDirectory (File Structure)

o <python_project_name>/
- /src/__init__.py
- /ext/__init__.py
- /doc/__init__.py
- /ide/__init__.py
- /bin/__init__.py
- /build/__init__.py
- /trash/__init__.py
- /__init__.py
- /.gitignore
- /README.md
- /LICENSE.md
- /setup_main.py
- /setup_test.py

o <python_project_name>/src/main/
- /<module_name-version>/<module_name>_<script_name>.py
- /<module_name-version>/__init__.py
- /<module_name-version>/README.md
- /__init__.py

o <python_project_name>/src/test/
- /<module_name-version>/<module_name>_<script_name>.py
- /<module_name-version>/__init__.py
- /<module_name-version>/README.md
- /__init__.py

o <python_project_name>/src/assembly/__init__.py
o <python_project_name>/src/config/__init__.py
o <python_project_name>/src/filters/__init__.py
o <python_project_name>/src/resources/__init__.py
o <python_project_name>/src/webapp/__init__.py

o <python_project_name>/ext/
- /<lib_name-version>/include/__init__.py
- /<lib_name-version>/<lib_name>
- /<lib_name-version>/__init__.py
- /<lib_name-version>/DOWNLOAD.md
- /__init__.py

o <python_project_name>/doc/
- /<doc_name>/__init__.py
- /<doc_name>/<doc_name-version>/<doc_name>_<script_name>.py
- /<doc_name>/<doc_name-version>/__init__.py
- /<doc_name>/<doc_name-version>/README.md
- /__init__.py

o <python_project_name>/ide/
- /__init__.py

o <python_project_name>/bin/
- /__init__.py

o <python_project_name>/build/
- /__init__.py


# Python File Copyright (.py)

o Put command below at start:
- FlowStructure version 0.01
- AKASHA framework - Main Program System (ClusterPipeline)
- Copyright (c) 2020 DevilTyreal. All rights reserved.
- 
- import sys
- sys.path.append('.')
- 
- """[enable path to be outside of directory]
- """
- 
- """[remove tests. for converting tests module to main - module]
- """
- 
- """[basic python module]
- """
- 
- """[global argument]
- """