# face_detection_realtime Project

## Description

This project is a web application developed using Flask. It requires certain Python libraries to be installed. This README provides instructions for setting up the project environment on macOS.

## Requirements

- Python 3.x
- `pip3`

## Installation Instructions

### 1. **Install Python**

Ensure Python 3 is installed on your macOS. If not, you can install it using Homebrew:

```bash
brew install python@3
```

### 2. **Set Up a Virtual Environment (Recommended)**

Create and activate a virtual environment to manage your dependencies. This keeps your project's libraries isolated from the global Python environment.

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. **Install Required Libraries**

Install the required libraries using `pip3`. These libraries include Flask and any other dependencies.

```bash
pip3 install flask
pip3 install opencv-python
pip3 install fer
pip3 install tensorflow
```

### 4. **Run the Application**

Navigate to the directory containing your `app.py` file and run the application:

```bash
python3 app.py
```

The application should now be running. You can access it in your web browser at `http://127.0.0.1:5000/`.

### 5. **Additional Notes**

- If you encounter issues with missing libraries, ensure they are installed using `pip3`.
- If you see any errors related to TensorFlow or other dependencies, refer to their respective documentation for troubleshooting.

### 6. **Troubleshooting**

- **ModuleNotFoundError**: If you get errors about missing modules (e.g., `ModuleNotFoundError: No module named 'flask'`), make sure the library is installed in the correct environment.
- **Permission Issues**: If you face permission issues, you can use `--user` with `pip3` to install libraries for your user only:

  ```bash
  pip3 install flask --user
  ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
