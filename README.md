# Building Documentation

To build the documentation:

1. Clone the project to the same directory of the docs folder.

   ```
   git clone -r git@github.com:walkerchi/tensormesh_sphinx_theme.git
   ```
2. Install the requirements in the **TensorMesh** Environment:

   ```
   pip install -r requirements.txt
   ```

3. Generate the documentation file via:
   ```
   make html
   ```

The documentation is now available to view by opening `docs/index.html`.
