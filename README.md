# Graph Representation Project

This project is designed for visualizing graphs using the PlantUML language. It represents nodes and their connections in a diagram format.

## Contents

- [Description](#description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Testing](#testing)
- [License](#license)

---

## Description

The project implements a simple mechanism for displaying graphs using PlantUML. You can create nodes, link them, and visualize the graph as a convenient diagram.

## Requirements

To run and successfully use the project, you will need:

- Python 3.12.8
- Installed packages:
  - `pyparsing`
  - `pytest`
  - `PyYAML`
  - `pip`
- PlantUML (installed locally or accessible via the web)

## Installation

1. Clone the repository:
   ```sh
   git clone <repository-URL>
   ```

2. Navigate to the project directory:
   ```sh
   cd <directory-name>
   ```

3. Install all necessary dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   Ensure all required packages are listed in `requirements.txt`.

## Usage

Run the script with the following syntax:
  ```bash
  python script.py <graphviz_path> <package_name> <depth>
  ```

- **`<graphviz_path>`**: Path to the Graphviz executable.
- **`<package_name>`**: Name of the package to visualize.
- **`<depth>`**: Depth of the graph to visualize.

## Example

Example PlantUML file:
```plantuml
@startuml
"abcdef1234567890" --> "34567890abcdef"
"34567890abcdef" --> "567890abcdef"
@enduml
```

This code creates a simple graph with nodes and connections.

The generated diagram will look like this:
```
abcdef1234567890 ---> 34567890abcdef ---> 567890abcdef
```

## Testing

![image_2024-11-17_16-24-13](https://github.com/user-attachments/assets/625021fb-a507-4b74-b1f6-685f80b13b7d)

![firefox_dependencies](https://github.com/user-attachments/assets/2fa28533-860d-4d9b-9cd3-7aea09ac87aa)


## License

This project is distributed under the [MIT License](LICENSE).
