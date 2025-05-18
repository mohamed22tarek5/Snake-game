
Here are the steps to accomplish the task:

1. **Open the terminal in the desired directory**:
   - If you're using a graphical interface, right-click inside the folder where `main.py` is located and select "Open Terminal Here" (the exact option may vary based on the operating system).

   - Alternatively, you can navigate to the folder via the terminal using the `cd` command:
     ```bash
     cd /path/to/your/project
     ```

2. **Create a `requirements.txt` file with the current environment's installed packages**:
   ```bash
   pip freeze > requirements.txt
   ```

3. **Install the packages listed in `requirements.txt`**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Python script**:
   ```bash
   python main.py
   ```

Following these steps will ensure that all the necessary dependencies are installed and your script runs correctly.
